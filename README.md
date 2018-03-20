# TOUCAN_VR_data

The repository contains the data and post-processing code employed to generate the experimental results presented in [1], employing the TOUCAN-VR app [2].

Created by:

Universite Nice Sophia Antipolis (Universite Cote d'Azur) and CNRS  
Laboratoire d'Informatique, Signaux et Systèmes de Sophia Antipolis (I3S)

Contributors:

Savino DAMBRA  
Giuseppe SAMELA  
Lucile SASSATELLI  
Romaric PIGHETTI  
Ramon APARICIO-PARDO  
Anne-Marie PINNA-DERY

References:

[1] S. Dambra, G. Samela, L. Sassatelli, R. Pighetti, R. Aparicio-Pardo, A. Pinna-Déry "Film Editing: New Levers to Improve VR Streaming", ACM Multimedia Systems Conference (MMSys), Amsterdam, The Netherlands, June 2018.
[2] TOUCAN-VR https://github.com/UCA4SVR/TOUCAN-VR

## Usage
Download and unzip the zipped folder. The results have been processed with Matlab R2017a and python3.  

Folder 'analysis/DataAnalysis' contains the matlab script to generate the results presented in article [1] above. To do so, run 'HM_BW_Boxplot_AugExp.m' and 'Subjective_measures_boxplot_OctExp.m' ('HM_BW_Boxplot_OctExp.m' is also available though not detailed in [1]).  

Folder 'data_for_exp' contains information about the videos and parameters used for the experiments.  

Folder 'data_from_exp' contains the datasets resulting from both experiments (carried out in Aug. and Oct. 2017).

## Contact
For any question, please send an email to githubprojecttoucanvr@gmail.com
