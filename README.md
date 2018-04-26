# Paradoxical Collider Effect in the Analysis of Non-Communicable Disease Epidemiological Data: a reproducible illustration and web application
In the epidemiological literature different explanations have been proposed to describe the paradoxical protective effect of established risk factors. A collider for a certain pair of variables (exposure and outcome) is a third variable that is influenced by both of them. Controlling for, or conditioning the analysis on (i.e., stratification or regression) a collider, can introduce a spurious association between its causes (exposure and outcome). Based on a motivating example in non-communicable disease epidemiology, we generated a dataset with 1,000 observations to contextualize the effect of conditioning on a collider. We estimate the effect of 24-hour dietary sodium intake in grams on systolic blood pressure in mmHg accounting for the effect of age in years to illustrate the paradoxical effect of 24-hour dietary sodium intake on systolic blood pressure after conditioning on a collider (24-hour urinary protein excretion in mg). If the main objective of an study is to obtain a predictive model that makes accurate predictions of the outcome researchers may probably condition on the collider to possibly increase the precision of the prediction. However, if the main objective is to create a model of reality that is useful in making decisions based on assumptions about the causal relationship of variables (a structural causal framework), then conditioning on the collider would introduce collider bias and probably paradoxical effects. We provide R-code in easy-to-read boxes throughout the manuscript and a GitHub repository: https://github.com/migariane/ColliderApp for reproducibility and an educational web application allowing real-time interaction to visualize the paradoxical effect of conditioning on a collider http://watzilei.com/shiny/collider/.



