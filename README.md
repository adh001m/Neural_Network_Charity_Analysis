# Neural_Network_Charity_Analysis
## Overview
#### To familiarize oneself with neural networks and 'onehotencoder' for data preprocessing and analysis

## Results
### Data Preprocessing
####
- Target Variable: Whether or not an application is succesful for a charity, "IS_SUCESSFUL" 
- Feature Variables: Application type, Affiliation, use case, organization, status, ask amount
- Non-Featured Variables: Special considerations, classification, ein, name
### Compiling, training, and evaluating the model
####
- Ideal Layers: 3
- Target Performance: 75% accuracy.  My achieved performance was of 72% accuracy. Target performance: failed.
- Steps taken to improve model: Increasing hidden layders from 2 to 3, gradually decreasing hideen nodes, removing extra 'type' or classification columns.

## Summary
Overall, I felt as if my second model created did a well enough job when it came to removing unnecessary columns. I had an accuracy score of 72% with a data loss of 57% which isn;t vastly different than my first attempt.  The one thing I'd change for better performance would be the hidden layers and nodes amount, however, I did learn that having too many hidden layers can, in fact, reduce our accuracy as evidenced from attempt number three.
