# ecse420-assignment-3-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/ecse420-assignment-3-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131417&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECSE420  Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Submission instructions: Students are to work in groups of two on the assignment.

Each group should submit a pdf file that contains the following information: students’ names, students’ IDs, instructions on how to run each file and the associated question solved. Students are also expected to submit a .zip file containing their source code. This code must compile and run without error. The code must be well formatted, commented, and follow the Google Java Style Guide. For more information, see the ECSE420AssignmentSubmissionInstructions.pdf in the Assignment section on myCourses.

Questions

The following benchmark is designed to measure the average time for reading array A containing L elements from memory, when the array elements are s words apart:

for stride s from 4 Bytes (1 word) to L/2 by 2x (s = 1, 2, 4, …, L/2) time the following loop (repeat many times and average) for i from 0 to L-1

load A[i*(s)] from memory (4 Bytes)

So, the benchmark reads L words from memory into cache, where L is a constant; however, these L words are not consecutive memory locations (they are “s” words apart).

The results obtained from the benchmark are shown in Fig.1:

Figure1. Average time for reading each array element.

Assuming only one level of cache exists, the cache line size is 4 words, and a single processor is running the benchmark, answer the following questions:

1.1 In Fig.1, when the total number of elements L of the array is smaller than L’, the average time per access remains constant. What does the value of L’ represent? What does time t0 show?

1.2 When L is larger than L’, what does time t1 indicate in Fig.1?

1.3 For each part of the graph (i.e., parts 1, 2 and 3), justify its behaviour.

1.4 We know a phenomenon called false sharing could cause unnecessary invalidations in ALock (Anderson Lock), and one way to avoid false sharing is to pad array elements so that

1/2

distinct elements are mapped to distinct cache lines. Considering the results from Fig.1, how could the padding technique used in ALock degrade the overall performance of the lock?

2.1. Provide the code for the contains() method missing from the fine-grained synchronization (hand-over-hand locking) algorithm described in chapter 9.

2.2. Write a test to verify the contains() method and explain why your implementation is correct.

3.1. Design a bounded lock-based queue implementation using an array instead of a linked list. Allow parallelism by using two separate locks for the head and the tail.

3.2. Try to transform your algorithm to be lock-free. Where do you run into difficulty?

4.2. Give an efficient and highly parallel multithreaded algorithm for multiplying an n × n matrix A by a length-n vector x that achieves work Θ(n2) and critical path Θ(log n).

[Hint: If you use a cached thread pool with the Future interface, to achieve the Θ(log n) critical path, you can follow the algorithm for matrix multiplication in Chapter 16. Otherwise, depending on how you divide-up the problem, you could obtain a critical path different than Θ(log n). This is acceptable, just be sure to show your work and justify in your report the critical path of your implementation.]

4.3. Write a test program that measures the execution time for multiplying a 4,000 by 4,000 matrix with a corresponding 4000 wide vector using the parallel method and sequential method, respectively. Discuss the execution time of the two methods and compute the speedup. Be sure to indicate how many threads are being used.

4.4. Analyze and discuss the work and critical-path length of your implementation and give the parallelism.

2/2
