# COVID-19 ICU Prediction:
A machine learning project where, we predict if a patient requries ICU or not, based on the test reports using Python and Scikit-Learn. <br>
So, the dataset for this project is taken from kaggle.<br>

## COVID-19 - Clinical Data to assess diagnosis 
Link for the dataset : https://www.kaggle.com/S%C3%ADrio-Libanes/covid19
<br><br>
## The Project
The notebook to refer is the final.ipynb <br>
Our aim was to find a patient who is suffering from COVID should be admited to an ICU or not. <br>
The data for each patient is taken for a window size of 2 hours from the time they are admited to the hospital to 12 hours. <br>
There were many missing values needed to be handled and the details regarding the handling of missing values was explained in the notebook.<br>
There insights we could find as was been visulised as well and they explained in the notebook.<br>
Few factors were about :
<ul>
<li>Age</li>
<li>Gender</li>
<li>Type of diseases they are suffering</li>
<li>Etc..</li>
</ul>
<br>
After the getting the insights we built few machine learning models like,
<li>SVM</li>
<li>Random forest classifer</li>
<li> Logistic Regression </li>
<br><br>
So, when seen in the notebook the accuracy for all models are less than 90% which is pretty bad . The next step for this project is to increase the accuracy, for which we need to tune our models or add more factors in our models.<br>
Will be updating the notebook and the readme file soon after we increase the accuracy of our models.
