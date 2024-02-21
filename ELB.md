# Elastic Load Balancing
- Elastic load balancing(ELB),automatically disributes incoming application traffic across multiple Amazon EC2 instances in the cloud




## ELB Tips
1. Keep it simple especially when you dont have complex load balancing needs like application specific routing of requests
2. If your architecture is so simple,lets say one server only set up a load balancer anyway as you will get more flexibility especially when scaling as you wont have to change any DNS settings 
3. Scaling in most circumstances is not instant and if you are expecting a hike in traffic you can do a dry run or contact Amazon to have them 'pre-warm' the balancer