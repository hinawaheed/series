#OS Project
# series
Project Title:

Comparison Between Multithreading And Multiprocessing 

Instructors:

Miss Nausheen Shoaib and Miss Sumaiyah Zahid 

Section:   D

Group Members:

Obaid Ur Rehman    17k-3848
Hina Waheed           17k-3862
Moosa Hussain        17k-3934


OBJECTIVE:

Our project will mainly focus on the differences between multithreading and multiprocessing. The performance comparison will be observed by the implementation of FOUR different series algorithms :

1)	Fibonacci Series
2)	Trag Series 
3)	 Lazy Caterer Series
4)	Catalan Series

INTRODUCTION:

Comparison will be shown on the basis of speed and input (number of elements in the series). All the above mentioned algorithms have been implemented using multithreading and multiprocessing along with the use of pipes. 

PROGRAMMING PLATFORM USED:

⦁	The programming platform used is C Language
⦁	The operating system that we worked on is Ubuntu.

OBSERVATIONS:

1.	Fibonacci Series

Number of elements in series	Time (in milliseconds) taken by
	Process	Threads
5	0.236	0.564
10	0.239	0.732
15	0.246	0.737
20	0.252	0.745
30	0.264	0.757
40	0.269	0.807
50	0.280	0.911

2.	Trag Series

Number of elements in series	Time (in milliseconds) taken by
	Process	Threads
5	0.244	0.635
10	0.259	0.692
15	0.288	0.715
20	0.300	0.727
30	0.315	0.759
40	0.342	0.782
50	0.354	0.837

3.	Lazy Caterer Series

Number of elements in series	Time (in milliseconds) taken by
	Process	Threads
5	0.247	0.664
10	0.250	0.677
15	0.255	0.695
20	0.268	0.726
30	0.289	0.742
40	0.303	0.799
50	0.321	0.834

4.	Catalan Series

Number of elements in series	Time (in milliseconds) taken by
	Process	Threads
5	0.227	0.563
10	0.239	0.647
15	0.270	0.749
20	0.283	0.809
30	0.312	0.847

CONCLUSION:

From the above observations it can be drawn that multiprocessing is actually faster than multithreading because of the overhead of synchronization of threads in multithreading. 
