# Orthopedic_deepAutoML
dataset from Kaggle



<img width="971" alt="Screenshot 2022-07-18 at 04 32 08" src="https://user-images.githubusercontent.com/100385953/179437201-ded9e397-e34d-4312-9138-c8c0fa119afe.png">

Source: https://github.com/AutoViML/deep_autoviml/



Auto_ViML was designed for building High Performance Interpretable Models with the fewest variables needed. The "V" in Auto_ViML stands for Variant because it tries multiple models with multiple features to find you the best performing model for your dataset. The "i" in Auto_ViML stands for "interpretable" since Auto_ViML selects the least number of features necessary to build a simpler, more interpretable model. In most cases, Auto_ViML builds models with 20%-99% fewer features than a similar performing model with all included features (this is based on my trials. Your experience may vary).

Auto_ViML is every Data Scientist's model accelerator tool that:

Helps you with data cleaning: you can send in your entire dataframe as is and Auto_ViML will suggest changes to help with missing values, formatting variables, adding variables, etc. It loves dirty data. The dirtier the better!
Performs Feature Selection: Auto_ViML selects variables automatically by default. This is very helpful when you have hundreds if not thousands of variables since it can readily identify which of those are important variables vs which are unnecessary. You can turn this off as well (see API).


![sulov_xgboost](https://user-images.githubusercontent.com/100385953/179437367-1041c0a8-dd3b-4b76-b551-0f7aeb2e0109.png)

Install deep_autoviml

!pip install deep_autoviml or !pip install git+https://github.com/AutoViML/deep_autoviml.git

In [1]:
# !pip install deep_autoviml
!pip install git+https://github.com/AutoViML/deep_autoviml.git
