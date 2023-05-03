Download Link: https://assignmentchef.com/product/solved-cs_1c-homework-12-templated-queue
<br>
A queue is a first-in-first-out data-storage technique (like a line at a bank teller’s window). If one puts in 1, 2, and 3, one gets back 1, 2, and 3. (Remember that a stack is a last-in-first-out datastorage technique.  If one puts in 1, 2, 3, one gets back 3, 2, 1.)

Implement an array based queue (i.e. elements are stored internally in a dynamic array). A stack needs only needs to keep track of one index for an array. A queue must keep track of two indices for an array. One index keeps track of the tail of the queue where new items are added.  The other index keeps track of the head of the queue where old items are removed.

Develop and test the copy constructor and overloaded copy assignment operator.

Develop and test the following methods:

Main queue operations:

<ul>

 <li>enqueue(object): inserts an element at the end of the queue</li>

 <li>object dequeue(): removes and returns the element at the front of the queue</li>

 <li>object front(): returns the element at the front without removing it</li>

 <li>integer size(): returns the number of elements stored</li>

 <li>boolean isEmpty(): indicates whether no elements are stored</li>

 <li>boolean isFull(): indicates whether queue is full</li>

</ul>

Write a class template for a queue class. Define several queues of different data types (int, double, string) and insert and remove data from them. Write a member function to print the queues. Use this function to verify the inserts and deletes.

Perform six additions, four deletions, five additions, three deletions. Print the queue after each operation (there should be about 25 output statements per data type).

Test your program by

<ol>

 <li>Adding to a full queue and removing from an empty queue</li>

 <li>Testing the isEmpty() and IsFull() methods for both the pass and fail conditions</li>

 <li>Testing the front() method</li>

</ol>

Run valgrind to check for memory leaks

Extra Credit [+10 pts]

Implement a node based queue class (suggested name linkedQueue). This time queue elements are stored internally as a singly linked list of nodes. Perform all addition &amp; deletion operations, tests as outlined above using linkedQueue. Run

valgrind to check for memory leaks.

Use the command script to capture your interaction compiling and running the program, including all operations, as shown below:

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="4e2d3d7f2d0e2d3d7f2d6318273c3a3b2f220c2136">[email protected]</a> ~/cs1c/hw/12 $ script hw12.scr Script started, file is hw12.scr <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="5d3e2e6c3e1d3e2e6c3e700b342f29283c311f3225">[email protected]</a> ~/cs1c/hw/12 $ date

…

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="8eedfdbfedceedfdbfeda3d8e7fcfafbefe2cce1f6">[email protected]</a> ~/cs1c/hw/12 $ ls -l

…

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="107363217350736321733d4679626465717c527f68">[email protected]</a> ~/cs1c/hw/12 $ make all

…

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="caa9b9fba98aa9b9fba9e79ca3b8bebfaba688a5b2">[email protected]</a> ~/cs1c/hw/12 $ ls -l

…

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="7516064416351606441658231c0701001419371a0d">[email protected]</a> ~/cs1c/hw/12 $ ./hw12




… // print queue output after each addition, deletion operation above

… // print output from queue tests 1 thru 3 above




<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="0566763466456676346628536c7771706469476a7d">[email protected]</a> ~/cs1c/hw/12 $ exit Script done, file is hw12.scr

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="fc9f8fcd9fbc9f8fcd9fd1aa958e88899d90be9384">[email protected]</a> ~/cs1c/hw/12 $ make tar