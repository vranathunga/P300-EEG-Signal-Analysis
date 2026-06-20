# P300-EEG-Signal-Analysis
This project implements a complete P300 Event-Related Potential (ERP) analysis pipeline using EEG data from the BNCI 2015-003 Visual P300 Speller dataset

<p align="left">
  <img src="images/cover-img" width="350" title="cover image">
</p>

## Introduction :bulb:

### What is a P300 Speller 
P300 Speller is a type of Brain-Computer Interface (BCI) that allows a user to select letters using only brain activity measured by EEG. It was first introduced by Lawrence Farwell and Emanuel Donchin in 1988. The system relies on a brain signal called the P300 ERP.

### What is P300 Signal 
P300 is a positive EEG peak that appears approximately 300 ms after a rare and important stimulus is seen. It is commonly produced using the oddball paradigm, where rare target events are mixed among frequent non-target events. 

### Advantages of  we analyze P300 
The scans such as PET, MRI, CT shows the structure of the brain. These P300 show how the brain functions. Sometimes function brakes before structure changes. Therefore we can use this to identify major neurological disorders such as Alzheimer’s, ADHD by using P300. Moreover we use that for, 

Brain-Computer Interfaces (BCI) 
Measuring Attention 
Measuring Recognition 
Understanding Brain Function 

### Why do we need to analyze? 
EEG is noisy. Identifying whether it has a peak or not is not easy. Therefore we have to preprocess it and find a peak or not?

## Pipeline for P300 Analysis :mag:
- Load EEG
- Filter
- Extract events
- Create epochs
- Average target
- Average non-target
- Plot ERP
- Find P300 peak
- Calculate amplitude
- Calculate latency 

## Dataset :bar_chart:
BNCI Horizon 2020 Dataset: BNCI 2015-003 (Visual P300 Speller)
- URL - https://bnci-horizon-2020.eu/database/data-sets

## Technologies :hammer_and_wrench:
- Python
- Google Colab
- NumPy
- SciPy
- Pandas
- Matplotlib

## Methodology :rocket:
For analyzing EEG singnals for identify P300. First we will implement the pipeline for one .mat file and check whether pipeline works smoothly without any errors. Then if no any errors we can implement full pipeline into all ten .mat files

## Findings :hammer_and_wrench:
The major findings of this analysis is to identify P300 and identify thier amplitude and latency. From those data we can use it for meaningful researches. To showcase how to do it using several EEG signals is demonstrated here. So as findings I am presenting latency and amplitude of all ten files and one file in csv format and visually. Those csv files are attached to the repository for your reference.

### Plot visualization for one mat file
<p align="left">
  <img src="images/plot-one-mat-file" width="350" title="plot-one-mat-file">
</p>

### Plot visualization for ten mat file
<p align="left">
  <img src="images/plot-ten-mat-file" width="350" title="plot-ten-mat-file">
</p>
