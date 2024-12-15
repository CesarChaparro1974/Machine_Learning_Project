![Alt Text](assets/machine_learning.png)

# Mobile carrier Megaline

## Overview
* Ther carrier has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra.
I have access to behavior data about subscribers who have already switched to the new plans. For this classification task, I need to develop a model that will pick the right plan. I’ve already performed the data preprocessing step, I move straight to creating the model.  
I developed a model with the highest possible accuracy. Checked the accuracy using the test dataset.  

### Data description
datasets/users_behavior.csv
Every observation in the dataset contains monthly behavior information about one user. The information given is as follows: 
1. сalls — number of calls,
2. minutes — total call duration in minutes,
3. messages — number of text messages,
4. mb_used — Internet traffic used in MB,
5. is_ultra — plan for the current month (Ultra - 1, Smart - 0).
