Description of the folders:

1. log - to store API logs.

2. raw_data - to store the result of the API load.

3. data - to store the result of EDA.

4. tableau - visualizations.

Description of the files:

1. football-load.ipynb - the notebook is used to load initial raw data using Rapid API. The file is just for reference, you won't be able to run it. It requires an API key to run. To get the API key you need a subscription, which is not free. However, you can find the reslut of the load in the raw_data folder.

2. football-eda.ipynb - the notebook is used for EDA. It loads the raw files and processes them. It performs several steps: cleaning, transformation, initial analysis and statistical analysis. The result is a dataset for modeling which is stored in data folder.

3. football-model.ipynb - the notebook is used for modeling and analysis of the results. I compared several algorithms, analyzed the errors and performed an interpritation of the models. 

4. README.txt - describes all other files and folders. :)