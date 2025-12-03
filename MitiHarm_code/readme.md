#### Revealing and Mitigating the Spread of Harmful Content in Recommender Systems

This is the code of our proposed framework MitiHarm, which is a generic and model-agnostic framework that can be seamlessly integrated into existing models to promote healthy content dissemination.

We instantiate our MitiHarm framework on three popular recommendation models: GRU4Rec, NARM, and BERT4Rec, and the codes including original model and its enhanced version with HealthRec are presented in these files.

For GRU4Rec, the codes are provided under the "GRU4Rec" path, where you can run "main.py" to run original GUR4Rec model, and use "mainhealth.py" to run its version enhanced by our HealthRec. The processed data of three datasets is located under the path "datasetsHealth".

For NARM, the codes are provided under the "NARM" path, where you can run "main.py" to run original NARM model, and use "mainhealth.py" to run its version enhanced by our HealthRec. The processed data of three datasets is located under the path "datasetsHealth".

For BERT4Rec, the codes are provided under the "BERT4Rec" path, where you can run "Bert4Rec.py" to run original BERT4Rec model, and use "Bert4RecHealth.py" to run its version enhanced by our BERT4Rec. The processed data of three datasets is located under the path "BERTHealth".