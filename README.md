# Paged-Segmentation

This project implements Paged Segmentation.
Paged Segmentation is a memory management technique that divides a process’s address space into segments and then divides each segment into pages. This allows for a flexible allocation of memory, where each segment can have a different size, and each page can have a different size within a segment.

Refer the Report for more Deatils.

<h3>TO COMPILE</h3>
	
	gcc main.c -o main
	
	
<h3>EXAMPLE USAGE TO RUN</h3>

	./main a.out ref.txt
	#OR
	./main a.out

 You can Change the executable file. 
 If no command line arguments are provided, the code will use the data from ref.txt by default.
