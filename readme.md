
# This code is the source code implementation for the paper "Publication of Social Network Data based on Node Differential Privacy"

  
  
  


# Experimental Environment

  

```

- networkx==2.6.3

- calmsize==0.1.3

- h5py==3.8.0

—  pandas==1.3.5

- numpy==1.21.5

- scikit-learn==1.2.2

- sklearn==0.0.post1

- matplotlib.pyplot==3.5.2

- scipy.stats==1.7.3


```

 

## Python Files

- **addNoise.py**:
This code aims to add differential privacy noise to a network dataset and analyze the difference between the data before and after adding the noise. This approach can be used to protect privacy while preserving the usefulness of the data.

- **binGroupingDensityCopy.py**:
The main purpose of this code is to determine the clustering centers of a network dataset using a density-based clustering algorithm. These clustering centers can be used for subsequent data analysis and modeling, such as identifying important nodes or community structures. The entire process reflects the basic ideas of data mining and network analysis.

- **gragh.py**:
This code is primarily used for analyzing network data, calculating the strength characteristics of nodes, and visualizing the distribution of node strength in the form of a histogram.

- **project.py**:
This code implements a data preprocessing method based on node degree and edge weight, which can be used for network data analysis and modeling.



## Update log

 

- {24.06.13} Uploaded overall framework code and readme file

