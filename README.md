# Purged and Embargoed K Fold CV (PEK-Fold CV) 

### Problem Setting  
How can we reduce leakage in CV?
### Proposed method
PEK Fold CV (Purged and Embargoed K Fold CV) 
   - What is PEK Fold CV?
     - Purging is to remove from the training set all observations whose labels overlapped in time with those labels included in the test set.
     - Embargoing is to remove from the training set all features that are computed using the observations in the test set like 60-day vol. 
   - What is good about it?
     - The decrease in leakage leads to decreasing the risk false discovery.
   
   
