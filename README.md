# AutoNEU2021_DomainAdaptation

This repository contains the datasets for Domain Adaptation challenge for AutoNEU 2021, CVPR Workshop. For more details, please visit https://cvit.iiit.ac.in/autonue2021/challenge.html

# Source datasets:
For the Cityscapes dataset, participants are requested to use the fine images (around 3200).
For the other datasets (BDD, GTA and Mapillary), the list of image names are given in the csv files in the folder "Source".

Participants are requested to download the datasets from original websites, given below for easy reference:-
https://www.cityscapes-dataset.com/
https://www.mapillary.com/
https://bdd-data.berkeley.edu/ (you might have to click on Advanced tab, and then click on "proceed to bdd-data.berkeley.edu")
https://download.visinf.tu-darmstadt.de/data/from_games/

# Target dataset:
For the IDD dataset:
1. Register an account at http://idd.insaan.iiit.ac.in/, with event selected as "AutoNUE Challenge 2019".
2. Go to Download > Download page in the menu.
3. Dataset consists of 2 parts which are available for download.
   - First part is the IDD - Segmentation that was released in 2018.
   - The other part is IDD 20k II that was released in 2019.
   
   Extract both the downloaded compressed files in to the same folder.

For the Semi-supervised Domain Adaptation challenge, please use the datasets mentioned in previous section for the source. 
For the target dataset, we consider two sub-settings, one with 500 samples from IDD training set, and the other with 1000 samples from the same. Please refer to the csv files shared in Folder "Target_SemiSupervised".
