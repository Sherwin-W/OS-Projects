# Projects Involving OS Concepts

## Producer_Consumer
<ul>
  <li>Uses kernel-space semaphores to solve the classic producer-consumer problem</li>
  <li>Producer adds all processes to a shared buffer</li>
  <li>Consumer removes the processes from buffer and collects the elapsed time</li>
  <li>Video demos one producere with multiple consumers</li>
</ul>

## Memory_Manager
<ul>
  <li>Implements kernel module to walk the page tables of a process and find pages present in physical memory</li>
  <li>Access five level table: PGD, P4D, PUD, PMD, PTE</li>
  <li>Measures working set size, resident set size, and swap size</li>
</ul>
