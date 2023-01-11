# Customer Churn Prediction
 
<div style="text-align:center;">
    <img src="images/cover_pic.jpg" width="500">
</div>

#### Introduction

"Customer churn" refers to the phenomenon when a customer stops doing business with a company. Predicting customer churn is an important task in the field of business analysis, as it can help companies to identify at-risk customers and take steps to retain them. In this project, a model is developed to predict customer churn for a fictional company called Swan-Teleco.

The goal of this project is to accurately predict which customers are at risk of leaving the company, so that targeted retention efforts can be made. The model uses a dataset that includes information about the customers, such as their demographic information, their account details, and their interactions with the company. Machine learning algorithms were applied to this dataset to train the model and make predictions about customer churn.

The performance of the model was evaluated using metrics such as accuracy, precision, recall, and AUC-ROC. The model achieved a good performance, which demonstrates the feasibility of using machine learning to predict customer churn. This project can be a valuable tool for Swan-Teleco to understand the factors that contribute to customer churn and take steps to prevent it, thus improving customer retention and overall business.


### Evaluation

<ul>
    <li> 
        The most important variable in the model was booking_origin with a score of 0.30
    </li> 
    <li>route,purchase lead and length of stay were significant
    </li>
    <li>  
        Also, Information about the flight, e.g. flight
        duration were also significant.
    </li> 
    <li> 
        RF_model1 and RF_model2 are random forest models and both has similar accuracy of 71% but RF_model2 has better precision and recall
    </li> 
</ul>

<table>

<tr>
    <th>Model</th>
    <th>Accuracy</th>
    <th>Precision</th>
    <th>Recall</th>
    <th>F1-score</th>
</tr>

<tr>
    <td>Base Model</td>
    <td>0.83</td>
    <td>0.40</td>
    <td>0.24</td>
    <td>0.30</td>
</tr>

<tr>
    <td>RF_model1</td>
    <td>0.71</td>
    <td>0.64</td>
    <td>0.61</td>
    <td>0.68</td>
</tr>
<tr>
    <td>RF_model2</td>
    <td>0.71</td>
    <td>0.66</td>
    <td>0.70</td>
    <td>0.68</td>
</tr>
</table>



#### Feature Importances

 <div style="text-align:center;">
    <img src="images/importances.png">
</div>

#### AUC-ROC

 <div style="text-align:center;">
    <img src="images/ROC.png">
</div>
AUC-ROC values range from 0 to 1, with a value of 1 indicating a perfect classifier, and a value of 0.5 indicating the performance of a random classifier. So, in this case, the classifier performs better than a random classifier and the result is decent.

