# TO BE OR NOT TO BE INSURED? 🧑‍🌾
## How Social Networks Influence One's Decision To Insure

This project is part of the Causality course at the UvA during fall 2023. We look at an experiment that investigated how the social environment of rice farmers in rural China influences whether they adopt weather insurance (Cai, De Janvry & Sadoulet, 2015), along with other variables such as demographics or previously adopting weather insurance.

## Set-up
To install the `causal_data_science_env` environment (Mac users only), run the following in the terminal:

```
conda env create -f causal_data_science_env_mac.yml
```

## Dataset
Data from a randomized experiment in rural China, focusing on weather insurance adoption among rice farmers. You can also find the dataset in [this repository](https://github.com/NickCH-K/causaldata/tree/main/Python/causaldata/social-insure).

## How to view this repository
You can follow the whole project by opening and running the `causal-estimation.ipynb` notebook. 

## The project pipeline 
We pay attention to the following:
1. **Exploratory data analysis**
* Testing for dependence of the variables
2. **Identifying estimands**
* Backdoor/frontdoor criterion, instrumental variables
3. **Estimating causal effects**
4. **Causal discovery**
5. **Validation and sensitivity analysis**


## References
*Cai, J., De Janvry, A. and Sadoulet, E., 2015. Social networks and the decision to insure. American Economic Journal: Applied Economics, 7(2), pp.81-108. DOI: 10.1257/app.20130442.*
