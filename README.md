# ENGO 500 Group 3

## Executive Summary

This project is based on creating an asset management web-app that integrates with OS and end-user services across various devices to display spatially-enabled information.

Many companies have assets that are dispersed around across large geographic areas. When these assets fail, maintenance crews are required to perform repairs efficiently to reduce downtime.
- travel time and fuel causes expense --> want to reduce
- analytics of machine lifespan can help assess when maintenance is needed
-
 We will create an asset management system for large IoT sensor networks. This system will provide a solution to two subproblems: asset data visualization and maintenance routing.
 To address the first subproblem, we will provide a web based interface for data analytics and visualization.  This system will also provide maintenance crews with a tool to optimize their route between machinery locations. Our algorithm will consider the economic priority of the machinery.  


To run our web-app, we will simulate sensor data for large IoT networks that monitor the status of machinery.  simulating machinery failure requiring maintenance and scheduling, and routing teams of maintenance workers to most efficiently perform repair.



This includes: the health of systems, prioritizing systems' up-time by some heuristic, providing efficient routing for members of a maintenance team, and allowing additional data visualization of the systems being monitored sever time (including tabs on historic data). The sensor data will be simulated for large IoT networks that monitor machinery, simulating machinery failure requiring maintenance and scheduling, and routing teams of maintenance workers to most efficiently perform repair. building a web-based front end for managing the system & history + DAV for the machinery stats + another view for the maintenance workers to route them... and possible integration with other rando shit (alexa?)

may be simulated, or find freely available data for this.   

Looks like we're going to be simulating sensor data for massive IoT networks (thousands of sensors) that monitor machinery, and then simulating machinery failure requiring maintenance and scheduling/ routing teams of maintenance workers to most efficiently perform repairs.. building a web-based front end for managing the system & history + DAV for the machinery stats + another view for the maintenance workers to route them... and possible integration with other rando shit (alexa?)

Specific technologies to consider (This shouldn't be part of the exec summary)
- vector map tiles for caching (must find efficient way to load large datasets to web-app)
(Basically we need to create a web-based system capable of serving the data efficiently, and to perform DAV, and on the front end to display the data nice & pretty)
