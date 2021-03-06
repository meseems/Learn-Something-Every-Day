# Scaling Up deployments through ELB, CloudWatch, Auto Scaling
### Elastic Load Balancer
**Elastic Load Balancer** is a managed service that automatically scales based on traffic metrics
- supports routing all HTTP, HTTPS, TCP and SSL traffic 
- balances traffic across availability zones, generally for homogeneous instances
- can be used for health checks on a set of instances
- **internet facing** load balancers receive dns record

### Amazon CloudWatch
Service for monitoring AWS resources and applications in real time

### Auto Scaling
Auto scaling in AWS is composed of three components: 
- **Launch configs** specify a template of EC2 resources to consume when launching an instance, including instance type, AMIU, security groups
- **auto scaling groups (ASG)** consume a launch config to provision a managed set of EC2 instances
- **auto scaling policy** is an optional component that let's administrators define the criterion for creating and destroying instances in the ASG based on workload metrics

