# cse232-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CSE232 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cse232-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127086&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE232 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
Note: This is a lengthy assignment. If you do not start by tomorrow you will not be able to finish it on time.

Warm-up

1. Watch this video to have a conceptual understanding of I/O multiplexing techniques such as select, poll, and epoll calls in Linux. This was also done in Tutorial 4.

2. Understand traditional, synchronous TCP socket programming from Tutorial 2.

4. Understand how to set up your system for TCP client/server experiments.

5. Please go through the FAQ before starting the assignment.

The objective of this assignment is to analyze the performance of synchronous and asynchronous TCP servers. Write the TCP server socket programs in C language only.

TCP client:

We have provided the concurrent TCP client program here, and its usage is explained in the README file.

The assignment comprises the following tasks.

1. Write the following TCP server programs:

a. Concurrent server program with multiple processes (using fork system call) [3]

b. Concurrent server program with multiple threads (using pthreads) [3]

c. Non-blocking server programs that implement I/O multiplexing using

i. select() system call [5]

ii. poll() system call [5]

iii. epoll API [5]

All non-blocking designs must support 4000 concurrent connections (i.e., listener file descriptors).

2. Server function: The server program (all designs in (1)), after accepting the incoming request, does the following. [points included in (1)]

a. Read the payload and cast it to a 64-bit unsigned integer, n.

b. Write a function, fact(n), to compute the factorial of the “n”; if n&gt;20, then calculate the factorial of 20.

c. Send the factorial result as the response message back to the client.

3. For each server program in (1), perform separate experiments with number of concurrent client connections equal to 500, 1000, and 3000. Each connection generates 50 requests. For each combination of &lt;server_prog_type&gt;

&lt;num_concurrent_clients&gt;, do the following.

a. Data collection: You must capture all the packets communicated between the client and the server on the server’s interface using a tool such as tcpdump or wireshark. [2]

b. Write python scripts that take the pcap file generated in (a), and computing the following metrics for each server experiment. Show your observations in a plot.

i. Average throughput for each TCP flow (in bits per second) [2.5]

ii. Average latency for each TCP flow (in milliseconds) [2.5]

c. Observe the following metrics. Show your observations in a table and analyze/justify it.

i. Server process’s CPU utilization (use “top” or “htop” command) [2.5]

ii. Server process’s memory utilization (use “time -v” command) [2.5] Note:

Do not use any print statements (while sending/processing requests) when you are observing the metrics. Such I/O operations will slow down the process.

———————
