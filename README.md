### General Information
This is a binary classification project. The aim is to predict whether or not a customer will be satisfied with their experience as well as to explain which factors best explain whether or not a customer will be satisfied. The data was very well seperated and test performance of around 96% was achieved, using Random Forest. in order to explain the feature importances, SHAP values were used. This was able to explain both the global significance of different features as well as explain how specific predictions were made by the model. SHAP was chosen due to its ability to provide both global and local interpretability.
The runtime is rather long. There are two reasons for this. The dataset is fairly large, by classical python standards. This meant that model fitting took some time (~10 mins). Secondly, calculation of SHAP values took a significant amount of time (~50 mins).

### Technology
This was run using Python 3.6.9 on Google Colab.

### Reproduction instructions
- Download datasets + ipynb
- Update paths for data load section
- Find something to do while you wait for the results!
