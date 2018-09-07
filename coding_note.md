#### linux change boot order

```
sudo gedit /etc/default/grub
sudo update-grub
```

#### ubuntu install root

```
http://root.cern.ch/drupal/content/build-prerequisites
http://root.cern.ch/drupal/content/installing-root-source

sudo apt-get install git dpkg-dev make g++ gcc binutils libx11-dev libxpm-dev libxft-dev libxext-dev gfortran libssl-dev libpcre3-dev xlibmesa-glu-dev libglew1.5-dev libftgl-dev libmysqlclient-dev libfftw3-dev cfitsio-dev graphviz-dev libavahi-compat-libdnssd-dev libldap2-dev python-dev libxml2-dev libkrb5-dev libgsl0-dev libqt4-dev

   ============================================================
   ===                ROOT BUILD SUCCESSFUL.                ===
   === Run 'source bin/thisroot.csh' before starting ROOT ===
   ============================================================
Ok, thanks Bertrand, it's working now, here the recipe:

1. Install xfs and xfstt:
CODE: SELECT ALL
sudo apt-get install xfs xfstt


2. Install the following fonts:
CODE: SELECT ALL
t1-xfree86-nonfree - non-free Postscript Type 1 fonts from XFree86
ttf-xfree86-nonfree - non-free TrueType fonts from XFree86
ttf-xfree86-nonfree-syriac - non-free syriac OpenType fonts from XFree86
xfonts-75dpi - 75 dpi fonts for X
xfonts-100dpi - 100 dpi fonts for X

3. Reboot

4. Recompile root

Cheers.
Last edited by lixo1 on Fri Apr 29, 2011 16:17, edited 1 time in total.

```

#### unbutu install matlab

http://wmyming01.blog.163.com/blog/static/12964879120121120102253573/
or:
http://www.linuxidc.com/Linux/2013-06/86130.htm

icon: sudo chmod a+w -R ~/.matlab

#### ssh

```
ssh-add ~/.ssh/ssh/id_rsa

ssh wangzhe@166.111.143.19

source ~mroot.csh

wangzhe@ln1 ~/depot/data/TWin/11_P12e_AdSimple_OWSNhit15_Tc400us_0.7MeV/H/EH1
```

#### set text start

```
sudo vi /etc/default/grub 
GRUB_CMDLINE_LINUX_DEFAULT="quiet splash"
-->
GRUB_CMDLINE_LINUX_DEFAULT="quiet splash text"
-->
sudo update-grub
```

#### replace in all files

```
sed -i "s/.png/.pdf/g" `grep .png -rl ./`
sed -i "s/.pdf/.png/g" `grep .pdf -rl ./`
```

#### delete a line with pattern for all files

```
sed -i '/pattern to match/d' infile
sed -i "/pattern at end of line$/d" infile
```

#### vim delete lines contain word

```
g/faild/d
```

#### vim delete from pattern to the end of line

```
:g/{pattern}/normal nd$
```

#### copy from github.com to local

```
git clone git@github.com:zhangzc11/RazorFramework.git
```

#### push to github.com

```
https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/
git init
git add .
git commit -m "AIC table"
git remote add origin git@github.com:zhangzc11/RazorFramework.git
git remote -v
git push origin master
git pull
git add ***
```

#### CMSSW

```
scram list CMSSW
cmsrel CMSSW_X_Y_Z
cd CMSSW_X_Y_Z
cmsenv
```

#### show the number of files in current directory

```
ls |wc -l
```

#### list the files by size

```
ls -lSh
```

#### copy files from cern eos (password required)

```
xrdcp root://eoscms.cern.ch//eos/cms/store/caf/user/zhicaiz/2015A_RAW_ALL/iter_0/2015A_EcalNtp_0.root ./
```

#### useful example about how to submit condor jobs in t3-higgs

```
/home/zhicaiz/ECALpro/CMSSW_6_2_11/src/pi0-analysis/submit_fastAnalysis_condor.sh
```

#### control the margin when divide the TCanvas to multiple plots

```
c1->cd(); gPad->SetLeftMargin(0.15); gPad->SetBottomMargin(0.15)
```

#### quota eos

```
first: eos
then: cd /eos/cms/store/caf/user/zhicaiz/
then: quota /eos/cms/store/caf/user/zhicaiz/
```

#### batch kill all jobs

```
bkill -u zhicaiz -0
```

#### CMS run summary

```
https://cmswbm.web.cern.ch/cmswbm/cmsdb/servlet/RunSummary
```

#### go to external disks:

```
cd /media/
```

#### ls sort by file size

```
ls -lSh
```

#### how to find files by a eos pointer

```
cern das to get the directory (just search with the pointer you get): https://cmsweb.cern.ch/das/
add the site you want to use: https://twiki.cern.ch/twiki/bin/view/CMSPublic/WorkBookXrootdService
```

#### TH2Poly 

```
https://github.com/cmorgoth/RazorFramework/blob/master/HggRazor/PlottingAndSystematic/app/GetHggRazorSystematics.cc
https://github.com/cmorgoth/RazorFramework/blob/master/HggRazor/CommonTools/src/HggRazorSystematics.cc

[4/15/16, 15:09:24] Cristian Peña Herrera: h2p = new TH2Poly(this->processName+"+nominal", "", 150, 10000, 0, 1);
[4/15/16, 15:09:39] Cristian Peña Herrera: h2p->AddBin(tmp[0], tmp[1], tmp[2], tmp[3]);
[4/15/16, 15:14:24] Cristian Peña Herrera: std::vector<float*> myBinning =  SetBinning_highpt();
for ( auto tmp : myBinning ) h2p->AddBin(tmp[0], tmp[1], tmp[2], tmp[3]);

check out a single branch from a git repository:

git clone -b mybranch --single-branch git://sub.domain.com/repo.git
```

#### git search

```
vim search for beginning of a line: ^
vim search for end of a line: \n
vim adding string end of each line: :%s/$/addedstring/g
```

#### how to set lxplus so that when you "cd ~/work/xxx" it understands as "cd /afs/cern.ch/work/z/zhicaiz/xxx"

```
try "ln -s /afs/cern.ch/work/z/zhicaiz ~/work"
it will create a symbolic link that persists
```


#### Change the queue of submitted jobs

```
bjobs | grep PEND | awk '{print $1}' | xargs -n 1 bmod -q 1nd
bjobs | grep PEND | grep cmscaf1nd |awk '{print $1}' | xargs -n 1 bmod -q 1nd
bjobs | grep PEND | grep 1nd |awk '{print $1}' | xargs -n 1 bmod -q cmscaf1nd
```


#### How to check duplicate events in a TTree

```
//root[0] myTree->SetScanField(0);
//root[1] myTree->Scan("eventNb:runNb:LS:zVtx:Reco_QQ_4mom.M()"); >tree.log

root [2] ((TTreePlayer*)(Tree_Optim->GetPlayer()))->SetScanRedirect(true);
root [3] ((TTreePlayer*)(Tree_Optim->GetPlayer()))->SetScanFileName("output.txt");
root [4] Tree_Optim->Scan("STr2_enG1_true:STr2_enG2_true")


$ wc -l tree.log
$ sort -u tree.log | wc -l


If the tree has duplicated events, the above two wc -l will not give same number of lines.
```

#### cmssw Output Command

```
https://twiki.cern.ch/twiki/bin/view/CMSPublic/SWGuideSelectingBranchesForOutput
```

#### scram build options

```
https://twiki.cern.ch/twiki/bin/view/CMSPublic/SWGuideScram#CmsswSCRAMCompile
```

#### how to make pull request to cmssw

```
http://cms-sw.github.io/tutorial.html
```

#### git show origin url:

```
git remote -v
git change origin url:
git remote set-url origin https://github.com/zhangzc11/REPOSITORY.git
```

#### pick one event from dataset:

```
edmPickEvents.py 'DatasetName' run:lumi:event
```

#### loop

```
for f in $(ls *.tar.gz); do tar -zxvf $f; done
```

#### add LS in process.source

```
process.source.lumisToProcess = cms.untracked.VLuminosityBlockRange('260536:9-260536:37')

for x in `seq 2 8`; do sed "s/EphemeralHLTPhysics1/EphemeralHLTPhysics$x/" crab_diphoton_304777_x1.py > crab_diphoton_304777_x$x\.py; crab submit -c crab_diphoton_304777_x$x\.py; done

```
#### copy a file to clipboard

```
xclip -sel c < diphoton_all.txt

```

#### brilcalc shit

```
export PATH=$HOME/.local/bin:/afs/cern.ch/cms/lumi/brilconda-1.1.7/bin:$PATH
pip uninstall brilws
pip install --install-option="--prefix=$HOME/.local" brilws
```





