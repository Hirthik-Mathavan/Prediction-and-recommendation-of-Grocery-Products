## Prediction and recommendation of Grocery Products

**Abstract**

In the e-commerce shopping experience, product recommendations come in many forms: they may be used to recommend other products on one product’s page (Amazon’s “Frequently bought together” feature, for instance), or they may be used on the checkout page to show customers, the products they may be interested in based on their total order. We have seen various departmental stores suffering because of the complexity and work overload they need to face. The same concept can be applied to grocery stores as well. 

Further, recommendations may be more helpful if they are targeted towards a specific segment of customers rather than made uniformly. For instance, if one group of customers tends to buy a lot of non-dairy milk substitutes and another tends to buy traditional milk, it may make sense to make different recommendations to go along with that box of Cheerios. In order to make tailored recommendations, we first segmented Instacart users based on their purchase history using K-Means clustering. We then made recommendations based on the product association rules within those clusters.

**Dataset**

The venture's objective is to foresee which items will be in a client's subsequent request. The dataset for this task is a social arrangement of records portraying customers' requests over time. The dataset is anonymized and contains an example of more than 3 million entire supply orders from over 200,000 Instacart clients. For every client, we give somewhere in the range of 4 and 100 of their requests, with the arrangement of items acquired in each request. It likewise gives the week and hour of the day the request was set and a relative proportion of time between requests. 
