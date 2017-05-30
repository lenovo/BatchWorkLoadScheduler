# BatchWorkLoadScheduler
An implementation of Batch Virtual Machine Workload Scheduler using Genetic Algorithm, Least Loaded, and Most Loaded 

This work was presented at Boston OpenStack Summit 2017

flavors  -- input file with VM flavors
servers  -- input file with compute server specs
ga.py    -- implementation of Genetic Algorithm based scheduling
ll.py    -- implementation of Least-Loaded heuristic
ml.py    -- implementation of Most-Loaded heuristic
wl.py    -- Generate workload

Test run:
1. edit the workload profile at wl.py, then generate workload
     $ python wl.py 
2. run different scheduling algorithm and then compare the result
     $ python ga.py
     $ python ll.py
     $ python ml.py

