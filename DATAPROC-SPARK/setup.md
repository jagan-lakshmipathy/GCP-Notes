# How to setup Dataproc w/ Spark
Before you follow the below steps to check out a dataproc cluster create a storage bucket
1. Go to GCP Navigation Menu (Sidebar)
2. Press Create Bucket (and complete all steps and press Create)

Now, do the following steps to check out the dataproc cluster:
1. Go to GCP Navigation Menu (Sidebar)
2. Find DataProc under BigData
3. Press "Create Cluster" from the top menu
4. You will see 4 tabs
	- Set up cluster
	- Confgure nodes
	- Customize cluster
	- Manage Security
5. Select Set up cluster
	- Populate the cluster name
	- Select the region you prefer
	- Select the cluster type
	- Enable component gateway under 'Components'
	- For jupyter note ( I had to select the optional components)
		- Anaconda
		- Jupyter Notebook

6. I don't have to change anything under Configure Nodes
7. Go to customize cluster section:
	- Browse to the storage you created above
	- I don't have to do any chages elsewhere
8. I dont't have to change anything under Manage Security

Wait for cluster to come up. It took me around 5 mintues for the cluster to come up. 

Once the cluster is up and running, select the cluster name and go Cluster details page and select the Web Interfaces tab and select the jupyter from the component gateway list. 
Walah you will see the Jupiter notebook page. You can create a Jupyter notebook with pyspark kernel now. Enjoy!