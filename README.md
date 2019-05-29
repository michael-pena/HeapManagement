# Heap Management


This project code written in malloc.c to implment best fit, worst fit, next fit, and first fit. This malloc.c file also:

<ul style="list-style-type:disc;">
  <li>splits blocks</li>
  <li>grows the heap</li>
  <li>coalesces free blocks</li>
  <li>callocs</li>
  <li>reallocs</li>
</ul>  

<h2>To Run</h2>
<code>make</code> <br>
<code>env LD_PRELOAD=lib/libmalloc-ff.so tests/test1<code> <br>

To run the other heap management schemes replace libmalloc-ff.so with the appropriate
library:

Best-Fit: libmalloc-bf.so
First-Fit: libmalloc-ff.so
Next-Fit: libmalloc-nf.so
Worst-Fit: libmalloc-wf.so
