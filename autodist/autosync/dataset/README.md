# Data processing instructions


## Arrange the dataset in the following folder structure:
Data/
|--Model-1/ (e.g., BERT-small)

|----Cluster-1/ (e.g., AWS-4-g4)

|------resource_spec.yaml

|------runtime/

|--------runtime_file_12345 (make sure the ID is the same with the strategy file)

|--------......

|------strategies/

|---------strategy_file_12345

|--------......

|----Cluster 2 (e.g., In-house-10-nodes, dont use ORCA, come up with a beter name)

|----......

|--Model-2

|----......

|--Model-3

|----......

|--Model-4

|--.......


## Write several scripts:
- a script on how to read a (resource_spec, strategy, runtime) tuple using AutoDist APIs.
- an example script on using a subset of the tuples to train a linear model (using your previous code is fine).


## Other notes
- NCF-dense and NCF-sparse are considered as different models; same for BERT-3L, BERT-6L, etc.
- Ask me if you are not sure about a data point.
