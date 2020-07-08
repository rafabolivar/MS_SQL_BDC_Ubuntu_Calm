# MS_SQL_BDC_Ubuntu_Calm

This Nutanix Calm blueprint deploys a k8s cluster using an Ubuntu Cloud Image, and installs Microsoft SQL Server Big Data Clusters, following [Microsoft's guidelines](https://github.com/microsoft/sql-server-samples/tree/master/samples/features/sql-big-data-cluster/deployment/kubeadm/ubuntu).

Once deployed, you can find your kubeconfig file on *http://<master_server_ip>/joincluster*

The name of the cluster deployed is the default one: **mssql-cluster**

If you prefer not to install azdata on your computer, you can use Calm to connect to the Master Server console and you'll find it there.
