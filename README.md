## How to run ? 
`cmsRun TriggerEff_80X.py data_25ns IsoMu24`

### For double muons:
`root -l -b -q /tmp/hbrun/TnPTree_SingleMuon_Run2017Av2_296172_to_296174_DCSOnly.root prepareForSoup.cxx+`
`cmsRun TriggerEff_80X.py data_25ns passMu17Mu8Dz`
