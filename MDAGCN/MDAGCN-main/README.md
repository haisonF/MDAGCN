# MDA-GCNGS



## Run the MDA-GCNS

1. pip install -r MDA-GKNN_requirements.txt
2. 1_Construct MDP graph.ipynb
3. 2_data preprocessing to model.ipynb
4. Train and test, for example:
   python -m graphsaint.pytorch_version.train_saveys --data_prefix drug_mutation_data/task_Tp__testlabel0_7knn_edge_fold0  --train_config graphsaint/parameters_epoch_1.yml

