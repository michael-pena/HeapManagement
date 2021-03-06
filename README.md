# Heap Management


Project code is written in C and uses malloc.c to implment best fit, worst fit, next fit, and first fit. This malloc.c file also:

<ul style="list-style-type:disc;">
  <li>splits blocks</li>
  <li>grows the heap</li>
  <li>coalesces free blocks</li>
  <li>callocs</li>
  <li>reallocs</li>
</ul>  

<h2>To Run</h2>
<code>make</code> <br> 
<code>env LD_PRELOAD=lib/libmalloc-ff.so tests/test1</code> <br> <br>

To run the other heap management schemes replace libmalloc-ff.so with the appropriate
library: <br><br>

Best-Fit: libmalloc-bf.so <br>
First-Fit: libmalloc-ff.so <br>
Next-Fit: libmalloc-nf.so <br>
Worst-Fit: libmalloc-wf.so <br>
