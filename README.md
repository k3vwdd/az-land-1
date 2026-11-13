a my simple azure landing zone used to deploy aks workloads for research purposes.

Tradeoffs:

- single region for now, easier to manage. If we're thinking about DR we can connect another.
- hub and spoke gives me full control.
- one sub for cost reasons, enterprise envs will have multiple subs following ms cloud adoption strategy.
- x Private DNS.
- seperate state per layer - limit blast radius.
- It's a lab, It can grow if needed..
