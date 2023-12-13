# Memory Allocation Simulation Report

### MemoryBlock Struct

```c
struct MemoryBlock {
    int memory[MAX_DIVS];
    bool free[MAX_DIVS];
    int divs;
    int totalJobs;
    int totalMemory;
    int totalHoles;
    int totalEvictions;
};
```

This struct represents the state of the memory system. It includes information such as memory block sizes, their availability (`free`), the number of divisions (`divs`), total jobs, total memory, total holes, and total evictions.

### Simulation Functions

#### `runSimulation`

```c
void runSimulation(struct MemoryBlock *m)
```

This function is responsible for running the simulation for a specified number of time steps (`SIMULATION_STEPS`). It generates new jobs, releases memory when jobs terminate, and calls the appropriate memory allocation function based on the chosen policy.

#### `printSummary`

```c
void printSummary(struct MemoryBlock *m)
```

This function prints a summary of the simulation results, including average fragmentation, average size of a hole, average number of holes examined, highest and lowest fragmentation, average number of jobs in memory, highest and lowest number of jobs in memory, average size of a job, average number of holes, highest and lowest number of holes recorded, largest number of partitions created in a row, and the largest number of evictions required.

### Memory Allocation Policies

#### `firstFit`, `bestFit`, `worstFit`

These functions implement different memory allocation policies - First Fit, Best Fit, and Worst Fit. They search for a suitable memory block based on the policy and update the memory state accordingly.

### User Interaction Functions

#### `welcomeMessage`, `processInput`, `memoryInput`, `choice`

These functions handle user interactions, such as welcoming the user, processing input, allowing the user to input memory data, and choosing the memory allocation algorithm.

### Main Function

```c
int main()
```

The `main` function initializes the `MemoryBlock` struct, welcomes the user, runs the simulation, and prints the simulation summary.


---

** The code which I wrote works fine for the 3 policies ( best fit, worst fit, first fit ) it shows clearly but coming to the 11 metrics sometimes show the results and sometimes it doesnot. 

** CHATGPT HAS BEEN USED TO OVERCOME THE PROBLEM BUT IT DOESN'T WORK. I HAVE ATTACHED BOTH THE CODES. 
