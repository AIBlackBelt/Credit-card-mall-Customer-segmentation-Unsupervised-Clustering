
This work concerns applying two unsupervised learning algorithms on a set of customer. The aim was to detect potential segment of people to target while conducting marketing activities

We used two datasets :
On top of Exploratory data analysis, clustering algorithms has been applied for both datasets
Mall customer dataset 
I applied OPTICS clustering (Density based clustering) on this data. The algorithm has been applied on every subset of two features in order to discover common patterns  each of these subsets.

![Alt text](screenshots/customer_segment.png?raw=true "Title")
![Alt text](screenshots/customer_segment2.png?raw=true "Title")
![Alt text](screenshots/customer_segment3.png?raw=true "Title")

Credit card customer dataset
I applied Spectral Cluster (connectivity based clustering) on this data.The algorithm has been applied on every subset of two features in order to discover common patterns  each of these subsets.

![Alt text](screenshots/cc_customer_segment1.png?raw=true "Title")
![Alt text](screenshots/cc_customer_segment2.png?raw=true "Title")
![Alt text](screenshots/cc_customer_segment3.png?raw=true "Title")

for more interpretations, visit the notebook either in this repo or kaggle :

https://www.kaggle.com/code/majdikarim/spectral-clustering
https://www.kaggle.com/code/majdikarim/customer-segmentation-using-optics-algorithm
