# Data-warehouse-tech-stack
## About the project
Me and my colleagues have joined to create an AI startup that deploys sensors to businesses, collects data from all activities in a business - people’s interaction, traffic flows, smart appliances installed in a company. Our startup helps organisations obtain critical intelligence based on public and private data they collect and organise. 
- A city traffic department wants to collect traffic data using swarm UAVs (drones) from a number of locations in the city and use the data collected for improving traffic flow in the city and for a number of other undisclosed projects. Our startup is responsible for creating a scalable data warehouse that will host the vehicle trajectory data extracted by analysing footage taken by swarm drones and static roadside cameras. 
- The data warehouse should take into account future needs, organise data such that a number of downstream projects query the data efficiently. We should use the Extract Load Transform (ELT) framework using DBT. Unlike the Extract, Transform, Load (ETL), the ELT framework helps analytic engineers in the city traffic department setup transformation workflows on a need basis.  

- ![alt text](https://github.com/Danu-B/Data-warehouse-tech-stack-/blob/main/Screenshoots/flowdiagram%20.png?raw=true) 

## Data
In Downloads – pNEUMA | open-traffic (epfl.ch) you can find a pNEUMA data 
-pNEUMA is an open large-scale dataset of naturalistic trajectories of half a million vehicles that have been collected by a one-of-a-kind experiment by a swarm of drones in the congested downtown area of Athens, Greece. Each file for a single (area, date, time) is 87MB data.  

