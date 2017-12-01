# powerRMST

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
    
