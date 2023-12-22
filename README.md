# TO BE OR NOT TO BE INSURED? 🧑‍🌾
## How Social Networks Influence One's Decision To Insure

This project is part of the Causality course at the UvA during fall 2023. We look at an experiment that investigated how the social environment of rice farmers in rural China influences whether they adopt weather insurance (Cai, De Janvry & Sadoulet, 2015), along with other variables such as demographics or previously adopting weather insurance.

## Set-up
To run the jupyter notebook yourself, install the `causal_data_science_env` environment.  Run the following in the terminal, depending on your OS:

```
conda env create -f causal_data_science_env_mac.yml
```
OR
```
conda env create -f causal_data_science_env_linux.yml
```
OR
```
conda env create -f causal_data_science_env_windows.yml
```

## Dataset
Data from a randomized experiment in rural China, focusing on weather insurance adoption among rice farmers. You can also find the dataset in [this repository](https://github.com/NickCH-K/causaldata/tree/main/Python/causaldata/social-insure).

## How to view this repository
You can follow the whole project by opening and running the `causal-analysis.ipynb` notebook. 

## The project pipeline 
We pay attention to the following:
1. **Exploratory data analysis**.
Testing for dependence of the variables, getting hints for the causal graph, and estimating it using common sense.
2. **Identifying estimands**. 
Using backdoor/frontdoor criterion, instrumental variables approaches to find ways to correct for spurious correlations in the causal graph.
3. **Estimating causal effects**. 
Identifying how the effect of various variables on the outcome variable.
4. **Causal discovery**. Automatically discovering the causal graph from observational data to test our initial estimate.
5. **Validation and sensitivity analysis**. Checking how robust our estimations are and concluding our analysis.


## References
*Cai, J., De Janvry, A. and Sadoulet, E., 2015. Social networks and the decision to insure. American Economic Journal: Applied Economics, 7(2), pp.81-108. DOI: 10.1257/app.20130442.*
