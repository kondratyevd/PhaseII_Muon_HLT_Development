# Instruction for Phase-II IterativeL3 (from Federica)
```
cmsrel CMSSW_11_1_2_patch3
cd CMSSW_11_1_2_patch3/src
cmsenv
git cms-addpkg SimMuon/MCTruth
git cms-addpkg Validation/RecoMuon
scram b -j 10
git clone -b IterL3 https://github.com/kondratyevd/PhaseII_Muon_HLT_Development
cd PhaseII_Muon_HLT_Development
cmsRun cfgs/step3_HLT_muons_TRK_v6_1.py
```
