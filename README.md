# Identifying the Causal Variables in the Castle Doctrine Dataset 🏰

This project is part of the Causality course at the UvA during fall 2023. We work with the Castle doctrine dataset (Cheng et al., 2012) to identify whether the castle (stand-your-ground) doctrine influences the rates of violence, and what are the important variables influencing this relationship. You can also find the dataset in [this repository](https://github.com/NickCH-K/causaldata/tree/main/Python/causaldata/castle).

## Set-up
To install the `castle` environment, run the following in the terminal:

```
conda env create -f castle-env.yml
```

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
Cheng, Cheng and Hoekstra, Mark and Cheng, Cheng, Does Strengthening Self-Defense Law Deter Crime or Escalate Violence? Evidence from Castle Doctrine (June 2012). NBER Working Paper No. w18134, Available at SSRN: https://ssrn.com/abstract=2079878
