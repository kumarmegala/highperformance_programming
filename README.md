# highperformance_programming
highperformance_programming

# data strcture
  pick one for those O(1)

# 

# kernal bypass
https://blog.cloudflare.com/kernel-bypass/
https://www.kernel.org/doc/Documentation/networking/packet_mmap.txt
https://sites.google.com/site/packetmmap/
 
# zero-copy

# lock-free 
## algorithms
General Approach to Lock-Free
Algorithms
● Designing generalized lock-free algorithms is hard
● Design lock-free data structures instead
– Buffer, list, stack, queue, map, deque, snapshot
● Often implemented in terms of simpler primitives
– e.g. ‘Multi-word Compare and Set’ (MCAS, CAS2, CASN)
– Cannot implement lock-free algorithms in terms of lockbased
data structures
– What’s going to be one of the scarier underlying lockfree,
thread-safe primitive?
● Hint: you usually need this for lists and stacks…

   
#https://www.solarflare.com/ultra-low-latency
