This playbook executes the following tasks

1.) Add BeeGFS 7.0 client repo for either RHEL 6 or 7
2.) Install required OS packages for BeeGFS client
3.) Install the BeeGFS packages
4.) Configure IP address of management service
5.) Enable quota tracking in config file
6.) Enable extended file attributes and ACLs
7.) Set the BeeGFS mount point
8.) Apply network connection filter for IB or ETH connected clients
9.) Adjust client settings based on network connection fabric type
10.) Set client autobuild parameters to support RDMA
11.) Start and enable beegfs-helperd
12.) Start and enable beegfs-client and mount filesystem
