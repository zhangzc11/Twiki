
## Action List and Schedule (2018July Revive)

   * (done) smear MC time resolution to match with data
   * (done) add MET filters
   * (done) sumET reweight for events in the GJets control region
   * (done) plot of photon time distribution before and after smear
   * (done) check the impact of the MC time stamp smearing to the final limit
   * (in progress) send email to cms-exo-mcrequest about signal sample priority
   * answer Juliette's comments to AN_v2
   * cut-flow table
   * (done) time shift between MC and data
   * (done) pT or eta dependent MC time smearing
   * check CR yields in signal samples
   * check the uncertainty of sigma ieta ita fit
   * fix the error bars of the ratio plot
   * other backgrounds
   * check whether we can use QCD background only
   * show example of how the fit look like if we inject some signal
   * check the photon selection sequence for BDT: leading photon is the one with largest BDT?
   * check the photon selection sequence for cut-based: take the most time delayed photon in the EB candidates?
   * Systematics
   * regression on the photon incidence angle
   * monitor performance of 2018 triggers
   * Check the status of 2016 Data and MC re-MiniAOD: https://twiki.cern.ch/twiki/bin/view/CMSPublic/WorkBookMiniAOD#2016_Data_legacy_re_miniAOD_94X 
      * data: https://dmytro.web.cern.ch/dmytro/cmsprodmon/workflows.php?campaign=Data2016MiniAODv2
      
   * (heavy work) Run Kevin's selection with 2017 data to see if we get the same limits
   * "tag" method of background estimation (beam halo, ECAL spikes, cosmic ray, etc)


## Documentation

* external references

   * http://lanl.arxiv.org/pdf/1212.1838v2
   * (Franci thesis) http://www.phys.uniroma1.it/fisica/sites/default/files/DOTT_FISICA/MENU/03DOTTORANDI/TesiFin23/Franci.pdf
   * (how to determine photon TOF in data) http://cms.cern.ch/iCMS/jsp/db_notes/noteInfo.jsp?cmsnoteid=CMS%20AN-2010/212
   * http://cms.cern.ch/iCMS/analysisadmin/cadilines?line=EXO-11-035&tp=an&id=503&ancode=EXO-11-035
   * http://cms.cern.ch/iCMS/analysisadmin/cadilines?line=EXO-12-035&tp=an&id=961&ancode=EXO-12-035
   * http://cms.cern.ch/iCMS/analysisadmin/cadilines?line=EXO-14-017&tp=an&id=1422&ancode=EXO-14-017
   * (ATLAS, 8TeV) https://arxiv.org/abs/1409.5542
   * (Sasha, 19/11/15, ECAL pulse shape/timing) https://indico.cern.ch/event/402606/contributions/954968/attachments/1190385/1728029/151119_dpg_ledovskoy.pdf
   * (Badder, 28/06/17, timing in 2017 data) https://indico.cern.ch/event/648996/contributions/2638536/attachments/1484792/2304941/EcalTiming_28_06_2017.pdf
   * (Badder, 07/06/17, timing in 2017 data) https://indico.cern.ch/event/645066/contributions/2619112/attachments/1471403/2278145/EcalTiming_07_06_2017.pdf 
   * (Peter Hansan etc, 12/12/16, mean time before and after calibration) https://indico.cern.ch/event/578798/contributions/2403102/attachments/1386607/2110404/timing-2016-12-12.pdf
   * (Marc, 20/07/16, laser timing) https://indico.cern.ch/event/556862/contributions/2243754/attachments/1312883/1965288/MD_DPG_160720.pdf
   * (Andrea, 10/02/17, ECAL pulse) https://indico.cern.ch/event/614392/contributions/2478702/attachments/1413123/2163333/Feb-10_ECAL_Massironi.pdf
   * (Fabrice, 29/03/17, electron scale on eta) https://indico.cern.ch/event/627300/contributions/2535177/attachments/1436148/2208503/EtaScale_Cal_March2017_ref.pdf
   * (Wells, 25/11/16, tried to send exotic mother only to Geant4 which caused a problem for us) https://indico.cern.ch/event/590180/contributions/2380149/attachments/1377737/2093496/20161125_LLWGGeantSimulation.pdf 
      * (Badder, 13/09/17, 2017 Timing Calibration) https://indico.cern.ch/event/662921/contributions/2718756/attachments/1522547/2379256/EcalTiming_13_09_2017.pdf

* work of Cornell group

   * (Kevin, 01/07/16, ZeeTiming): https://indico.cern.ch/event/548294/contributions/2222985/attachments/1302338/1944764/timing_studies_dispho.pdf
   * (Kevin, 28/03/17, request to store OOT photons in MiniAOD) https://indico.cern.ch/event/626270/contributions/2529266/attachments/1434855/2206127/ootecal_xpog280317.pdf
   * (Kevin, 19/10/16, general update) https://indico.cern.ch/event/586184/contributions/2361887/attachments/1366401/2070031/dispho_update_041116.pdf
   * (Kevin, 01/12/16, general update) https://indico.cern.ch/event/571620/contributions/2327611/attachments/1381097/2099548/dispho_exowksp_2016.pdf
   * (Kevin, 26/06/17, signal sample request) https://indico.cern.ch/event/648483/contributions/2636137/attachments/1482688/2299957/mci_dispho_260617.pdf
   * (Kevin, 27/04/17, trigger 2017) https://indico.cern.ch/event/634617/contributions/2568309/attachments/1450696/2236803/dispho_trigger_update_270417.pdf
   * (Kevin, 27/04/18, analysis update) https://indico.cern.ch/event/723764/contributions/2976570/attachments/1641243/2621053/llp_270418_mcdermott_v5.pdf
   * (Kevin, 08/06/18, analysis update, with big improvement in limits) https://indico.cern.ch/event/734879/contributions/3031010/attachments/1664663/2668225/llp_mcdermott_080618_v3.pdf

* our own work documentation
   * (Analysis note, 2016 data) http://zhicaiz.web.cern.ch/zhicaiz/sharebox/notes/AN-17-318_temp.pdf
   * (Zhicai, 14/08/17, bug in cmssw about delayed SimHits) https://indico.cern.ch/event/659605/contributions/2689979/attachments/1507923/2350239/issue_CMSSW_delayed_SimHits_14Aug2017.pdf
   * (Daniel, 08/08/17, Zee timing studies) https://indico.cern.ch/event/656603/contributions/2683936/attachments/1505792/2346441/Zee.pdf
   * (Gillian, 08/08/17, analysis update) https://indico.cern.ch/event/656603/contributions/2683410/attachments/1505427/2346423/Week8.pdf
   * (Daniel, 21/08/17, Zee update) https://indico.cern.ch/event/660697/contributions/2695795/attachments/1510580/2355487/Zee.pdf 
   * (Zhicai, 21/08/17, GEN vs. RECO update) https://indico.cern.ch/event/660697/contributions/2695797/attachments/1510512/2355353/DelayedPhoton_21Aug2017.pdf 
   * (Daniel, 13/09/17, Zee at MoCa) https://indico.cern.ch/event/662921/contributions/2719766/attachments/1522639/2379427/Zee_MoCa.pdf
   * (Zhicai, 17/11/17, analysis update at LLP meeting) https://indico.cern.ch/event/681779/contributions/2793288/attachments/1560769/2456940/DelayedPhoton_17Nov2017.pdf
   * (Zhicai, 06/06/18, trigger efficiency plots for 2018A data) https://indico.cern.ch/event/734148/contributions/3027883/subcontributions/256606/attachments/1662766/2664948/DelayedPhoton_Trigger_2018A_06June2018_1.pdf
   
## Analysis Framework

## Rerunning MiniAOD in 9_2_X to retain out of time photons

* use CMSSW_9_2_5
* cmsDriver command: 

```
cmsDriver.py step3 --conditions 80X_mcRun2_asymptotic_2016_TrancheIV_v6 --mc --scenario pp --process PAT --era Run2_2016,run2_miniAOD_80XLegacy --eventcontent MINIAODSIM --runUnscheduled -s PAT --datatier MINIAODSIM --filein root://cmsxrootd.fnal.gov//store/mc/RunIISummer16DR80Premix/gluinoGMSB_M950_ctau100p0_TuneCUETP8M1_13TeV_pythia8/AODSIM/PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6-v1/120000/364903F7-84C8-E611-85AF-0CC47A00AA80.root --fileout step3_PAT.root --no_exec --customise Configuration/DataProcessing/Utils.addMonitoring
```


## ECAL Timing Intercalibration

### How to Dump ECAL Conditions (like IC, pedestal, etc) from Database

*Tool

 (provided by EGM POG)  [https://github.com/ferriff/usercode](https://github.com/ferriff/usercode)

*List of ECAL tags in DB that you can dump

 [https://twiki.cern.ch/twiki/bin/view/CMS/EcalDB](https://twiki.cern.ch/twiki/bin/view/CMS/EcalDB)

*Extra Instructions

   * First you need to know which tag you want to dump. Different tags are different measurements. (To see which ECAL tags are used in a global tag, clike the corresponding global tag here and you'll find the information in condDB: SWGuideFrontierConditions )
   * The output is a bunch of text files. Each file represent a measurement in one IOV, and in the file there are usually the crystal DetID, iEta, iPhi and the corresponding measurement.
   * There are basically two ways to name the output file, one is run based, which usually looks like "since_XXXXXXXX_till_YYYYYYYY", where XXXXXXXX and YYYYYYYY is the start and end run number of that IOV; another way is time stamp based, which the big numbers near "since" and "till" represent the time range of the IOV.
   * Example: if you dump the pedestal tag "EcalPedestals_Legacy2016_time_v1", you will get some files like this:
      
    dump_EcalPedestals__since_6279651441300733952_till_6279662750949624319.dat
     
     To translate the two big numbers to [Unix time](https://en.wikipedia.org/wiki/Unix_time), you need to right shift them by 32 bits: 6279651441300733952>>32 which is 1462095287 (seconds)

* One can also directly read the ECAL conditions given a global tag, detId, and eventTime*, see: https://github.com/RazorCMS/SUSYBSMAnalysis-RazorTuplizer/commit/ae8171d2ba7f9b5876f65f3d4fe8ef410552db0c

* Tools to convert the DB text files to root tree:
   * [https://github.com/RazorCMS/Pi0Tuplizer/blob/master/analysis/scripts/pedestal_perFile.C](pedestal_perFile.C): takes one single pedestal text file and save it into a root file with only one tree
   * [https://github.com/RazorCMS/Pi0Tuplizer/blob/master/analysis/scripts/pedestal.C](pedestal.C): takes a list of pedestal text files and save them into a root file in which one entry contains the entire data from one text file (*warning*: for some unknown reason if you do it in this way the file size is *much* larger than the sum of hadded single root files in the previous method)
   * similarly for [https://github.com/RazorCMS/Pi0Tuplizer/blob/master/analysis/scripts/timeCalibTag_perFile.C](timeCalibTag_perFile.C) and [https://github.com/RazorCMS/Pi0Tuplizer/blob/master/analysis/scripts/timeCalibTag.C](timeCalibTag.C)

*How to use the text file or the root file:*
   * text files: each file is an IOV, just open it and you can see what it means;
   * root tree: each entry is an IOV, it has the run range or time range, and some vectors such as iEta, iPhi, DetId, and the measurement on that crystal (same as the text file)
   * to determine which IOV to use, you need either the event number or the timestamp of your event:

```
eventNum = iEvent.id().event();
eventTime = iEvent.eventAuxiliary().time().unixTime();
```
 
   * to convert between DetId and iEta, iPhi or iX, iY, you can take a look at those scripts: [https://github.com/RazorCMS/Pi0Tuplizer/blob/master/analysis/scripts/detID_iEtaiPhi.C](detID_iEtaiPhi.C) (standalone and doesn't need cmssw package) or [https://github.com/RazorCMS/Pi0Tuplizer/blob/master/analysis/scripts/detID_iEtaiPhi_cmssw.C](detID_iEtaiPhi_cmssw.C) (uses the cmssw package, which is easier if you have cmssw enviroment). The functions are also available now in the [https://github.com/RazorCMS/RazorAnalyzer/blob/master/include/RazorAnalyzer.h#L216-L218](RazorAnalyzer).
   * An example script* showing how to find the constant given run number and DetID can be found here: [https://github.com/RazorCMS/Pi0Tuplizer/blob/master/analysis/scripts/DB_read_example.C](DB_read_example.C)

* List of tags that are saved on eos

   * pedestal tag "EcalPedestals_Legacy2016_time_v1": /eos/cms/store/group/phys_susy/razor/EcalTiming/EcalPedestals_Legacy2016_time_v1/tree_EcalPedestals_Legacy2016_time_v1.root (same tag but only with G12 rms content: tree_EcalPedestals_Legacy2016_time_v1_G12rmsonly.root)
   * time calibration constant tag "EcalTimeCalibConstants_Legacy2016_v1" (best one so far): /eos/cms/store/group/phys_susy/razor/EcalTiming/EcalTimeCalibConstants_Legacy2016_v1/EcalTimeCalibConstants_Legacy2016_v1.root
   * time calibration constant tag "EcalTimeCalibConstants_v08_offline" (corresponds to global tag "80X_dataRun2_2016SeptRepro_v7"): /eos/cms/store/group/phys_susy/razor/EcalTiming/EcalTimeCalibConstants_v08_offline/tree_EcalTimeCalibConstants_v08_offline.root
   * time calibration constant tag "EcalTimeCalibConstants_v01_express" (corresponds to global tag "80X_dataRun2_Prompt_v16"): /eos/cms/store/group/phys_susy/razor/EcalTiming/EcalTimeCalibConstants_v01_express/tree_EcalTimeCalibConstants_v01_express.root
   * ADCToGeV constants tag "EcalADCToGeVConstant_3.8T" (just 4 IOVs):  /eos/cms/store/group/phys_susy/razor/EcalTiming/EcalADCToGeVConstant_3.8T/sum_EcalADCToGeVConstant_3.8T.txt

### ZeeTiming analyzer and output ntuples

* List of ntuples available
   * /eos/cms/store/group/phys_susy/razor/EcalTiming/ntuples_V3p14_09May2017/     
      * 2016BCDEFG ntuples 
      * tags used: "EcalPedestals_Legacy2016_time_v1" for pedestal and "EcalTimeCalibConstants_Legacy2016_v1" for time calibration tag
   * /eos/cms/store/group/phys_susy/razor/EcalTiming/ntuples_V3p14_05Aug2017/     
      * 2016BCDEFG ntuples
      * fixed the cluster weighted time  
      * tags used: "EcalPedestals_Legacy2016_time_v1" for pedestal and "EcalTimeCalibConstants_Legacy2016_v1" for time calibration tag
   * /eos/cms/store/group/phys_susy/razor/EcalTiming/ntuples_V3p16_21Aug2017/     
      * 2016BCDEFG ntuples
      * with transparency branch
      * tags used: "EcalPedestals_Legacy2016_time_v1" for pedestal and "EcalTimeCalibConstants_Legacy2016_v1" for time calibration tag
*slides/plots:
   * Zhicai - 23Apr2017 (slides about how to apply different corrections to get the best time resolution): https://cernbox.cern.ch/index.php/s/yWIJCQjtQmZIsTW 
   * Time resolution vs. run period: http://zhicaiz.web.cern.ch/zhicaiz/sharebox/EcalTiming/15May2017/ 
   * Energy vs. time: http://zhicaiz.web.cern.ch/zhicaiz/sharebox/EcalTiming/15May2017/E_vs_time/

## Datasets

### 2016 
   * REMINIAOD of 2016 DoubleEG dataset (private): 
      * output in T2 Caltech: https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fphys03&input=dataset%3D%2FDoubleEG%2Fzhicaiz-crab_CMSSW_9_2_5_REMINIAOD_DoubleEG_2016*_T2Caltech_21Sept2017-0df9c016f1cc9d6241c9a6a877912101%2FUSER
      * use CMSSW_9_2_5
      * cmsDriver command i used: 

```
cmsDriver.py REMINIAOD -s PAT --runUnscheduled --nThreads 4 --data --era Run2_2016,run2_miniAOD_80XLegacy --scenario pp --conditions 80X_dataRun2_2016LegacyRepro_v4 --eventcontent MINIAOD --datatier MINIAOD --filein root://cms-xrd-global.cern.ch//store/data/Run2016B/DoubleEG/AOD/18Apr2017_ver1-v1/90000/003B7073-A13D-E711-9577-001E67A40514.root --fileout step3_PAT.root  -n -1 --python_filename=REMINIAOD_2016DoubleEG.py --no_exec
```

   * reMiniAOD of 2016 DoubleEG dataset (official):
      * razorNtuple location: /eos/cms/store/group/phys_susy/razor/run2/Run2RazorNtupleV4.1/Data/DoubleEG2016ReMiniAOD_EcalRechits/v1/zhicaiz/DoubleEG
      * [https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=%2FDoubleEG%2FRun2016B-17Jul2018_ver1-v1%2FMINIAOD](/DoubleEG/Run2016B-17Jul2018_ver1-v1/MINIAOD);  done [events: 5686987]; ntuple 100% done
      * [https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=%2FDoubleEG%2FRun2016B-17Jul2018_ver2-v1%2FMINIAOD](/DoubleEG/Run2016B-17Jul2018_ver2-v1/MINIAOD); done [events: 143073268]; ntuple 100% done
      * [https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=%2FDoubleEG%2FRun2016C-17Jul2018-v1%2FMINIAOD](/DoubleEG/Run2016C-17Jul2018-v1/MINIAOD); done [events: 47677856]; ntuple 100% done
      * [https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=%2FDoubleEG%2FRun2016D-17Jul2018-v1%2FMINIAOD](/DoubleEG/Run2016D-17Jul2018-v1/MINIAOD); done [events: 53324960]; ntuple 100% done
      * [https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=%2FDoubleEG%2FRun2016E-17Jul2018-v1%2FMINIAOD](/DoubleEG/Run2016E-17Jul2018-v1/MINIAOD); done [events: 49877710]; ntuple 100% done
      * [https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=%2FDoubleEG%2FRun2016F-17Jul2018-v1%2FMINIAOD](/DoubleEG/Run2016F-17Jul2018-v1/MINIAOD); done [events: 34577629]; ntuple 100% done
      * [https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=%2FDoubleEG%2FRun2016G-17Jul2018-v1%2FMINIAOD](/DoubleEG/Run2016G-17Jul2018-v1/MINIAOD); done [events: 78797031]; ntuple 100% done
      * [https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=%2FDoubleEG%2FRun2016H-17Jul2018-v1%2FMINIAOD](/DoubleEG/Run2016H-17Jul2018-v1/MINIAOD); done [events: 85388734]; ntuple 100% done



## Samples

### Pythia fragments 

   * GMSB Pythia config (from Livia): https://github.com/lsoffi/GMSB-MC2016-PRODUCTION 
  
   * Simple neutralino -> photon + gravitino pythia config:  https://github.com/zhangzc11/McM/blob/master/Configuration/GenProduction/python/ThirteenTeV/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_Tau5000mm_13TeV-pythia8_cff.py  [corresponding python file after cmsDriver command: https://github.com/zhangzc11/McM/blob/master/NeuNeuToPhoGrav_CTau5000mm_71X.py]

   * Simple gluino -> neutralino -> photon + gravitino pythia config: https://github.com/zhangzc11/McM/blob/master/Configuration/GenProduction/python/ThirteenTeV/GluinoToNeutralinoToGravitinoPhoton_M1000_CTau-5000mm_13TeV_cff.py  [corresponding python file after cmsDriver command: https://github.com/zhangzc11/McM/blob/master/GluinoToNeuToPhoGrav_M1000_CTau5000mm.py]

### Extra instructions in various steps

   * In GEN-SIM step (step 0): CMSSW_7_1_25 (or patch1/2) is the correct 71X release to use, any release since CMSSW_7_1_25_patch3 is bad.

   * How to store the gen vertex time information in MiniAOD when you are making the sample:
      * If: MiniAOD is from 2017 production, by default there will be a genParticles_t0 collection in the miniaod, so just use it
      * Else if: you produce the MiniAOD by yourself (in 92X), and the AOD is produced in 80X:
         * Method 1 (not recommended): you explicitly save the HepMC collection in your AOD (step 2) and MiniAOD (step 3) by modifying the outputcommand (so that HepMC will be saved in MiniAOD and you can get teh gen vertex time from HepMC): process.AODSIMoutput.outputCommands += ['keep *_generatorSmeared_*_*',]  (for AOD config) or process.MINIAODSIMoutput.outputCommands += ['keep *_generatorSmeared_*_*',] (for MiniAOD config)
         * Method 2: try to get the genParticles_t0 collection (which is much much smaller than the HepMC collection): 1) in GEN-SIM-RAW (step 1) and AOD (step 2) step, get the following commits and re-compile cmssw: [https://github.com/cms-sw/cmssw/commit/064ea373f714e1c0a78df29194edad8a824c0fcf](commit 1) and [https://github.com/lgray/cmssw/commit/664fd0d3c8a467ae28b282cc85ac0f20af6bdf88](commit 2), and then run the same cmsDriver command and do get new GEN-SIM-RAW and AOD (GEN-SIM to GEN-SIM-RAW to AODSIM); 2) in MiniAOD (step 3) step, get the following commit:  [https://github.com/lgray/cmssw/commit/664fd0d3c8a467ae28b282cc85ac0f20af6bdf88](commit 2), and and redo the MiniAOD (AODSIM to MINIAODSIM)
      * If you are still not sure, copy everything from Zhicai's directory (80X for step1 and step2, 92X for step3): /afs/cern.ch/work/z/zhicaiz/public/release/McM/forGillian/withGenParticleFix

### (Private) NeutralinoToGratinoPhoton samples

   * (BAD SAMPLE - no delayed SimHits) NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton, M = 1000GeV, lifetime = 500mm/c = 1.67ns, private, 100K
      * GEN-SIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?instance=prod%2Fphys03&limit=50&input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_7_1_25_patch3_NeutNeutToGravGrav_Mass1000_LifeTime500_24July2017_GENSIM_T2Caltech-c5fa86fed9078637e2de9b653df332e4%2FUSER&view=list](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_7_1_25_patch3_NeutNeutToGravGrav_Mass1000_LifeTime500_24July2017_GENSIM_T2Caltech-c5fa86fed9078637e2de9b653df332e4/USER);  [https://cmsweb.cern.ch/crabserver/ui/task/170724_131729%3Azhicaiz_crab_CMSSW_7_1_25_patch3_NeutNeutToGravGrav_Mass1000_LifeTime500_24July2017_GENSIM_T2Caltech](details here)
      * GEN-SIM-RAW (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime500_24July2017_GEN-SIM-RAW_T2Caltech_20PUFiles1Core-16ca0fac1b892ff3c3d45d801745cbbf%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime500_24July2017_GEN-SIM-RAW_T2Caltech_20PUFiles1Core-16ca0fac1b892ff3c3d45d801745cbbf/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170724_222426%3Azhicaiz_crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime500_24July2017_GEN-SIM-RAW_T2Caltech_20PUFiles1Core](details here)
      * AODSIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime500_24July2017_AODSIM_T2Caltech_v1-b1a4edca9adfa7a2e4059536bf605cd7%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime500_24July2017_AODSIM_T2Caltech_v1-b1a4edca9adfa7a2e4059536bf605cd7/USER)
      * MINIAODSIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime500_25July2017_MINIAODSIM_T2Caltech_v1-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime500_25July2017_MINIAODSIM_T2Caltech_v1-159e03626145fdd5d707939f335a7521/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170725_140702%3Azhicaiz_crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime500_25July2017_MINIAODSIM_T2Caltech_v1](details here)
      * MINIAODSIM - with fix to include gen vertex time - PLEASE USE THIS ONE (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime500_30July2017_MINIAODSIM_T2Caltech_v3-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime500_30July2017_MINIAODSIM_T2Caltech_v3-159e03626145fdd5d707939f335a7521/USER), [https://cmsweb.cern.ch/crabserver/ui/task/170731_114032%3Azhicaiz_crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime500_30July2017_MINIAODSIM_T2Caltech_v3](details here)
      * RazorNtuples (on eos): 
      * RazorAnalyzer tree (on eos):
   * (BAD SAMPLE - no delayed SimHits) NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton, M = 1000GeV, lifetime = 5000mm/c = 16.7ns, private, 100K
      * GEN-SIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_7_1_25_patch3_NeutNeutToGravGrav_Mass1000_LifeTime5000_24July2017_GENSIM_T2Caltech-5692d9da7a0b71aa970f8551a12b6973%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_7_1_25_patch3_NeutNeutToGravGrav_Mass1000_LifeTime5000_24July2017_GENSIM_T2Caltech-5692d9da7a0b71aa970f8551a12b6973/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170724_133841%3Azhicaiz_crab_CMSSW_7_1_25_patch3_NeutNeutToGravGrav_Mass1000_LifeTime5000_24July2017_GENSIM_T2Caltech](details here)
      * GEN-SIM-RAW (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime5000_24July2017_GEN-SIM-RAW_T2Caltech_v1-16ca0fac1b892ff3c3d45d801745cbbf%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime5000_24July2017_GEN-SIM-RAW_T2Caltech_v1-16ca0fac1b892ff3c3d45d801745cbbf/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170725_084521%3Azhicaiz_crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime5000_24July2017_GEN-SIM-RAW_T2Caltech_v1](details here)
      * AODSIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime5000_24July2017_AODSIM_T2Caltech_v1-b1a4edca9adfa7a2e4059536bf605cd7%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime5000_24July2017_AODSIM_T2Caltech_v1-b1a4edca9adfa7a2e4059536bf605cd7/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170725_191229%3Azhicaiz_crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime5000_24July2017_AODSIM_T2Caltech_v1](details here)
      * MINIAODSIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime5000_25July2017_MINIAODSIM_T2Caltech_v1-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime5000_25July2017_MINIAODSIM_T2Caltech_v1-159e03626145fdd5d707939f335a7521/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170726_074244%3Azhicaiz_crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime5000_25July2017_MINIAODSIM_T2Caltech_v1](details here)
      * MINIAODSIM - with fix to include gen vertex time - PLEASE USE THIS ONE (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime5000_30July2017_MINIAODSIM_T2Caltech_v3-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime5000_30July2017_MINIAODSIM_T2Caltech_v3-159e03626145fdd5d707939f335a7521/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170731_114212%3Azhicaiz_crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime5000_30July2017_MINIAODSIM_T2Caltech_v3](details here)
      * RazorNtuples (on eos): 
      * RazorAnalyzer tree (on eos):

   * NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton, M = 1000GeV, lifetime = 500mm/c = 1.67ns, private, 1000K (with GENSIM delayed SimHit fixed)
      *  GEN-SIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_7_1_25_NeutToPhoGrav_Mass1000_LifeTime500_07Aug2017_GENSIM_T2Caltech-7045fdc8c71a7ca713d72f5aae1639a6%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_7_1_25_NeutToPhoGrav_Mass1000_LifeTime500_07Aug2017_GENSIM_T2Caltech-7045fdc8c71a7ca713d72f5aae1639a6/USER), [https://cmsweb.cern.ch/crabserver/ui/task/170807_151754%3Azhicaiz_crab_CMSSW_7_1_25_NeutToPhoGrav_Mass1000_LifeTime500_07Aug2017_GENSIM_T2Caltech](details here)
      * GEN-SIM-RAW (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime500_08Aug2017_GEN-SIM-RAW_T2Caltech_v1-16ca0fac1b892ff3c3d45d801745cbbf%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime500_08Aug2017_GEN-SIM-RAW_T2Caltech_v1-16ca0fac1b892ff3c3d45d801745cbbf/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170808_074259%3Azhicaiz_crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime500_08Aug2017_GEN-SIM-RAW_T2Caltech_v1](details here)
      * AODSIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime500_08Aug2017_AODSIM_T2Caltech_v1-b1a4edca9adfa7a2e4059536bf605cd7%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime500_08Aug2017_AODSIM_T2Caltech_v1-b1a4edca9adfa7a2e4059536bf605cd7/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170808_201057%3Azhicaiz_crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime500_08Aug2017_AODSIM_T2Caltech_v1](details here)
      * MINIAODSIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime500_08Aug2017_MINIAODSIM_T2Caltech_v1-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime500_08Aug2017_MINIAODSIM_T2Caltech_v1-159e03626145fdd5d707939f335a7521/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170809_085902%3Azhicaiz_crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime500_08Aug2017_MINIAODSIM_T2Caltech_v1](details here)
      * RazorNtuple (on eos): /eos/cms/store/group/phys_susy/razor/run2/Run2DelayedPhotonNtuple_92X/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-500mm_13TeV-pythia8/500mm_withOOT.root

   * NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton, M = 1000GeV, lifetime = 5000mm/c = 1.67ns, private, 1000K (with GENSIM delayed SimHit fixed)
      * GEN-SIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_7_1_25_NeutToPhoGrav_Mass1000_LifeTime5000_07Aug2017_GENSIM_T2Caltech-94fe85745d81d86ba8aff72d16f4cd1a%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_7_1_25_NeutToPhoGrav_Mass1000_LifeTime5000_07Aug2017_GENSIM_T2Caltech-94fe85745d81d86ba8aff72d16f4cd1a/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170807_151353%3Azhicaiz_crab_CMSSW_7_1_25_NeutToPhoGrav_Mass1000_LifeTime5000_07Aug2017_GENSIM_T2Caltech](details here)
      * GEN-SIM-RAW (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime5000_08Aug2017_GEN-SIM-RAW_T2Caltech_v1-16ca0fac1b892ff3c3d45d801745cbbf%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime5000_08Aug2017_GEN-SIM-RAW_T2Caltech_v1-16ca0fac1b892ff3c3d45d801745cbbf/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170808_074449%3Azhicaiz_crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime5000_08Aug2017_GEN-SIM-RAW_T2Caltech_v1](details here)
      * AODSIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime5000_08Aug2017_AODSIM_T2Caltech_v1-b1a4edca9adfa7a2e4059536bf605cd7%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime5000_08Aug2017_AODSIM_T2Caltech_v1-b1a4edca9adfa7a2e4059536bf605cd7/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170808_201245%3Azhicaiz_crab_CMSSW_8_0_21_NeutNeutToGravGrav_Mass1000_LifeTime5000_08Aug2017_AODSIM_T2Caltech_v1](details here)
      * MINIAODSIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FNeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime5000_08Aug2017_MINIAODSIM_T2Caltech_v1-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime5000_08Aug2017_MINIAODSIM_T2Caltech_v1-159e03626145fdd5d707939f335a7521/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170809_090054%3Azhicaiz_crab_CMSSW_9_2_5_NeutNeutToGravGrav_Mass1000_LifeTime5000_08Aug2017_MINIAODSIM_T2Caltech_v1](details here)
      * RazorNtuple (on eos): /eos/cms/store/group/phys_susy/razor/run2/Run2DelayedPhotonNtuple_92X/NeutralinoNeutralinoToGravitinoGravitinoPhotonPhoton_M-1000_CTau-5000mm_13TeV-pythia8/5000mm_withOOT.root 

### (Private) GluinoToNeutralinoToGratinoPhoton samples

   * GluinoToNeutralinoToGratinoPhoton, M_neu = 1000GeV, CTau = 500mm/c
      * GEN-SIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FGluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_7_1_25_GluinoToNeuToPhoGrav_M1000_LifeTime500_19Aug2017_GENSIM_T2Caltech-38941b2c6aa24dc45a8e9d59f2c03ccb%2FUSER&instance=prod%2Fphys03](/GluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_7_1_25_GluinoToNeuToPhoGrav_M1000_LifeTime500_19Aug2017_GENSIM_T2Caltech-38941b2c6aa24dc45a8e9d59f2c03ccb/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170819_144152%3Azhicaiz_crab_CMSSW_7_1_25_GluinoToNeuToPhoGrav_M1000_LifeTime500_19Aug2017_GENSIM_T2Caltech](details here)
      * GEN-SIM-RAW (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FGluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_8_0_21_GluinoToNeutToPhoGrav_M1000_CTau500_20Aug2017_GEN-SIM-RAW_T2Caltech-16ca0fac1b892ff3c3d45d801745cbbf%2FUSER&instance=prod%2Fphys03](/GluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_8_0_21_GluinoToNeutToPhoGrav_M1000_CTau500_20Aug2017_GEN-SIM-RAW_T2Caltech-16ca0fac1b892ff3c3d45d801745cbbf/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170819_222743%3Azhicaiz_crab_CMSSW_8_0_21_GluinoToNeutToPhoGrav_M1000_CTau500_20Aug2017_GEN-SIM-RAW_T2Caltech](details here)
      * AODSIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FGluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_8_0_21_GluinoToNeutToPhoGrav_M1000_CTau500_20Aug2017_AODSIM_T2Caltech-b1a4edca9adfa7a2e4059536bf605cd7%2FUSER&instance=prod%2Fphys03](/GluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_8_0_21_GluinoToNeutToPhoGrav_M1000_CTau500_20Aug2017_AODSIM_T2Caltech-b1a4edca9adfa7a2e4059536bf605cd7/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170820_141025%3Azhicaiz_crab_CMSSW_8_0_21_GluinoToNeutToPhoGrav_M1000_CTau500_20Aug2017_AODSIM_T2Caltech](details here)
      * MINIAODSIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FGluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-500mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_iGluinoToNeutToPhoGrav_M1000_CTau500_20Aug2017_MINIAODSIM_T2Caltech-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](/GluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-500mm_13TeV-pythia8/zhicaiz-crab_CMSSW_9_2_5_iGluinoToNeutToPhoGrav_M1000_CTau500_20Aug2017_MINIAODSIM_T2Caltech-159e03626145fdd5d707939f335a7521/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170820_221014%3Azhicaiz_crab_CMSSW_9_2_5_iGluinoToNeutToPhoGrav_M1000_CTau500_20Aug2017_MINIAODSIM_T2Caltech](details here)
      * RazorNtuple (on eos): /eos/cms/store/group/phys_susy/razor/run2/Run2DelayedPhotonNtuple_92X/GluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-500mm_13TeV-pythia8/500mm_withOOT.root

   * GluinoToNeutralinoToGratinoPhoton, M_neu = 1000GeV, CTau = 5000mm/c
      * GEN-SIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FGluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_7_1_25_GluinoToNeuToPhoGrav_M1000_LifeTime5000_19Aug2017_GENSIM_T2Caltech-a43a5cbcb4a12cfdf6659663ad182690%2FUSER&instance=prod%2Fphys03](/GluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_7_1_25_GluinoToNeuToPhoGrav_M1000_LifeTime5000_19Aug2017_GENSIM_T2Caltech-a43a5cbcb4a12cfdf6659663ad182690/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170819_153937%3Azhicaiz_crab_CMSSW_7_1_25_GluinoToNeuToPhoGrav_M1000_LifeTime5000_19Aug2017_GENSIM_T2Caltech](details here)
      * GEN-SIM-RAW (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FGluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_8_0_21_GluinoToNeutToPhoGrav_M1000_CTau5000_20Aug2017_GEN-SIM-RAW_T2Caltech-16ca0fac1b892ff3c3d45d801745cbbf%2FUSER&instance=prod%2Fphys03](/GluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_8_0_21_GluinoToNeutToPhoGrav_M1000_CTau5000_20Aug2017_GEN-SIM-RAW_T2Caltech-16ca0fac1b892ff3c3d45d801745cbbf/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170819_222908%3Azhicaiz_crab_CMSSW_8_0_21_GluinoToNeutToPhoGrav_M1000_CTau5000_20Aug2017_GEN-SIM-RAW_T2Caltech](details here)
      * AODSIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FGluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_8_0_21_GluinoToNeutToPhoGrav_M1000_CTau5000_20Aug2017_AODSIM_T2Caltech-b1a4edca9adfa7a2e4059536bf605cd7%2FUSER&instance=prod%2Fphys03](/GluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_8_0_21_GluinoToNeutToPhoGrav_M1000_CTau5000_20Aug2017_AODSIM_T2Caltech-b1a4edca9adfa7a2e4059536bf605cd7/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170820_142253%3Azhicaiz_crab_CMSSW_8_0_21_GluinoToNeutToPhoGrav_M1000_CTau5000_20Aug2017_AODSIM_T2Caltech](details here)
      * MINIAODSIM (on T2_US_Caltech): [https://cmsweb.cern.ch/das/request?input=%2FGluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-5000mm_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_iGluinoToNeutToPhoGrav_M1000_CTau5000_20Aug2017_MINIAODSIM_T2Caltech-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](/GluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-5000mm_13TeV-pythia8/zhicaiz-crab_CMSSW_9_2_5_iGluinoToNeutToPhoGrav_M1000_CTau5000_20Aug2017_MINIAODSIM_T2Caltech-159e03626145fdd5d707939f335a7521/USER); [https://cmsweb.cern.ch/crabserver/ui/task/170820_232350%3Azhicaiz_crab_CMSSW_9_2_5_iGluinoToNeutToPhoGrav_M1000_CTau5000_20Aug2017_MINIAODSIM_T2Caltech](details here)
      * RazorNtuple (on eos): /eos/cms/store/group/phys_susy/razor/run2/Run2DelayedPhotonNtuple_92X/GluinoToNeutralinoToGravitinoPhoton_M-1000_CTau-5000mm_13TeV-pythia8/5000mm_withOOT.root

### (Private) GMSB/HVDS Signal samples

   * (Kevin, see his email on 07Aug2017-12:04AM CERN TIME for details) [https://cmsweb.cern.ch/das/request?instance=prod%2Fphys03&limit=50&input=%2FGMSB_L180_Ctau6000_Pythia8_13TeV_cff_py_GEN_SIM%2Fkmcdermo-GMSB_L180_Ctau6000_userHLT_legacy_PAT-MINIAODSIM-v1-ef93839e5df81cfe97dbe8d1e73bf805%2FUSER&view=list](/GMSB_L180_Ctau6000_Pythia8_13TeV_cff_py_GEN_SIM/kmcdermo-GMSB_L180_Ctau6000_userHLT_legacy_PAT-MINIAODSIM-v1-ef93839e5df81cfe97dbe8d1e73bf805/USER )
      * RazorNtuple (on eos): /eos/cms/store/group/phys_susy/razor/run2/Run2DelayedPhotonNtuple_92X/GMSB_L180_Ctau6000_Pythia8_13TeV_cff_py_GEN_SIM/2190mm_withOOT.root
   * (Private, grid, on T2_Caltech, MINIAODSIM, 2016) https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fphys03&input=dataset%3D%2FGMSB_L*_13TeV-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_GMSB_*_25Oct2017_MINIAODSIM_T2Caltech-159e03626145fdd5d707939f335a7521%2FUSER

### (Official) GMSB/HVDS 2016 Signal samples

   * HVDS: https://cms-pdmv.cern.ch/mcm/requests?range=EXO-RunIISummer15GS-10956,EXO-RunIISummer15GS-11039&page=0&shown=127

### (Official) GMSB/HVDS 2017 Signal samples

### (Private/Official re-miniAOD) 2016 Background samples

   * GJets_HT40To100_TuneCUETP8M1_13TeV-madgraphMLM-pythia8:
      * starting from AODSIM: /GJets_HT-40To100_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/RunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1/AODSIM   - [https://cmsweb.cern.ch/das/request?input=dataset%3D%2FGJets_HT-40To100_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2FRunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1%2FAODSIM&instance=prod%2Fglobal](das)
      * private re-miniAOD output (Caltech T2): /GJets_HT-40To100_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/zhicaiz-crab_CMSSW_9_2_5_GJets_HT40To100_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521/USER   - [https://cmsweb.cern.ch/das/request?input=%2FGJets_HT-40To100_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_GJets_HT40To100_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](das)
      * official re-miniAOD output:
   * GJets_HT100To200_TuneCUETP8M1_13TeV-madgraphMLM-pythia8:
      * starting from AODSIM: /GJets_HT-100To200_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/RunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1/AODSIM   - [https://cmsweb.cern.ch/das/request?input=dataset%3D%2FGJets_HT-100To200_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2FRunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1%2FAODSIM&instance=prod%2Fglobal](das)
      * private re-miniAOD output (Caltech T2): /GJets_HT-100To200_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/zhicaiz-crab_CMSSW_9_2_5_GJets_HT100To200_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521/USER   - [https://cmsweb.cern.ch/das/request?input=%2FGJets_HT-100To200_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_GJets_HT100To200_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](das)
      * official re-miniAOD output:
   * GJets_HT200To400_TuneCUETP8M1_13TeV-madgraphMLM-pythia8:
      * starting from AODSIM: /GJets_HT-200To400_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/RunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1/AODSIM   - [https://cmsweb.cern.ch/das/request?input=dataset%3D%2FGJets_HT-200To400_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2FRunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1%2FAODSIM&instance=prod%2Fglobal](das)
      * private re-miniAOD output (Caltech T2): /GJets_HT-200To400_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/zhicaiz-crab_CMSSW_9_2_5_GJets_HT200To400_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521/USER   - [https://cmsweb.cern.ch/das/request?input=%2FGJets_HT-200To400_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_GJets_HT200To400_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](das)
      * official re-miniAOD output:
   * GJets_HT400To600_TuneCUETP8M1_13TeV-madgraphMLM-pythia8:
      * starting from AODSIM: /GJets_HT-400To600_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/RunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v2/AODSIM   - [https://cmsweb.cern.ch/das/request?input=dataset%3D%2FGJets_HT-400To600_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2FRunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v2%2FAODSIM&instance=prod%2Fglobal](das)
      * private re-miniAOD output (Caltech T2): /GJets_HT-400To600_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/zhicaiz-crab_CMSSW_9_2_5_GJets_HT400To600_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521/USER - [https://cmsweb.cern.ch/das/request?input=%2FGJets_HT-400To600_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_GJets_HT400To600_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](das)
      * official re-miniAOD output:
   * GJets_HT600ToInf_TuneCUETP8M1_13TeV-madgraphMLM-pythia8:
      * starting from AODSIM: /GJets_HT-600ToInf_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/RunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1/AODSIM   - [https://cmsweb.cern.ch/das/request?input=dataset%3D%2FGJets_HT-600ToInf_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2FRunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1%2FAODSIM&instance=prod%2Fglobal](das)
      * private re-miniAOD output (Caltech T2): /GJets_HT-600ToInf_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/zhicaiz-crab_CMSSW_9_2_5_GJets_HT600ToInf_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521/USER   - [https://cmsweb.cern.ch/das/request?input=%2FGJets_HT-600ToInf_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_GJets_HT600ToInf_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](das)
      * official re-miniAOD output:
   * QCD_HT200to300_TuneCUETP8M1_13TeV-madgraphMLM-pythia8:
      * starting from AODSIM: /QCD_HT200to300_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/RunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1/AODSIM   - [https://cmsweb.cern.ch/das/request?input=dataset%3D%2FQCD_HT200to300_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2FRunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1%2FAODSIM&instance=prod%2Fglobal](das)
      * private re-miniAOD output (Caltech T2): /QCD_HT200to300_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/zhicaiz-crab_CMSSW_9_2_5_QCD_HT200To300_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521/USER   - [https://cmsweb.cern.ch/das/request?input=%2FQCD_HT200to300_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_QCD_HT200To300_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](das)
      * official re-miniAOD output:
   * QCD_HT300to500_TuneCUETP8M1_13TeV-madgraphMLM-pythia8:
      * starting from AODSIM: /QCD_HT300to500_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/RunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1/AODSIM - [https://cmsweb.cern.ch/das/request?input=dataset%3D%2FQCD_HT300to500_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2FRunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1%2FAODSIM&instance=prod%2Fglobal](das)
      * private re-miniAOD output (Caltech T2): /QCD_HT300to500_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/zhicaiz-crab_CMSSW_9_2_5_QCD_HT300To500_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521/USER - [https://cmsweb.cern.ch/das/request?input=%2FQCD_HT300to500_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_QCD_HT300To500_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](das)
      * official re-miniAOD output:
   * QCD_HT500to700_TuneCUETP8M1_13TeV-madgraphMLM-pythia8:
      * starting from AODSIM: /QCD_HT500to700_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/RunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v2/AODSIM - [https://cmsweb.cern.ch/das/request?input=dataset%3D%2FQCD_HT500to700_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2FRunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v2%2FAODSIM&instance=prod%2Fglobal](das)
      * private re-miniAOD output (Caltech T2): /QCD_HT500to700_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/zhicaiz-crab_CMSSW_9_2_5_QCD_HT500To700_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521/USER - [https://cmsweb.cern.ch/das/request?input=%2FQCD_HT500to700_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_QCD_HT500To700_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](das)
      * official re-miniAOD output:
   * QCD_HT700to1000_TuneCUETP8M1_13TeV-madgraphMLM-pythia8:
      * starting from AODSIM: /QCD_HT700to1000_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/RunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1/AODSIM - [https://cmsweb.cern.ch/das/request?input=dataset%3D%2FQCD_HT700to1000_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2FRunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1%2FAODSIM&instance=prod%2Fglobal](das)
      * private re-miniAOD output (Caltech T2): /QCD_HT700to1000_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/zhicaiz-crab_CMSSW_9_2_5_QCD_HT700To1000_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521/USER  - [https://cmsweb.cern.ch/das/request?input=%2FQCD_HT700to1000_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_QCD_HT700To1000_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](das)
      * official re-miniAOD output:
   * QCD_HT1000to1500_TuneCUETP8M1_13TeV-madgraphMLM-pythia8:
      * starting from AODSIM: /QCD_HT1000to1500_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/RunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1/AODSIM - [https://cmsweb.cern.ch/das/request?input=dataset%3D%2FQCD_HT1000to1500_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2FRunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1%2FAODSIM&instance=prod%2Fglobal](das)
      * private re-miniAOD output (Caltech T2): /QCD_HT1000to1500_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/zhicaiz-crab_CMSSW_9_2_5_QCD_HT1000To1500_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521/USER - [https://cmsweb.cern.ch/das/request?input=%2FQCD_HT1000to1500_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_QCD_HT1000To1500_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](das)
      * official re-miniAOD output:
   * QCD_HT1500to2000_TuneCUETP8M1_13TeV-madgraphMLM-pythia8:
      * starting from AODSIM: /QCD_HT1500to2000_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/RunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1/AODSIM - [https://cmsweb.cern.ch/das/request?input=dataset%3D%2FQCD_HT1500to2000_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2FRunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1%2FAODSIM&instance=prod%2Fglobal](das)
      * private re-miniAOD output (Caltech T2): /QCD_HT1500to2000_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/zhicaiz-crab_CMSSW_9_2_5_QCD_HT1500To2000_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521/USER  -  [https://cmsweb.cern.ch/das/request?input=%2FQCD_HT1500to2000_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_QCD_HT1500To2000_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](das)
      * official re-miniAOD output:
   * QCD_HT2000toInf_TuneCUETP8M1_13TeV-madgraphMLM-pythia8:
      * starting from AODSIM: /QCD_HT2000toInf_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/RunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1/AODSIM - [https://cmsweb.cern.ch/das/request?input=dataset%3D%2FQCD_HT2000toInf_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2FRunIISummer16DR80Premix-PUMoriond17_80X_mcRun2_asymptotic_2016_TrancheIV_v6_ext1-v1%2FAODSIM&instance=prod%2Fglobal](das)
      * private re-miniAOD output (Caltech T2): /QCD_HT2000toInf_TuneCUETP8M1_13TeV-madgraphMLM-pythia8/zhicaiz-crab_CMSSW_9_2_5_QCD_HT2000ToInf_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521/USER - [https://cmsweb.cern.ch/das/request?input=%2FQCD_HT2000toInf_TuneCUETP8M1_13TeV-madgraphMLM-pythia8%2Fzhicaiz-crab_CMSSW_9_2_5_QCD_HT2000ToInf_reMiniAOD_19Sept2017-159e03626145fdd5d707939f335a7521%2FUSER&instance=prod%2Fphys03](das)
      * official re-miniAOD output:

 

