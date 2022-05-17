# Survival Model for Breast Cancer

Survival model with Random Survival Forest, Support Vector Machine, Gradient Boosted Model and Neural Network


Survival analysis is a branch of statistics for analyzing the expected duration of time until one event occurs, such as death in biological organisms and failure in mechanical systems. To demonstrate how to create survival models, we are going to use data from the German Breast Cancer Study Group (GBSG-2) on the treatment of node-positive breast cancer patients. The dataset can be loaded as part of sksurv.datasets 

It contains data on 686 women and 8 prognostic factors: 
1. age
2. estrogen receptor (estrec)
3. whether or not a hormonal therapy was administered (horTh)
4. menopausal status (menostat)
5. number of positive lymph nodes (pnodes)
6. progesterone receptor (progrec)
7. tumor size (tsize)
8. tumor grade (tgrade)
