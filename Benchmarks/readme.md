#### Revealing and Mitigating the Spread of Harmful Content in Recommender Systems

This contains the constructed Datasets, TN, QB and EB-NeRD for our work "Revealing and Mitigating the Spread of Harmful Content in Recommender Systems" which aims to investigate recommender systems from a healthiness perspective.

These three datasets are enriched from existing content recommendation datasets, where we add harmfulness-related information into the original datasets, including harmfulness tag (healthy or harmful), and corresponding reasons that provide justifications for the assigned tags.

#### Item content information

TN_data.xlsx, QB_data.xlsx and EB_NERD_data.xlsx are item content information which mainly contains:

asin: original item ID.

tag: A binary label that classifies content as either healthy or harmful. 0 indicates harmful, and 1 indicates healthy.

reason: A textual explanation that provides the detailed reason supporting the healthiness classification.  

title: item title information.

title_english: English title information.

abstract: item abstract information.

abstract_english: English abstract information.

#### User behavior data

TN_behaviour.tsv, QB_behaviour.tsv and EB-NERD_behavior.tsv are user behavior data, that is, user-item interaction record, which follows the following format:

User_ID, Item_ID, Item_ID, ..., Item_ID

it indicates that a user (User_ID) has interacted with the following items.

