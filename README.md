Wine quality-MODEL DEPLOYMENT

![image](https://user-images.githubusercontent.com/111189874/189470455-4b3812ba-3135-4f09-a457-43fa75f646fd.png)

1. About the dataset:
* The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

* These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.

2. Requirements:
* python
* numpy 
* Jupyter notebook
* pandas
* skleran libraries
* seaborn
* css
* Html
* JS

3. Data cleaning:
* first we load the data in the jupyter notebook.
*  clean the data by data preprocessing.

4. Data Visualization:
* Showing Correlation (heatmap):

![image](https://user-images.githubusercontent.com/111189874/189470982-26a14e80-2eb3-49fe-b368-02253bf60a57.png)


* By Using seaborn:

![image](https://user-images.githubusercontent.com/111189874/189470724-3e7ea92b-c2d2-444a-912a-0ac1b46c4ff5.png)


5. Splitting & Training hte data :
* using  train_test_ split we split the data .
* We train the data.
* then we test the data.


6. Saving the  model in the pickle file formate.

7. After that we write the CSS , Html, JS code in the website.

8. Connecting the code with the flask.

9. We deploy the  odel in a website and then try to  predict the model .




