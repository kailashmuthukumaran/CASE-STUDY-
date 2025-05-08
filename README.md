# Case Study: Resource Allocation and Cost Optimization in an OpenStack Private Cloud
# Problem 1: Total Compute Capacity
# Given:

5 Compute Nodes

# Each node has:

64 vCPUs

256 GB RAM

2 TB SSD storage

# Q: What is the total available compute capacity in terms of:

Total vCPUs

Total RAM

Total storage

# Step 1: Total vCPUs
Total vCPUs = 5 × 64 = 320 vCPUs

# Step 2: Total RAM
Total RAM = 5 × 256 = 1280 GB or 1.25 TB

# Step 3: Total Storage
Total Storage = 5 × 2 TB = 10 TB

# Answer: 
The infrastructure has 320 vCPUs, 1.25 TB RAM, and 10 TB SSD storage.

# Problem 2: Storage Allocation and VM Capacity
# Given:

Total block storage available: 10 TB = 10,000 GB

Each VM requires: 100 GB block storage

Snapshot overhead: 20% extra

# Q(a): How many VMs can be supported without snapshot overhead?
Number of VMs = 10,000 GB / 100 GB = 100 VMs

# Q(b): How many VMs can be supported with 20% snapshot overhead?
# Each VM now consumes:
100 GB + 20% = 100 × 1.2 = 120 GB

Number of VMs = 10,000 / 120 ≈ 83 VMs (rounded down)

# Answer:

Without snapshot overhead: 100 VMs

With 20% snapshot overhead: 83 VMs
