# Processing

rs-fMRI

|                  Analysis                 | Papers | Software | Scripts | Status | Comments | Who? |
|:-----------------------------------------:|:------:|:--------:|:-------:|:------:|:------:|----------|
|      Independent component analysis (ICA) | [Beckmann et al. (2005)](https://royalsocietypublishing.org/doi/10.1098/rstb.2005.1634?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed), [Beckmann et al. (2009)](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/DualRegression?action=AttachFile&do=get&target=CB09.pdf)       |   [FSL MELODIC](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/MELODIC)       |         |    awaiting    |    20 ICs + 70 ICs      |      |
|           Network-to-network connectivity |  e.g. [Smith et al. (2015)](https://www.nature.com/articles/nn.4125)     |  [FSLNets](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSLNets) |         |    awaiting    |    How many components?      |       |
|                   ROI-to-ROI connectivity | [Power et al. (2011)](https://www.sciencedirect.com/science/article/pii/S0896627311007926) e.g., [Xia et al. 2018](https://www.nature.com/articles/s41467-018-05317-y)       |          |         |        |  Using the [Freesurfer segmentation output](https://freesurfer.net/fswiki/FsTutorial/AnatomicalROI_tktools) and/or [Power atlas](https://www.sciencedirect.com/science/article/pii/S0896627311007926) |
|                    Effective connectivity |  [Zeidman et al. (2019a)](https://www.sciencedirect.com/science/article/pii/S1053811919305221), [Zeidman et al. (2019b)](https://www.sciencedirect.com/science/article/pii/S1053811919305233)      |  [SPM Dynamic causal modeling (DCM)](        |         |        |  Which nodes to use?        |      |
| Percent amplitude of fluctuations (perAF) |        |          |         |        |          |       |
|               Regional homogeneity (ReHo) |        |          |         |        |          |      |



QC of freesurfer segmentation: [Qoala-T](https://www.sciencedirect.com/science/article/pii/S1053811919300138)
