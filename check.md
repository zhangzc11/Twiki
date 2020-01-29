Cards and inputs
---------------------

Result of running: `ValidateDatacards.py card_all_cut.txt`
```
[SetFlag] Changing value of flag "check-negative-bins-on-import" from 1 to 0
[SetFlag] Changing value of flag "workspaces-use-clone" from 0 to 1
================================
=======Validation results=======
================================
>>>There were no warnings of type  'up/down templates vary the yield in the same direction'
>>>There were no warnings of type  'At least one of the up/down systematic uncertainty templates is empty'
>>>There were  533 warnings of type  'Uncertainty has normalisation effect of more than 10.0%'
>>>There were no warnings of type  'Uncertainty probably has no genuine shape effect'
>>>There were  19 warnings of type  'Empty process'
```

Result of running: `ValidateDatacards.py card_all_bdt.txt`
```
================================
=======Validation results=======
================================
>>>There were no warnings of type  'up/down templates vary the yield in the same direction'
>>>There were no warnings of type  'At least one of the up/down systematic uncertainty templates is empty'
>>>There were  492 warnings of type  'Uncertainty has normalisation effect of more than 10.0%'
>>>There were no warnings of type  'Uncertainty probably has no genuine shape effect'
>>>There were  33 warnings of type  'Empty process'
```

On pre-fit Asimov toys
---------------------

   * Run `combine -M FitDiagnostics -t -1 --expectSignal 0 ` for card_all_cut.txt, we get: `Best fit r: 0.00794461  -0.00794461/+0.166131  (68% CL)`
   * Run `combine -M FitDiagnostics -t -1 --expectSignal 0 ` for card_all_bdt.txt, we get: `Best fit r: 0.00592608  -0.00592608/+0.131332  (68% CL)`
   * Run `python diffNuisances.py -a fitDiagnostics.root -g plots.root` for card_all_cut.txt, we see few nuisance parameters in the `b-only fit` having values of around `+0.00, 0.88`, those are: `LLDataErr02, PhFksSimStat04, PhFksSimStat05, PhFksSimStat09, QflpSimStat07, ttWSimStat08`; where `LLDataErr02` is the statisc of lost-lepton control region yields, and the rest are the MC statistics of the backgrounds.
   * Run `python diffNuisances.py -a fitDiagnostics.root -g plots.root` for card_all_bdt.txt, we see few nuisance parameters in the `b-only fit` having values of around `+0.00, 0.74-0.90`, those are: `FksFakeClosureMu, LLDataErr08, LLDataErr11, LLTFstat07, PhFksSimStat04`, which is similar as we see in card_all_cut.txt; where `FksFakeClosureMu` closure test systematics of the fake rate measurement, which is either the MC statistics or the fake rate difference in QCD and ttbar/W+jets samples; the rest are the statistics in either control region or the background MC.
   * Run `combine -M FitDiagnostics -t -1 --expectSignal 1` on card_all_cut.txt, we get: `Best fit r: 1.00705  -0.232877/+0.253905  (68% CL)`
   * Run `combine -M FitDiagnostics -t -1 --expectSignal 1` on card_all_bdt.txt, we get: `Best fit r: 1.00664  -0.195907/+0.211237  (68% CL)`
   * Run `python diffNuisances.py -a fitDiagnostics.root -g plots.root` on card_all_cut.txt (--expectSignal 1 fit), we see similar results as seen in the case of --expectSignal 0 
   * Run `python diffNuisances.py -a fitDiagnostics.root -g plots.root` on card_all_bdt.txt (--expectSignal 1 fit), we see similar results as seen in the case of --expectSignal 0 
  
Impacts
---------------------

Impact plots for card_all_cut.txt: https://zhicaiz.web.cern.ch/zhicaiz/sharebox/VVV/combine/impacts_cut.pdf

Impact plots for card_all_bdt.txt: https://zhicaiz.web.cern.ch/zhicaiz/sharebox/VVV/combine/impacts_bdt.pdf

   
