# ads-508-final
Use SageMaker to create recommendation system for independent games on PlayStation systems

- Data is read in from s3 for exploratory analysis in EDA.ipynb
- Data is prepared and engineered for general modeling in general_data_prep.ipynb
- Random negative samples are generated for each user. The data is then transformed once again into RecordIO format for modeling in factorization_machines_data_prep.ipynb
  - (These are specific steps for Facotrization Machines on SageMaker so they are separated into isolated notebook)
- Model traning and evaluation for SageMaker Factorization Machines in smfm-train.ipynb
- Model traning and evaluation for XGBoost in SageMaker in XGBoost.ipynb
