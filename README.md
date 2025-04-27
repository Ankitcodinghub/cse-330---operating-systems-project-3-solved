# cse-330---operating-systems-project-3-solved
**TO GET THIS SOLUTION VISIT:** [CSE 330 – Operating Systems Project #3 Solved](https://www.ankitcodinghub.com/product/cse-330-operating-systems-project-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;35706&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;6&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (6 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE 330 - Operating Systems Project #3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (6 votes)    </div>
    </div>
<strong>Implementing Semaphores</strong>

Using the threads, you have implemented, implement semaphores. Since the threads are nonpreemptive, you do not need to ensure atomicity of the semaphores (they are already atomic).

Implement the following: (in a file called sem.h)

<ol>
<li><strong>Semaphore data structure: </strong>A value field and a queue of TCBs.</li>
<li><strong>InitSem(semaphore, value):</strong> Initializes the value field with the specified value.</li>
<li><strong>P(semaphore):</strong> The P routine decrements the semaphore, and if the value is less than zero then blocks the process in the queue associated with the semaphore.</li>
<li><strong>V(semaphore):</strong> The V routine increments the semaphore, and if the value is 0 or negative, then takes a PCB out of the semaphore queue and puts it into the run queue. Note: <strong>The V routine also “<em><u>yields</u></em>” to the next runnable process.</strong> //this is important.</li>
<li>Implement a solution to the Producer Consumer Problem with the following settings:</li>
</ol>
<em><u>There are three producers all in infinite while loops each producing 1 item in one loop</u></em><em>. </em>

<em><u>There are three consumers all in infinite while loops each consuming 1 item in one loop</u></em><em>.</em>

<em><u>Every consumer or producer yields at the end of a loop to the next process</u></em><em>. </em>

<em><u>Consider that the buffer size is 6 items.</u></em>

<em><u>Consider that in your ready queue there are three consumers then seven producers then</u></em><em> <u>7 consumers and finally three more producers .</u> </em>

<em><u>Run the code for infinitely long.</u></em>

<em><u>At the end of each loop before yield the consumer should print the following:</u></em><em> <u>if consumer X is consuming an item then print</u></em>

<em><u>“This is consumer X consuming item generated by producer Y”</u></em><em> <u>else print</u></em>

<em><u>“Consumer X is waiting”</u></em>

<em><u>At the end of each loop before yield the producer should print the following:</u></em>

<em><u>if producer X is producing an item then print “This is producing X producing item number Y”</u></em><em> <u>else print</u></em>

<em><u>“Producer X is waiting”</u></em>

<strong>&nbsp;Submission and Grading:</strong>

Your project must consist of 4 files

<ol>
<li>h (uses ucontext.h)</li>
<li>h (includes TCB.h)</li>
<li>h (includes q.h)</li>
<li>h (includes threads.h)</li>
<li>proj-3.c (includes threads.h) – must contain your name(s) in comments @ beginning (make sure the compile command, “gcc proj-3.c” does the correct compilation).</li>
</ol>
All 5 files are to be ZIPPED into one zip or gzip file and uploaded in Canvas. The name of this file should reflect the name of the student (abbreviated, do not make it too long).

<strong>Note: Grading is on Ubuntu. It is in your interest to make sure the program compiles and runs in the target test platform.</strong>
