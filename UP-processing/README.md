# Processing


<details>
  <summary><b>sMRI</b></summary>

|                  Analysis                 | Papers | Software | Scripts | Status | Comments | Who? |
|:-----------------------------------------:|:------:|:--------:|:-------:|:------:|:------:|----------|
|        Regional volume                    |  e.g., [ten Doesschate et al. (2014)](https://www.frontiersin.org/articles/10.3389/fpsyt.2014.00169/full)       |   Freesurfer [recon-all](https://surfer.nmr.mgh.harvard.edu/fswiki/recon-all)      |         | awaiting |  post-processing QC [Paper](https://www.sciencedirect.com/science/article/pii/S1053811921004511)     |       |
|        Cortical thickness                 |  e.g., [Qiu et al. (2014)](https://www.nature.com/articles/tp201418)       |   Freesurfer [recon-all](https://surfer.nmr.mgh.harvard.edu/fswiki/recon-all)        |         | awaiting |       |       |
  
</details>




<details>
  <summary><b>rs-fMRI</b></summary>

|                  Analysis                 | Papers | Software | Scripts | Status | Comments | Who? |
|:-----------------------------------------:|:------:|:--------:|:-------:|:------:|:------:|----------|
|      Independent component analysis (ICA) | [Beckmann et al. (2005)](https://royalsocietypublishing.org/doi/10.1098/rstb.2005.1634?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed), [Beckmann et al. (2009)](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/DualRegression?action=AttachFile&do=get&target=CB09.pdf)       |   [FSL MELODIC](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/MELODIC)       |         |    awaiting    |    20 ICs + 70 ICs      |      |
|           Network-to-network connectivity |  e.g., [Smith et al. (2015)](https://www.nature.com/articles/nn.4125)     |  [FSLNets](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSLNets) |         |    awaiting    |     20 ICs + 70 ICs     |       |
|                   ROI-to-ROI connectivity | [Power et al. (2011)](https://www.sciencedirect.com/science/article/pii/S0896627311007926), e.g., [Xia et al. (2018)](https://www.nature.com/articles/s41467-018-05317-y)       |  Partial correlation     |         |    awaiting    |  Using the [Freesurfer segmentation output](https://freesurfer.net/fswiki/FsTutorial/AnatomicalROI_tktools) and/or [Power atlas](https://www.sciencedirect.com/science/article/pii/S0896627311007926) |
| graph based measures | [Wang et al. (2010)](https://www.frontiersin.org/articles/10.3389/fnsys.2010.00016/full) | [Brain Connectivity Toolbox](https://sites.google.com/site/bctnet/) |  | awaiting | e.g., degree, clustering, shortest pathlength, etc |  |
|                    Effective connectivity |  [Zeidman et al. (2019a)](https://www.sciencedirect.com/science/article/pii/S1053811919305221), [Zeidman et al. (2019b)](https://www.sciencedirect.com/science/article/pii/S1053811919305233)      |  [SPM Dynamic causal modeling (DCM)](https://www.fil.ion.ucl.ac.uk/spm/course/slides17-oct/10_DCM_Introduction_fMRI.pdf)        |         |    awaiting    |  Which nodes to use?        |      |
| Percent amplitude of fluctuations (perAF) |  [Jia et al. (2020)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0227021)      |   [SPM RESTplus](http://restfmri.net/forum/restplus)       |         |   awaiting     |  Summarized using FS segmentation and/or Power atlas   |       |
|               Regional homogeneity (ReHo) |  [Yao et al. (2009)](https://www.sciencedirect.com/science/article/pii/S0165032708004199?casa_token=4q0fY8hRUZUAAAAA:gVFzKTOI2fFTD1n5hvx3Sq3lES1YpcLJWGPlthNe5snEmWesJz65fZ6BfIRTuZV6MKs9xuBWj1SC), [Zang et al. (2004)](https://www.sciencedirect.com/science/article/pii/S1053811904000035?casa_token=jWlLaHefMVMAAAAA:RK6alYBCO_YtSgYslr7_CDWfvLzWt9QfrFXz9xIcAtyNWWQd3OkYvv6A2tpJDXt-Y66LcxJw-SEy)        |  [SPM RESTplus](http://restfmri.net/forum/restplus)     |         |    awaiting    |    Summarized using FS segmentation and/or Power atlas       |      |

</details>

<details>
  <summary><b>DTI</b></summary>

|                  Analysis                 | Papers | Software | Scripts | Status | Comments | Who? |
|:-----------------------------------------:|:------:|:--------:|:-------:|:------:|:------:|----------|
|                                           |         |         |         | awaiting |       |       |
|                                           |         |         |         | awaiting |       |       |
|                                           |         |         |         | awaiting |       |       |
  
</details>


<details>
  <summary><b>MRS</b></summary>

|                  Analysis                 | Papers | Software | Scripts | Status | Comments | Who? |
|:-----------------------------------------:|:------:|:--------:|:-------:|:------:|:------:|----------|
|                                           |         |         |         | awaiting |       |       |
|                                           |         |         |         | awaiting |       |       |
|                                           |         |         |         | awaiting |       |       |
  
</details>


<details>
  <summary><b>ASL</b></summary>

|                  Analysis                 | Papers | Software | Scripts | Status | Comments | Who? |
|:-----------------------------------------:|:------:|:--------:|:-------:|:------:|:------:|----------|
|                                           |         |         |         | awaiting |       |       |
|                                           |         |         |         | awaiting |       |       |
|                                           |         |         |         | awaiting |       |       |
  
</details>

<details>
  <summary><b>EEG</b></summary>

|                  Analysis                 | Papers | Software | Scripts | Status | Comments | Who? |
|:-----------------------------------------:|:------:|:--------:|:-------:|:------:|:------:|----------|
|                                           |         |         |         | awaiting |       |       |
|                                           |         |         |         | awaiting |       |       |
|                                           |         |         |         | awaiting |       |       |
  
</details>

<details>
  <summary><b>Ictal-EEG</b></summary>

|                  Analysis                 | Papers | Software | Scripts | Status | Comments | Who? |
|:-----------------------------------------:|:------:|:--------:|:-------:|:------:|:------:|----------|
|                                           |         |         |         | awaiting |       |       |
|                                           |         |         |         | awaiting |       |       |
|                                           |         |         |         | awaiting |       |       |
  
</details>
