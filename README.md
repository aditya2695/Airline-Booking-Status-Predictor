# Customer Feedback Analysis
 
<img src="images/cover_pic.jpg">

####



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

<img src="images/importances.png">

#### AUC-ROC

<img src="images/ROC.png">

AUC-ROC values range from 0 to 1, with a value of 1 indicating a perfect classifier, and a value of 0.5 indicating the performance of a random classifier. So, in this case, the classifier performs better than a random classifier and the result is decent.

