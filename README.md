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

https://www.cs.cmu.edu/~410-s05/lectures/L31_LockFree.pdf
https://pdfs.semanticscholar.org/b3a6/ed040a94cd527bc746fcd7063ac693bf7c1a.pdf

   
#https://www.solarflare.com/ultra-low-latency



https://www.ea.oit.va.gov/EAOIT/docs/Oct_2016_Release_Docs/APM-2-2.pdf

