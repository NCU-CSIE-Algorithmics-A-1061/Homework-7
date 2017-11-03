# Homework 7

1. Exercises 16.2‐4<br>
Professor Gekko has always dreamed of inline skating across North Dakota. He plans to cross the state on highway U.S. 2, which runs from Grand Forks, on the eastern border with Minnesota, to Williston, near the western border with Montana. The professor can carry two liters of water, and he can skate m miles before running out of water. (Because North Dakota is relatively flat, the professor does not have to worry about drinking water at a greater rate on uphill sections than on flat or downhill sections.) The professor will start in Grand Forks with two full liters of water. His official North Dakota state map shows all the places along U.S. 2 at which he can refill his water and the distances between these locations.<br>
The professor’s goal is to minimize the number of water stops along his route across the state. Give an efficient method by which he can determine which water stops he should make. Prove that your strategy yields an optimal solution, and give its running time.

2. Exercises 16.2-7<br>
Suppose you are given two sets A and B, each containing n positive integers. You can choose to reorder each set however you like. After reordering, let a<sub>i</sub> be the ith element of set A, and let b<sub>i</sub> be the ith element of set B. You then receive a payoff of ![product(a\_i^b\_i)](http://latex.codecogs.com/gif.latex?%5CPi_%7Bi%3D1%7D%5Ena_i%5E%7Bb_i%7D). Give an algorithm that will maximize your payoff. Prove that your algorithm maximizes the payoff, and state its running time.

3. Exercise 16.5-1<br>
Solve the instance of the task-scheduling problem given below.

| task | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|:----:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| deadline | 5 | 4 | 3 | 4 | 2 | 4 | 2 |
| profit | 20 | 60 | 30 | 40 | 10 | 70 | 50 |

4. Exercise 16.5-2<br>
Show how to use property 2 of Lemma 16.12(unit06-演算法.pdf p30) to determine in time O(|S|) whether or not a given set S of tasks is independent.

5. Problem 16-2: Scheduling to minimize average completion time<br>
Suppose you are given a set S = { a<sub>1</sub>, a<sub>2</sub>, ... , a<sub>n</sub> } of tasks, where task a<sub>i</sub> requires p<sub>i</sub> units of processing time to complete, once it has started. You have one computer on which to run these tasks, and the computer can run only one task at a time. Let c<sub>i</sub> be the *completion time* of task a<sub>i</sub>, that is, the time at which task a<sub>i</sub> completes processing. Your goal is to minimize the average completion time, that is, to minimize ![sum(c\_i)](http://latex.codecogs.com/gif.latex?%5CSigma_%7Bi%3D1%7D%5Enc_i). Give an algorithm that schedules the tasks so as to minimize the average completion time. Each task must run non-preemptively, that is, once task a<sub>i</sub> starts, it must run continuously for p<sub>i</sub> units of time. Prove that your algorithm minimizes the average completion time, and state the running time of your algorithm.

6. Suppose you have one machine and a set of n jobs a<sub>1</sub>, a<sub>2</sub>, ... , a<sub>n</sub> to process on the machine. Each job a<sub>j</sub> has a processing time t<sub>j</sub>, the same profit 1, and a deadline d<sub>j</sub>. The machine can process only one job at a time, and job a<sub>j</sub> must run uninterruptedly for t<sub>j</sub> consecutive time units. If job a<sub>j</sub> is completed by its deadline d<sub>j</sub>, you receive a unit profit, but if it is completed after its deadline, you receive a profit of 0. Give an algorithm to find a schedule that obtains the maximum amount of profit. Prove that your algorithm maximizes the profit, and show its running time.

7. Give an efficient algorithm that solves the problem [13054 Hippo Circus](https://uva.onlinejudge.org/external/130/13054.pdf) on UVa Online Judge. Prove the correctness of your algorithm, and analyze the running time of it.
