### **FOR Networking_hw**
	Run Networking_hw.gns3 file, then start all devices and run:
	 1. For PC1 : load pc1.config
	 2. For PC2 : load pc2.config
	 3. For PC3 : load pc3.config
	Routers will run their startup configs on start.
	After this configurations you should ping any endpoint 

### **FOR Sonic_hw**
	Run Networking_hw.gns3 file, then start all devices and run:
	 1. For Sonic1 : sudo config bgp startup all
	 2. For Sonic2 : sudo config bgp startup all
	This changes applied because of "sudo config bgp shutdown all" running before and now, for this routers bgp shutdown by default. 
	After this configurations you should ping any endpoint 
