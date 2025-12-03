#### Revealing and Mitigating the Spread of Harmful Content in Recommender Systems  

This is the code used to evaluate recommender systems' performance in terms of harmfulness.

The file harmfulnessMetric.ipynb is used to obtain recommender systems' performance under our proposed harmfulness-related metrics, HP@k and HO@k. 

HP@k (Healthy content Proportion) measures the proportion of healthy content
among the top-k recommended items, offering a straightforward assessment of healthy content
coverage. 

HO@k (Healthy content Ordering) further incorporates ranks of healthy content by
rewarding models that prioritize healthy content higher in the list.  

Specifically, you can obtain the top-k (top-20 supported by this file) recommendation lists of a model for a test set, i.e., the txt file saved under the datasets path, and then you can use the harmfulnessMetric.ipynb to obtain the model's performance under HP@k and HO@k.

We have presented six models' recommendation results on three datasets, and you can directly run the harmfulnessMetric.ipynb to examine their performance. The six models include GRU4Rec, NARM and BERT4Rec, as well as their enhanced version with our proposed HealthRec framework, named GRU4Rec+, NARM+ and BERT4Rec+ under the "datasets" path. 

For example, the file "prediction_health_TN_BERT4Rec.txt" means that it contains the recommendation results of model BERT4Rec under the TN dataset.

Note that, following common practices, we optimize existing methods according to their performance on Prec@5, so their performance on harmfulness-related metrics will hold a certain degree of fluctuation.

In the file "harmfulnessMetric.ipynb", you can set MODEL and DATASET to examine the healthiness performance of various models on different datasets.

MODEL: GRU4Rec, NARM, BERT4Rec, GRU4Rec+, NARM+, BERT4Rec+ 

DATASET: TN, QB, NERD

