# powerRMST

This project contains the material in support of the following paper: Weir, IR., Trinquart, L. Design of non-inferiority randomized trials using the difference in restricted mean survival times. Clin Trials 2018; 15: 499-508. https://www.ncbi.nlm.nih.gov/pubmed/30074407
We ask that if you use these data to please include the above citation. 

all_reconstructed_data.txt

    reconstructed data for 35 non-inferiority clinical trials included in all_reconstructed_data.txt
      All 35 trials (variable "ID") have time to event outcomes. One row per subject. 
      Variable "Time" indicates time of event occurence
      Variable "Event" indicates whether subject had event (1) or not (0)
      Variable "Arm" indicates treatment assignment to experimental arm (1) or control arm (0)
   
sample size.R 
  
    Includes R code for function to determine power under a given sample size using a 
      non-inferiority margin based on the difference in RMST. 
    
    Includes iterative process for determining required sample size in a trial with specified 
      parameters (accrual period, allocation ratio, etc) to achieve a desired target power. 
    
