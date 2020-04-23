# Government policies and Social Distancing
Non-pharmaceutical government policies have led to social distancing - our best hope to contain COVID-19 until vaccine is developed. However, these NPIs come at an economic cost. To understand the impact of government policies on the social distancing, the community mobility data can be used to estimate/quantify the impact of each of the government policy.

In this notebook, we use a simple lasso regression to find how the goernment policies affect social distancing. Data includes:
1. <a href="https://www.google.com/covid19/mobility/">Google community movement data (% change in user mobility over time)</a>
2. <a href="https://covid19.healthdata.org/united-states-of-america">Government NPIs introduced and implemented across states</a>
