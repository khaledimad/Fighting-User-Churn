# Fighting-User-Churn

# Business Objective
## Industry Background
Millions of users use music streaming services to play their favorite songs. These services
usually offer free tier plans with advertisements or ad free premium subscription plans that come
with additional features. With the increased demand in music streaming services, several players
have entered the market in aim of acquiring potential customers. This has prompted such
services to continuously upgrade and improve their platform to ensure that their users are
satisfied with their free or premium subscriptions.

With the increased reliance in implementing data-driven decisions to fulfill business needs, these
services are collecting data from their users such as activity logs, subscription changes and
device types to define key metrics associated with customer satisfaction.

## Problem Statement
It is a known fact that it costs much more to acquire customers than to keep an existing one,
sometimes by up to five times [1]. According to research done by Bain & Company [2],
increasing customer retention rates by 5% increases profits by 25% to 95%. With such figures,
it's paramount for businesses to focus their efforts on satisfying existing customers. The goal of
our project is to help Sparkify, a music streaming service, to identify ways to reduce customer
premium churn where churn refers to paying subscribers who cancel their premium subscription.

# Role of Analytics
Our business initiative is primarily driven by a data-driven approach. A classification machine
learning model may be implemented which will use customer features as input and churn labels
as an output, based on historical data, to identify features correlated with churn. Accordingly, we
are able to predict which customers are likely to churn in the future based on similar behaviors in
order to proactively prevent customers from cancelling their services. Analytics will also be
widely used to address key issues which will in evaluating the success of our business initiative.

# Type of Analytics: 
Due to high costs involved in the implementation, we have to ensure good performance of the
model - high accuracy and recall. For the recommendation generation, we have to ensure the
model is explainable.
We ran three types of models - Logistic Regression , Gradient Boost , Random Forest.
Through Random Forest, we got an F1 score of 68% ,and AUC of 67% ( 10% improvement
from GBM model). Also, to make sure, we account for class imbalance and superior predictive
power, we end up choosing Random Forest and use metrics like importance of variables to see
feature insights.

# References
[1] https://www.invespcro.com/blog/customer-acquisition-retention/<n>
[2] https://media.bain.com/Images/BB_Prescription_cutting_costs.pdf
