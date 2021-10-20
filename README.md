# ECT-imaging-pipeline
This repository contains the pipeline for uniform preprocessing, quality control and processing for electroconvulsive therapy (ECT) imaging data acquired in Rijnstate hospital Arnhem and UMC Amsterdam. Furthermore, we provide documentation on the pipeline and example pieces of text that describe the analysis for your manuscript. 

### Datasets, -types and -timepoints
Multiple ECT-imaging datasets were acquired:
* Seizure threshold dataset
     * This dataset was acquired in order to study neuroimaging and clinical predictors of seizure threshold in ECT. The study acquired the following modalities:
        *  Clinical data was acquired pre- and post-ECT. You can find a clinical description of the sample [here](https://link.springer.com/article/10.1007/s00406-012-0342-7/tables/1). 
        *  Structural MRI (sMRI) was acquired pre-ECT. See related paper [here](https://www.sciencedirect.com/science/article/pii/S1935861X12002094?casa_token=cAC-WLm3LVcAAAAA:gm4tDvav6UkNTPFnTLWB_7c2fY4bnB_o-BNe3HnInR2mOL0qw0iFPD7MNEdiymz7QwEy4v7DvGk) or [here](https://www.frontiersin.org/articles/10.3389/fpsyt.2014.00169/full).
        *  Resting-state functional MRI (rs-fMRI) was acquired pre-ECT. See related [paper](https://www.nature.com/articles/mp201478). 
        *  Diffusion Tensor Imaging (DTI) was acquired pre-ECT (?).
     *  Study status: data acquisition is finished. 
* Schema-ECT dataset
     * This dataset was acquired to study a combined psychological+ECT intervention. For a description of the intervention see this [paper](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2768949). The following data were acquired in this dataset:
        * Clinical data was acquired pre- and post-ECT, and at follow up. A brief clinical description is presented [here](https://cdn.jamanetwork.com/ama/content_public/journal/jamanetworkopen/938527/zoi200468t1.png?Expires=1636631862&Signature=nWlCfYCET7ojxyvCuaFI5kitSWKRMCwvL~d5EF3blsRjbXMKw4zxSAsV6nRbeaOsUY6fYXKS9atC6FiCngE4EOIoVbNJuW4EsXfnjvY0SKLxkvh~GM3Ij9vdUhWI1YI4pGXww~h8amcKYizUJRt3ehFKxWZoASeQI9OoxXyw4orAge8AGmlhgv~bDyjb5KWUnoqiWtQUacBcz3nAdRAjh5El03wRKsSjvJZ7kybzNnv~LVRLQIYlcwAlxvK2KRshAtN-Vn2w3ULVxyriDm08ZGejQn0A4g3vfTO9VqTXvVlFqmFm3haArQakZGYBf3bRQG2Vo~2dL~-t09Khtn2qNA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA).
        * sMRI was acquired pre- and post-ECT, and at follow-up (?).
        * rs-fMRI was acquired pre- and post-ECT, and at follow-up (?).
        * DTI was acquired pre- and post-ECT, and at follow-up (?). 
        * EEG was acquired pre- and post-ECT, and at follow-up (?). 
     * Status: data acquisition is finished.
* SNOEP dataset
     * This dataset was acquired for ...  
     * Status: acquisition is ongoing. 
* Synapse dataset
     * This dataset was acquired for ...
     * Status: acquisition is ongoing. 


### Preprocessing

[FMRIprep](https://fmriprep.org/en/stable/)
[QSIprep](https://qsiprep.readthedocs.io/en/latest/)
