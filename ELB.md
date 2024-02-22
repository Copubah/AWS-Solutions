# Elastic Load Balancing
- Elastic load balancing(ELB),automatically distributes incoming application traffic across multiple Amazon EC2 instances in the cloud in one or more Availabilty Zones 

## Types of ELBs
1. Application load balancer;best suited for routing HTTP/HTTPS traffic and provides advanced routing features
2. Network load balancer;ideal for handling TCP/UDP traffic,suitable for gaming,IOT and other heavy workloads
3. Classic load balancer;legacy load balancer that distributes traffic accross EC2 instances but with fewer features as the above two.


## ELB Diagram


![Architecture Diagram](https://miro.medium.com/v2/resize:fit:720/format:webp/1*vUG06AzpKmeEr7fyMZddsw.png).




## ELB Tips
1. Keep it simple especially when you dont have complex load balancing needs like application specific routing of requests
2. If your architecture is so simple,lets say one server only set up a load balancer anyway as you will get more flexibility especially when scaling as you wont have to change any DNS settings 
3. Scaling in most circumstances is not instant and if you are expecting a hike in traffic you can do a dry run or contact Amazon to have them 'pre-warm' the balancer