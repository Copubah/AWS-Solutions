# Auto Scaling
- A distinct advantage of deploying to cloud is the ability to launch and release servers in response to variable worloads
- Auto Scaling Groups(ASGs) are used to control the number of instances in a service therefore reducing the manual effort to provision or deprovision EC2 instances

## Tips
1. Have clear Scaling policies such as CPU utilization,memory usage or request latency
2. Set up scaling alarms(use Cloudwatch alarms)when specific thresholds are breached
3. Consider scheduled scaling if your application has predictable traffic patterns
4. Monitor auto scaling activities
5. Intergrate with Infrastructure as code to manage configurations effectively