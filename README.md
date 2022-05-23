# How does subjective social class affect mobilizatipn of parental aid in the job search process?

The provided Jupyter notebooks are written in python 3.7.3. To install the required packages and dependences, please run the following code in reference to the provided `requirements.txt` file

```
pip install -r requirements.txt
```

# Exploratory findings:
## Results from logistic regression - mobilization of mother
Notable finding: the child's perception of their father's class and their tie strength with their mother are statistically signficant as predictors for mobiizing their mother in the job search process.
![](mother_activation_results.png "Results: mobilization of mother's network")

## Results from logistic regression - mobilization of father
![](father_activation_results.png "Results: mobilization of father's network")

## Significance of intial findings:
Firstly, the main predictor variables of interest (social class, tie strength, network size) were not able to predict the mobilization of the father in the job search process in logistic regression. However, the father's social class was statistically significant in predicting the mobilization of the mother when accounting for the predictor variables of interest and also controlling for race and gender of the respondent. Due to the small sample size, additional review is necessary to see if the results replicate (the sample was also non-representative with 0 self-reported identities of Hispanic/Latino ethinicity).

### Additional exploratory results (including participant demographics) can be found in the jupyter notebook: 
- [Jupyter Notebook : Initial data analysis](https://github.com/macs30200-s22/replication-materials-helyap/blob/main/child_network_survey_analysis.ipynb)


# Required packages
* statsmodel 0.13.2
* numpy 1.21.5
* pandas 1.3.5

### Instructions to re-run:
Load the provided csv file and run all lines in the Jupyter Notebook

# Citation:
* [Citation file](https://github.com/macs30200-s22/replication-materials-helyap/blob/main/CITATION.cff)
