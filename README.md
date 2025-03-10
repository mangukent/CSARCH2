# CSARCH2

1. Cache line = 16 words
2. Number of cache blocks = 32 blocks
3. Cache line = 16 words
4. Read policy: non load-through
5. ***Number of memory blocks = user input (but at least 1024 blocks)

Test cases (n is the number of cache blocks):
a.) Sequential sequence: up to 2n cache block. Repeat the sequence four times. Example: 0,1,2,3,...,63 {4x}
b.) Random sequence: containing 4n main memory blocks.
c.) Mid-repeat blocks: Start at block 0, repeat the sequence in the middle two times up to n-1 blocks, after
which continue up to 2n. Then, repeat the sequence four times. Example: if n=8, sequence=0, 1,2,3,4,5,6,7
1,2,3,4,5,6,7 8,9,10,11,12,13,14,15 {4x}

a.) System output:
a. Cache memory snapshot.
i. Option for step-by-step animated tracing or final memory snapshot
ii. Provide a text log of the cache memory trace (regardless of whether it is a step-by-step or
final memory snapshot).
b. Output: 1. memory access count; 2. cache hit count; 3. cache miss count; 4. cache hit rate; 5. cache
miss rate; 6. average memory access time; 7. total memory access time
b.) Detail analysis of the three test cases. It will be submitted as “readme” in your GitHub. Note: Don’t forget
to specify the full specs of your cache simulation system
c.) Video containing the “walkthrough” of your system. Specify the link in the Github readme, or it can be
stored in GitHub.
d.) Note: the source code /executable program (stand-alone) or link to the web-based app as well as the video
and analysis writeup, should all be in GitHub.
e.) Project demo if needed

Cache Memory: 8-way BSA + MRU
