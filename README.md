# California-Housing-Prediction
The Californian housing dataset from has been used to predict the price based on numerous features like "number of bedrooms", "proximity to ocean", "median income" etc and the Machine learning model is developed after pre-processing the raw data using custom transformer function.

steps followed to develop this machine learning model are:
<ol>
  <li>Performed EDA (Exploratory data analytics)</li>
  <li>Developed a custom transformer to transform the columns into numerical or categorical or vice versa and create new features based on the needs.</li>
  <li>Developed a full pipeline to impute the missing values, transform the data, scale the data using different scaling techniques like StandardScalar.</li>
  <li>Developed different models like ‘Linear Regression’, ‘Decision Tree Regressor’, ‘Random Forest Regressor’ for the pre-processed data via cross validation technique like k-fold cross validation.</li>
  <li>Fine-tuned the final model (Random Forest Regressor) using hyper-tuning techniques like ‘Grid Search CV’ and ‘Random Search CV’.</li>
  <li>evaluated the model using metrics like 'root mean squared error'</li>
  
</ol>
