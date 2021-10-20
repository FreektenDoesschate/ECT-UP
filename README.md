# ECT-imaging-pipeline
This repository contains the pipeline for uniform preprocessing, quality control and processing for electroconvulsive therapy (ECT) imaging data acquired in Rijnstate hospital Arnhem and UMC Amsterdam. Furthermore, we provide a description of the available data, documentation on the pipeline, and example pieces of text that describe the analysis for your manuscript. 

## Datasets
Multiple ECT-imaging datasets were acquired:
* Seizure threshold dataset
     * This dataset was acquired in order to study neuroimaging and clinical predictors of seizure threshold in ECT. See related papers on [clinical data](https://link.springer.com/article/10.1007/s00406-012-0342-7/tables/1). For papers on the structural MRI data, see [here](https://www.sciencedirect.com/science/article/pii/S1935861X12002094?casa_token=cAC-WLm3LVcAAAAA:gm4tDvav6UkNTPFnTLWB_7c2fY4bnB_o-BNe3HnInR2mOL0qw0iFPD7MNEdiymz7QwEy4v7DvGk) and [here](https://www.frontiersin.org/articles/10.3389/fpsyt.2014.00169/full). And another paper on the [Resting-state functional MRI (rs-fMRI) data](https://www.nature.com/articles/mp201478). 
     *  Study status: data acquisition is finished. 
* Schema-ECT dataset
     * This dataset was acquired to study a combined psychological+ECT intervention. For a description of the intervention see this [paper](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2768949), with a brief clinical description of the sample [here](https://cdn.jamanetwork.com/ama/content_public/journal/jamanetworkopen/938527/zoi200468t1.png?Expires=1636631862&Signature=nWlCfYCET7ojxyvCuaFI5kitSWKRMCwvL~d5EF3blsRjbXMKw4zxSAsV6nRbeaOsUY6fYXKS9atC6FiCngE4EOIoVbNJuW4EsXfnjvY0SKLxkvh~GM3Ij9vdUhWI1YI4pGXww~h8amcKYizUJRt3ehFKxWZoASeQI9OoxXyw4orAge8AGmlhgv~bDyjb5KWUnoqiWtQUacBcz3nAdRAjh5El03wRKsSjvJZ7kybzNnv~LVRLQIYlcwAlxvK2KRshAtN-Vn2w3ULVxyriDm08ZGejQn0A4g3vfTO9VqTXvVlFqmFm3haArQakZGYBf3bRQG2Vo~2dL~-t09Khtn2qNA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA). 
     * Status: data acquisition is finished.
* SNOEP dataset
     * SNOEP stands for Study on Neuroimaging predictors of Outcome in ECT Patients. This dataset is a continuous acquisition of neuroimaging and clinical data in ECT with the primary objective to predict treatment outcome.
     * Status: acquisition is ongoing. 
* SYNAPSE dataset
     * In the SYNAPSE study, ECT is primarily used as a human model for epilepsy. Multiple pharmacotherapeutic interventions are studied to reduce post-ictal confusion. One of the hallmarks of this study is its acquisition of high-quality EEG data _during_ the seizure induced by ECT. Also multiple MRIs were acquired 30 minutes after the seizure.
     * Status: acquisition is ongoing. 



## Acquired data


__Clinical data__
|      Datasets     	| pre-ECT 	| during-ECT 	| post-ECT 	| follow-up 	|
|:-----------------:	|:-------:	|:----------:	|:--------:	|:---------:	|
| Seizure threshold 	|    X    	|            	|     X   	|           	|
|        Schema-ECT 	|    X    	|            	|     X    	|     X     	|
|             SNOEP 	|    X    	|            	|     X    	|     X     	|
|           SYNAPSE 	|    X    	|           	|     X    	|     X     	|


__structural MRI, resting-state functional MRI, Diffusion Tensor Imaging (DTI)__
|      Datasets     	| pre-ECT 	| during-ECT 	| post-ECT 	| follow-up 	|
|:-----------------:	|:-------:	|:----------:	|:--------:	|:---------:	|
| Seizure threshold 	|    X    	|            	|          	|           	|
|        Schema-ECT 	|    X    	|            	|     X    	|     X     	|
|             SNOEP 	|    X    	|            	|     X    	|     X     	|
|           SYNAPSE 	|    X    	|      X     	|     X    	|     X     	|


__Magnetic resonance spectroscopy__
|      Datasets     	| pre-ECT 	| during-ECT 	| post-ECT 	| follow-up 	|
|:-----------------:	|:-------:	|:----------:	|:--------:	|:---------:	|
| Seizure threshold 	|          	|            	|          	|           	|
|        Schema-ECT 	|    X    	|            	|     X    	|     X     	|
|             SNOEP 	|    X    	|            	|     X    	|     X     	|
|           SYNAPSE 	|    X    	|      X     	|     X    	|     X     	|


__ASL__
|      Datasets     	| pre-ECT 	| during-ECT 	| post-ECT 	| follow-up 	|
|:-----------------:	|:-------:	|:----------:	|:--------:	|:---------:	|
| Seizure threshold 	|        	|            	|          	|           	|
|        Schema-ECT 	|        	|            	|         	|             	|
|             SNOEP 	|    X    	|            	|     X    	|     X     	|
|           SYNAPSE 	|    X    	|      X     	|     X    	|     X     	|


__EEG__
|      Datasets     	| pre-ECT 	| during-ECT 	| post-ECT 	| follow-up 	|
|:-----------------:	|:-------:	|:----------:	|:--------:	|:---------:	|
| Seizure threshold 	|        	|            	|          	|           	|
|        Schema-ECT 	|        	|            	|         	|            	|
|             SNOEP 	|    X    	|            	|     X    	|     X     	|
|           SYNAPSE 	|    X    	|      X     	|     X    	|     X     	|



## Preprocessing

[FMRIprep](https://fmriprep.org/en/stable/)

[QSIprep](https://qsiprep.readthedocs.io/en/latest/)
