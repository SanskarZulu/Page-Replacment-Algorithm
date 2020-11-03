# Page Replacement Algorithm: 
A page fault happens when a running program accesses a memory page that is mapped into the virtual address space, but not loaded in physical memory.

Since actual physical memory is much smaller than virtual memory, page faults happen. In case of page fault, Operating System might have to replace one of the existing pages with the newly needed page. Different page replacement algorithms suggest different ways to decide which page to replace. The target for all algorithms is to reduce the number of page faults.
1. FIFO.
2. Optimal Page Replacement Algo.
3. Least Recently Used.

/*
Output of Page Replacement Algorithm:
		OS Lab Assignment: Page Replacement Algorithm
			By Sanskar Sharma 090
			   PRN: 0120180381
	Choose the Page Replacement algorithm.
		1. FIFO
		2. Optimal Page Replacement.
		3. Least Recently Used
		4. EXIT
		Enter your choice: 1
			Enter the number of reference & frame slots (separated by spaces): 7 3
			Enter the page reference in sequence (separated by spaces): 
			  1 3 0 3 5 6 3
	Page Faults : 6
	Hits        : 1
		OS Lab Assignment: Page Replacement Algorithm
			By Sanskar Sharma 090
			   PRN: 0120180381
	Choose the Page Replacement algorithm.
		1. FIFO
		2. Optimal Page Replacement.
		3. Least Recently Used
		4. EXIT
		Enter your choice: 2
			Enter the number of reference & frame slots (separated by spaces): 14 4
			Enter the page reference in sequence (separated by spaces): 
			  7 0 1 2 0 3 0 4 2 3 0 3 2 3
	Page Faults : 6
	Hits        : 8
		OS Lab Assignment: Page Replacement Algorithm
			By Sanskar Sharma 090
			   PRN: 0120180381
	Choose the Page Replacement algorithm.
		1. FIFO
		2. Optimal Page Replacement.
		3. Least Recently Used
		4. EXIT
		Enter your choice: 3
			Enter the number of reference & frame slots (separated by spaces): 12 4
			Enter the page reference in sequence (separated by spaces): 
			  1 2 3 4 5 1 3 1 6 3 2 3
	Page Faults : 8
	Hits        : 4
		OS Lab Assignment: Page Replacement Algorithm
			By Sanskar Sharma 090
			   PRN: 0120180381
	Choose the Page Replacement algorithm.
		1. FIFO
		2. Optimal Page Replacement.
		3. Least Recently Used
		4. EXIT
		Enter your choice: 4
...Program finished with exit code 0                                                                                                            
Press ENTER to exit console. 
 
*/
