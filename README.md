# protein_flexibility
CS229 Final Project: Predicting per-residue protein flexibility using sequence- and structure-based models

Data-processing and model development/training/testing was conducted in Jupyter Notebooks. Notebooks were run either locally or on Google Colab.
- dataset_generation: takes in the flexibility dataset from Wankowicz et al., aligns structures with PDBs, extracts and cleans data of interest
- dataset_analysis: plots distributions across the constructed dataset
- graphein: uses the Graphein.ai package to generate graphical representations of all protein structures, and extract various input features
- run_models: runs all machine learning models benchmarked here (linear regression, random forest, MLP, several GCN variants, EGNN)
- depth_and_input_analyses: conducts analyses of how different random forest depths impact performanace, and of how diffferent input featurizations influence the performance of both random forests and a GCN
