# Customer Feedback Analysis
 
<img src="images/cover_pic.jpg">

### Evaluation

<ul>
    <li> 
        The most important variable in the model was
        purchase_lead, that is the time between purchase and
        departure.
    </li> 
    <li>  
        Information about the flight, e.g. flight time and
        duration was also significant, however booking origin of
        the customer was not important.
    </li> 
    <li> 
        The accuracy of the model was approximately 0.7
        (Precision) and 0.003 (Recall), showing that this model
        requires more improvement. I suggest adding more
        customer-centric features into the model.
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

RF_model1 and RF_model2 are random forest models and both has similar accuracy of 71% but RF_model2 has better precision and recall

#### Feature Importances

<img src="images/importances.png">

#### ROC

<img src="images/ROC.png">

