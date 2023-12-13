# Memory Allocation Simulation Report

## Introduction

The purpose of this simulation was to explore and analyze the effects of different memory allocation policies on a hypothetical machine with variable-size partitions. The simulation considered three size distribution profiles (Any-sized jobs, Small jobs, Large jobs) and three replacement policies (Best fit, Worst fit, First fit).

## Experimental Conditions

### Size Distribution Profiles

1. **Any-sized jobs**
   - Each job can be of any random size between 1 and 1024.

2. **Small jobs**
   - Each job can be of any random size between 1 and 100.

3. **Large jobs**
   - Each job can be of any random size between 500 and 1000.

### Replacement Policies

1. **Best fit (Policy 1)**
2. **Worst fit (Policy 2)**
3. **First fit (Policy 3)**

## Simulation Results

### Overview

The simulation ran for 2000 time steps, allowing for a thorough exploration of memory allocation behavior. Each scenario underwent 1000 initial time steps to reach a state of equilibrium before recording measurements.

### Summary Metrics

1. **Average Fragmentation**
   - The average fraction of total memory occupied by holes.

2. **Average Size of a Hole**
   - The average size of holes in memory.

3. **Average Number of Holes Examined**
   - The average number of holes examined to satisfy a single new partition request.

4. **Highest and Lowest Fragmentation**
   - The highest and lowest fragmentation measured during the simulation.

5. **Average Number of Jobs in Memory**
   - The average number of jobs present in memory.

6. **Highest and Lowest Number of Jobs in Memory**
   - The highest and lowest number of jobs recorded in memory.

7. **Average Size of a Job**
   - The average size of jobs in memory.

8. **Average Number of Holes**
   - The average number of holes in memory.

9. **Highest and Lowest Number of Holes Recorded**
   - The highest and lowest number of holes recorded during the simulation.

10. **Largest Number of Partitions Created in a Row**
    - The largest number of partitions created consecutively without any intervening evictions.

11. **Largest Number of Evictions Required**
    - The largest number of evictions required to satisfy a single new partition request.

---
