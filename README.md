# sparql-query-exec-prediction-model

Estamos disponibilizando acá los notebooks utilizandos para nuestro paper **A Neural Networks Approach to SPARQL QueryPerformance Prediction**

Los notebooks de los experimentos finales son:
 - project-lastnewdata_runall.ipynb
 - project-lastlegacy_runall.ipynb
 - **project-lastnewdata_newcolumns_runall.ipynb** //Include the last features used and results in DBPedia query logs form LSQ.

In the dataclei folder is the data to use:
- algebra_features.txt
- vectors_medoids.csv
- datasetlsq_output_rlearningtfeat.csv

It can be processed with the notebook or load directly the x_*. Csv files. Each file include the time column  which is the target to predict.
