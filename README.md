# project_code_explaination-group5
We have devided our codes into two separate notebooks. The "IST718_Final_Project_EDA_Group5.ipynb" is used for data cleaning and exploratory analysis,
which does not involve any use of PySpark.
We included visualizations that can help answer to our inference questions and some other ones for worth investigating trends of the data in the notebook.

The second notebook called "IST718_Final_Project_Models_Group5.ipynb", which contains all the models we have built for making predictions. We started with 
visualizing 2 dimensional princeple components to see how the data is distributed, then ran Decision Tree, Logistic Regression, Random Forest, and Gradient
Boosted Trees on three resampling techniques. 
After Comparing model performance, we decided to use undersampling for grid search, over-sampling and over&under sampling are provided in the appendix section.
We had set enable_grid_search to be False before submission, and included our best model for each machine learning algorithm in the notebook for predicting 
the validation data.
