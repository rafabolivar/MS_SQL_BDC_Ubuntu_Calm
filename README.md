# MS_SQL_BDC_Ubuntu_Calm

This Nutanix Calm blueprint deploys a k8s cluster using an Ubuntu Cloud Image, and installs Microsoft SQL Server Big Data Clusters, following [Microsoft's guidelines](https://github.com/microsoft/sql-server-samples/tree/master/samples/features/sql-big-data-cluster/deployment/kubeadm/ubuntu).

Once deployed, you can find your kubeconfig file on *http://<master_server_ip>/joincluster*

The name of the MS SQL cluster deployed is the default one: **mssql-cluster**

If you prefer not to install azdata on your computer, you can use Calm to connect to the Master Server console and you'll find it there.

There's a significant performance improvement if you use LVM and more vDisks. The Blueprint called *4_MS_SQL_BDC_k8s_Ubuntu_Local_LVM.json* configures a local-storage class, with 4 vdisks.

As usual, the password is: **nutanix/4u**
