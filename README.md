# Computer Network Inventory Portfolio Project
I would like to develop a computer network inventory database that keeps track of network devices that are up and operational in a production network. Each device will have list of attributes that are associated to the device listed in a "Devices" table. 

In a production network, devices are located in network closets. Those network closets are identified as either a IDF (Intermediate Distribution Frame), MDF (Main Distribution Frame), or data center. These network closets will be listed in a "Network Closets" table.  

In network closets, there are devices called UPS' (Uninterruptible Power Supplies) that assist with keeping networking equipment up during a building power failure. Network devices connect to UPS’ for redundant power and UPS’ are associated to a specific network closets. UPS’ will be listed in a “UPS” table. 

Network closets are associated to buildings on a campus computer network. These buildings will be listed in a “Buildings” table. 
