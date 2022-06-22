# Attacking-the-problem-of-leakage-in-CV

### Problem Setting  
How can we reduce leakage in CV?
### Existing methods
1. Purged K Fold CV  
   - What is Purged K Fold CV?
     - Purging is to remove from the training set all observations whose labels overlapped in time with those labels included in the test set.
     - Embargoing is to remove from the training set all features that are computed using the observations in the test set like 60-day vol. 
