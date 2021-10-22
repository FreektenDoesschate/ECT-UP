
# ECT imaging data: Uniform (pre)processing 
This repository contains the pipeline for uniform preprocessing, quality control and processing for electroconvulsive therapy (ECT) imaging data acquired in Rijnstate hospital Arnhem and AMC Amsterdam. Furthermore, we provide a description of the available data, documentation on the pipeline, and example pieces of text that describe the analysis for your manuscript. 

 </br> 
 ***
 </br>

#### Table of contents
[Datasets](#Datasets)  
[Datatypes](#Datatypes)  
[Preprocessing](#Preprocessing)  
[Quality control](#Quality-control)  
[Processing](#Processing)  
[Dataformats](#Dataformats)  
[Data availability](#Data-availability)  
[Current projects](#Current-projects)

 </br> 
 ***
 </br>

## Datasets
Multiple ECT-imaging datasets were acquired:

*   Seizure threshold dataset</b> </summary>
    *  This dataset was acquired in order to study neuroimaging and clinical predictors of seizure threshold in ECT. See related papers for the [clinical characteristics](https://link.springer.com/article/10.1007/s00406-012-0342-7/tables/1) of the sample. For papers on the structural MRI data, see [here](https://www.sciencedirect.com/science/article/pii/S1935861X12002094?casa_token=cAC-WLm3LVcAAAAA:gm4tDvav6UkNTPFnTLWB_7c2fY4bnB_o-BNe3HnInR2mOL0qw0iFPD7MNEdiymz7QwEy4v7DvGk) and [here](https://www.frontiersin.org/articles/10.3389/fpsyt.2014.00169/full). And another paper on the [Resting-state functional MRI (rs-fMRI) data](https://www.nature.com/articles/mp201478). 
    *  Study status: data acquisition is finished. 
* Schema-ECT dataset
     * This dataset was acquired to study a combined psychological+ECT intervention. For a description of the intervention see this [paper](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2768949), with a brief clinical description of the sample [here](https://cdn.jamanetwork.com/ama/content_public/journal/jamanetworkopen/938527/zoi200468t1.png?Expires=1636631862&Signature=nWlCfYCET7ojxyvCuaFI5kitSWKRMCwvL~d5EF3blsRjbXMKw4zxSAsV6nRbeaOsUY6fYXKS9atC6FiCngE4EOIoVbNJuW4EsXfnjvY0SKLxkvh~GM3Ij9vdUhWI1YI4pGXww~h8amcKYizUJRt3ehFKxWZoASeQI9OoxXyw4orAge8AGmlhgv~bDyjb5KWUnoqiWtQUacBcz3nAdRAjh5El03wRKsSjvJZ7kybzNnv~LVRLQIYlcwAlxvK2KRshAtN-Vn2w3ULVxyriDm08ZGejQn0A4g3vfTO9VqTXvVlFqmFm3haArQakZGYBf3bRQG2Vo~2dL~-t09Khtn2qNA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA). This dataset was acquired at both the Rijnstate and AMC site.
     * Status: data acquisition is finished.
* SNOEP dataset
     * SNOEP stands for Study on Neuroimaging predictors of Outcome in ECT Patients. This dataset is a continuous acquisition of neuroimaging and clinical data in ECT with the primary objective to predict treatment outcome.
     * Status: acquisition is ongoing. 
* SYNAPSE dataset
     * In the SYNAPSE study, ECT is primarily used as a human model for epilepsy. Multiple pharmacotherapeutic interventions are studied to reduce post-ictal confusion. One of the hallmarks of this study is its acquisition of high-quality EEG data _during_ and after the seizure induced by ECT. Also multiple MRIs were acquired 30 minutes after the seizure.
     * Status: acquisition is ongoing.
* Healthy control dataset
     * One of the current aims is to collect data on healthy controls that match patients of the schema-ECT dataset. Extensive cognitive data will be acquired in this dataset. 
     * Status: awaiting for start acquisition. 


## Datatypes

<details>
<summary> <b>Clinical and demographic data</b> </summary>
    
|      Datasets     | pre-ECT 	| during-ECT 	| post-ECT 	| follow-up 	|
|:-----------------:|:-------:	|:----------:	|:--------:	|:---------:	|
| Seizure threshold |    X    	|            	|          	|           	|
|        Schema-ECT |    X    	|            	|     X    	|     X     	|
|            SNOEP 	|    X    	|            	|     X    	|     X     	|
|          SYNAPSE 	|    X    	|           	|     X    	|     X     	|

</details>


<details>
<summary> <b>structural MRI</b> </summary>

|      Datasets     	| pre-ECT 	| during-ECT 	| post-ECT 	| follow-up 	|
|:-----------------:	|:-------:	|:----------:	|:--------:	|:---------:	|
| Seizure threshold 	|    X    	|            	|          	|           	|
|        Schema-ECT 	|    X    	|            	|     X    	|     X     	|
|             SNOEP 	|    X    	|            	|     X    	|     X     	|
|           SYNAPSE 	|    X    	|      X     	|     X    	|     X     	|
  
</details>    
    

<details>
<summary> <b>resting-state fMRI</b> </summary>

|      Datasets     	| pre-ECT 	| during-ECT 	| post-ECT 	| follow-up 	|
|:-----------------:	|:-------:	|:----------:	|:--------:	|:---------:	|
| Seizure threshold 	|    X    	|            	|          	|           	|
|        Schema-ECT 	|    X    	|            	|     X    	|     X     	|
|             SNOEP 	|    X    	|            	|     X    	|     X     	|
|           SYNAPSE 	|    X    	|      X     	|     X    	|     X     	|

</details>   
 
 
<details>
<summary> <b>Diffusion Tensor Imaging (DTI)</b> </summary>

|      Datasets     	| pre-ECT 	| during-ECT 	| post-ECT 	| follow-up 	|
|:-----------------:	|:-------:	|:----------:	|:--------:	|:---------:	|
| Seizure threshold 	|    X    	|            	|          	|           	|
|        Schema-ECT 	|    X    	|            	|     X    	|     X     	|
|             SNOEP 	|    X    	|            	|     X    	|     X     	|
|           SYNAPSE 	|    X    	|      X     	|     X    	|     X     	|
 
</details>      
    

<details>
<summary> <b>Magnetic Resonance Spectroscopy (MRS)</b> </summary>

|      Datasets     	| pre-ECT 	| during-ECT 	| post-ECT 	| follow-up 	|
|:-----------------:	|:-------:	|:----------:	|:--------:	|:---------:	|
| Seizure threshold 	|       	|            	|          	|           	|
|        Schema-ECT 	|    X    	|            	|     X    	|     X     	|
|             SNOEP 	|    X    	|            	|     X    	|     X     	|
|           SYNAPSE 	|    X    	|      X     	|     X    	|     X     	|

</details>     

<details>
<summary> <b>Arterial Spin Labeling (ASL)</b> </summary>

|      Datasets     	| pre-ECT 	| during-ECT 	| post-ECT 	| follow-up 	|
|:-----------------:	|:-------:	|:----------:	|:--------:	|:---------:	|
| Seizure threshold 	|       	|            	|          	|           	|
|        Schema-ECT 	|       	|            	|         	|           	|
|             SNOEP 	|    X    	|            	|     X    	|     X     	|
|           SYNAPSE 	|    X    	|      X     	|     X    	|     X     	|

</details>     


<details>
<summary> <b>Electroencephalography (EEG)</b> </summary>

|      Datasets     	| pre-ECT 	| during-ECT 	| post-ECT 	| follow-up 	|
|:-----------------:	|:-------:	|:----------:	|:--------:	|:---------:	|
| Seizure threshold 	|       	|            	|          	|           	|
|        Schema-ECT 	|       	|            	|         	|           	|
|             SNOEP 	|    X    	|            	|     X    	|     X     	|
|           SYNAPSE 	|    X    	|      X     	|     X    	|     X     	|

</details>   


## Preprocessing

The goal is to perform uniform preprocessing for all modalities across datasets. 
[Here](UP-preprocessing) we provide for each modality:
* A detailed description of the preprocessing steps and software used
* Code that was used to perform preprocessing
* The current status of the preprocessing for each modality
* Example texts on the preprocessing procedurefor your manuscript.


## Quality Control

We aim to perform state-of-the-art quality control (QC) for each datamodality that was acquired. Quality was both assessed using quality metrics and visual inspection. [Here](UP-QC) you'll find for each modality: 
* A detailed description of the QC process
* The current status of the QC process 
* Example texts on the QC proces to include in your manuscript

## Processing (1st-level analysis)

To make the proces from hypothesis to paper easier and faster, we aim to extract features from each datamodality that can be used with ease. [Here](UP-processing) you'll find for each modality:
* The list of datafeatures we aim to extract
* The code we used for analysis
* Essential papers on the performed analysis
* The current status of the analysis
* Post-processing QC checks? 

## Dataformats

We aim to provide two dataformats for your final analysis:
* The dataformat that is provided by the specific 1st-level analysis (e.g., IC maps and weights for the ICA analysis on rs-fMRI data)
* We aim to provide each feature in csv format that easy to load into your statistics software of choice (SPSS/MATLAB/R/Python etc)


## Data availability
Data can be accessed in two ways (?):
* All data (in raw, intermediate, processed, and csv-file format) will be available through the AMC psychiatry research server. 
* By reasonable request, csv files on specific features can be provided to perform analysis outside of the server (e.g. on your own computer).

## Current projects
Click [here](UP-projects) for an overview of the current projects and their status. 
