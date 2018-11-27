# Mongosfs-nfs

First we need to install nfs server on kubernetes master and mount the shared folder with worker nodes.
Here the link: https://wiki.onap.org/pages/viewpage.action?pageId=16010229

Next create the PV and PVCs for statefulsets.

After that, Create Mongodb stateful set

Finally, Configure the ReplicaSet amoung the Mongodb pods.


