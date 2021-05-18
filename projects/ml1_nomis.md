[<img src="../images/ml1_nomis_res.png">](https://raw.githubusercontent.com/josephazanza/josephazanza.github.io/master/images/ml1_nomis_res.png)

# Nomis Case Study: Optimizing the Loan Pricing System of e-Car

[Joseph Matthew Azanza](https://www.linkedin.com/in/josephazanza/) | [Christian Angelo Delariarte](https://www.linkedin.com/in/jelodelariarte/) | [Lyon Alec Fiesta](https://www.linkedin.com/in/lyonfiesta/) | [Alfonso Limpo](https://www.linkedin.com/in/alfonsolimpo/) | [Rea Tanguilig](https://www.linkedin.com/in/rea-tanguilig/) <br>
Asian Institute of Management

## Abstract
<p align='justify'>
As consultants for Nomis Solutions, we are tasked to help optimize e-Car’s loan pricing system. The current model is through a risk-based assessment of the customer, using three parameters such as loan term, loan type, and customer risk band. However, e-Car’s current system has failed to consider the price sensitivity of their customers in pricing their loans. Given e-Car’s loan data containing 12 distinct features, our team has developed a workflow involving two machine learning models and a price optimization process that can identify unique market segments and optimize the loan prices. The models we developed are a Random Forest Regressor with an accuracy of 97.1%, used to predict the base APR rate for customers. The second model is a Gradient Boosting Classifier with an accuracy of 86.8%, used to predict whether customers will accept or reject the loan. The workflow utilizes the two models in succession. For customers initially predicted to accept the quoted loan, the rate was incrementally increased until the prediction changes to reject; while customers initially predicted to reject the quoted loan, the rate was incrementally decreased until the prediction changes to accept. Certain thresholds were put in place for both adjustments and e-Car can adjust these depending on their risk appetite. Our workflow resulted to an increase in loan rates by 162.56% and increase in profit by 139.14% compared to e-Car’s current system. The workflow can further be optimized by including additional data such as customers who defaulted. The workflow can also be re-trained and fine-tuned anytime e-Car deems it fit
<br><br>
<b>Keywords:</b> supervised learning, ensemble methods, price optimization
</p>

---

**Source code can be provided upon request, and upon approval of all project collaborators**

---

## [Back to main page](https://josephazanza.github.io/)