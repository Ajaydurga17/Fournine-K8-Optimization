# Fournine-K8-Optimization
Kubernetes Deployment Optimization

This project focuses on optimizing a Kubernetes Deployment named "mischievous-deployment" that deploys an nginx container across three replicas. The provided manifest file incorporates a balanced approach to memory allocation, aiming for optimal resource utilization and adaptability to varying workloads.

Key Changes Made:
Memory Allocation Adjustment:
requests memory set to "60Mi" for a balanced baseline.
limits memory set to "130Mi" for flexibility during workload spikes.


Why These Changes:
Optimal Resource Utilization: Adjusted memory values for optimal resource usage without over-allocating.
Flexibility for Workload Variation: Chosen values strike a balance for both regular and spike workloads.
Avoiding Resource Underutilization: Preventing both too conservative limits and unnecessary resource allocation.

Rationale:
Aiming for a balanced approach between conservative and liberal resource allocation.
Ensuring a reasonable baseline memory for regular operations (requests at "60Mi").
Providing flexibility for occasional spikes in resource demands (limits at "130Mi").





How It Can Be Helpful:
Optimal Resource Utilization
Adaptability to Workload Changes
Performance Optimization


