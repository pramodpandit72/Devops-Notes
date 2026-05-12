## Scaling - adjusting resources based on demand

Example:-
More users → increase resources
Less users → decrease resources

## Two Types of Scaling
# Horizontal Scaling (Scale Out/In) - Increase number of instances (pods/servers)
# Vertical Scaling (Scale Up/Down) - Increase power of a single machine
Example: -
RAM: 4GB → 16GB
CPU: 2 cores → 8 cores

Advantages
Simple to implement
No need to manage multiple instances



## Horizontal vs Vertical (VERY IMPORTANT TABLE)

| Feature            | Horizontal Scaling     | Vertical Scaling              |
| ------------------ | ---------------------- | ----------------------------- |
| Meaning            | Add more machines/pods | Increase power of one machine |
| Example            | 1 pod → 5 pods         | 2 CPU → 8 CPU                 |
| Availability       | High                   | Low                           |
| Complexity         | Higher                 | Lower                         |
| Limit              | No limit (almost)      | Hardware limit                |
| Kubernetes Support | HPA (common)           | Limited                       |


Horizontal = scale out (pods increase)
Vertical = scale up (resources increase)
HPA = automatic horizontal scaling
VPA = vertical scaling (less used)
Horizontal scaling is preferred in Kubernetes