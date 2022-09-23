# graph-data
This repository hosts preprocessed versions of popular datasets often used for GNN evaluation.

## :page_facing_up: Format
Each dataset contains node features in a comma-separated csv file *[dataset name].feats* of the following format:

| Node name | Feature1 | Feature2 | ... | Class | 
| --------- | -------- | -------- | --- | ----- |
| node1     | 0.5      | 0.1      | ... | label0|
| node2     | 0.3      | 1.0      | ... | label2|
| node3     | 0.7      | 0.6      | ... | label1|

There is also an edge list organized into a comma-separated csv file *[dataset name].edges* of the following format:
| From | To   |
| ---- | ---- |
| node1| node2|
| node2| node3|

For ease of loading, files do not comprise column names.

## :gem: Citations
If you use these datasets in any derivative works, do not forget to cite the original publications.
For the current datasets, all original publication can be found in the namesake links in: 
https://linqs.org/datasets/
