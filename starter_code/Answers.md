1. How many Minor GCs Occurred?

  2 GC Pause Young's were found within the log file. There are 2 minor GCs within the gc.log

2. How many Major/Full GCs Occured?

  0. The app ran without causing too massive of a problem with its memory. Otherwise, there would need to be a full cleanup done.

3. What was the longest GC pause time?

   3.902ms. Found within the second Pause young of the file. This was the length of time the application code had to pause to process the allocation.

|GC Type|Total GC Events|Longest Pause|Throughput|
|-------|---------------|-------------|----------|
|Serial| 1 | 19.477ms | 99.71%|
|G1GC| 4 | 1.600ms | 99.94%|
|ZGC| 4 | 0.046ms | 99.996%|
