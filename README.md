# CPU-Scheduling-Algorithms-Simulator
 A simulator for various CPU Scheduling Algorithms. Provide real-time visualizations for Gantt charts and process execution
 1. Project Overview  
 Goals:  
    -> Develop a simulator for visualizing and comparing different CPU scheduling algorithms.  
    -> Help users understand the behavior of scheduling policies with real-time Gantt charts.  
    -> Compute performance metrics like Average Waiting Time (AWT), Turnaround Time (TAT), and CPU Utilization.  
 Expected Outcomes:  
     -> A working simulator supporting FCFS, SJF (Preemptive & Non-Preemptive), Round Robin, and Priority Scheduling.  
     -> Graphical visualization of scheduling (e.g., Gantt Chart).  
     -> Performance evaluation with key metrics.  
     User-friendly interface for input and real-time execution.  
 Scope:  
    -> Input: Process details (arrival time, burst time, priority, quantum time for RR).  
    -> Output: Gantt chart, per-process details, and performance metrics.  
    -> User Interaction: GUI for adding processes and selecting algorithms.  
 2. Module-Wise Breakdown  
    # Three main modules:  
 
   1. Input & Process Management Module  
      -> Handles user input of process attributes.  
      -> Stores process details dynamically.  
      -> Implements various scheduling algorithms.  
   2. Scheduling & Computation Module  
      -> Implements different CPU scheduling algorithms.  
      -> Calculates key metrics (Waiting Time, Turnaround Time, etc.).  
      -> Generates Gantt Chart data.  
   3. GUI & Visualization Module  
      -> Uses Tkinter/PyQt for user interaction.  
      -> Displays real-time Gantt chart using Matplotlib.  
      -> Shows tabular process statistics.  
 3. Functionalities  
   1. Input & Process Management  
     ✅ Features:  
      -> Allow users to enter process details (Arrival Time, Burst Time, Priority, etc.).  
      -> Modify/Delete process entries dynamically.  
      -> Load predefined test cases.  
 2. Scheduling & Computation   
     ✅ Features:  
 
   Implements:  
    -> FCFS (First Come, First Serve)   
    -> SJF (Shortest Job First - Preemptive & Non-Preemptive)    
    -> Round Robin    
     -> Priority Scheduling  
   Calculates:  
    -> Completion Time (CT)  
    -> Turnaround Time (TAT = CT - AT)  
    -> Waiting Time (WT = TAT - BT)  
    -> CPU Utilization & Throughput  
    -> Generates Gantt chart sequence.
    3. GUI & Visualization    
    ✅ Features:    
 
  -> Real-time Gantt chart visualization.    
 -> Tables for per-process analysis.    
 -> Graphical comparison of scheduling metrics. 
 

 5. Execution Plan    
     Step 1: Setup Development Environment   
         -> Install Python (if using Python) or C++ compiler (if using C++).  
         ->  Install required libraries (Tkinter, Matplotlib for Python).  
     Step 2: Implement Scheduling Algorithms  
         -> Start with FCFS (simplest).  
         ->  Implement SJF, Priority, and Round Robin.  
         ->  Test each algorithm with sample inputs.  
     Step 3: Build the GUI  
         ->  Create a simple process input interface.  
         ->  Add buttons for algorithm selection & execution.  
     Step 4: Implement Gantt Chart & Performance Metrics  
         -> Use Matplotlib (Python) or SFML/SDL (C++) to visualize scheduling.  
         -> Display average waiting time, turnaround time, and CPU utilization.  
     Step 5: Optimize & Finalize  
         ->  Add error handling for invalid inputs.  
         ->  Improve UI for better usability.  
         ->  Optimize algorithm execution.      
