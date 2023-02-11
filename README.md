# Capstone-Project

### Tasks To Do:
1. Figure out unrelated features in our dataset to remove those
2. Method to handle missing values
3. Method to handle unbalanced dataset
    1. create Dataset# 1, reduce number of real job postings to balance dataset
    2. create Dataset# 2, using SMOTE algorithm
4. List of two or three models we are going to use

### Tasks Done:
1. Gathering Dataset
2. Importing Dataset
3. Data Unbalancing:
    1. Dataset# 1: number of real job postings reduced. New dataset contains real positing 2000: and fake positings: 866
4. Remove/Add features from dataset
    1. Removed: job_id
    2. Removed: company_profile removed as most of the info is unrelated
    3. Added: has_company_profile, if positing has company profile then value is 1 otherwise 0.
    4. Removed: department, removed .. find our reason
