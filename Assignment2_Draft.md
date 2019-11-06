## Assignment 2

This is a group project. You are required to pick **at least 1 dataset** and **1 method from each of the three categories** (quantization-based method, locality sensitive hashing method, and proximity-graph based method) and do an experimental study. 

* Dataset: Different group CANNOT work on the same dataset. 
  * First in first got with this [Google Doc (The second sheet: Assignment2)](https://docs.google.com/spreadsheets/d/1S_Vu6uaJo0h5bKMbwEPTopx_sFYBdemSyJoNQUuPTZ0/edit?usp=sharing). Please check duplication when you fill your dataset.
* Method: Different group can work on same method.

Submit a report by doing benchmark experiment with state-of-art methods.

Note that you will present your findings in the last lecture.

## Recommend Method

### Reference Materials 

1. Algorithms: Here are some recommended algorithms. You can choose algorithms other than the following.

* Hnswlib  : https://github.com/nmslib/hnswlib
* FALCONN: https://falconn-lib.org/
* PQ table: https://github.com/matsui528/pqtable
* PQ fast scan: https://github.com/technicolor-research/pq-fast-scan
* QALSH: https://github.com/HuangQiang/QALSH
* E2LSH: https://www.mit.edu/~andoni/LSH/

2. Datasets:  You can use the benchmark datasets that already tested within the paper that constructed the algorithm. **However, you cannot evaluate the same dataset with another group! So please declare your intention ASAP. (Link to [Google Doc (The second sheet: Assignment2)](https://docs.google.com/spreadsheets/d/1S_Vu6uaJo0h5bKMbwEPTopx_sFYBdemSyJoNQUuPTZ0/edit?usp=sharing) that get avoid of duplication)**

## Report 

### Title and team info

Provide a title for your project along with the names of all the
team members.

### Summary (One-page)

A 1-page (maximum) summary about your experiment result.  

### Goals

What are the goals of your project? Please state them with minimal jargon. 

### Brief description of compared methods

### Experiment Detail

Please provide technical details that you build out. 

1. Datasets: a brief description of your test dataset.
2. Algorithm / machine: What language, algorithm or tool did you use? What are the configuration of your machine and what is the compiler and compile option? Any adjustment when you apply it on your dataset?

### Evaluation (The most important section!)

How do you plan to evaluate your result? What metrics will you use? What
are your experimental setup(s)?

The following criteria is required:

1. query time 
2. index time 
3. index size 
4. accuracy 
5. scalability
6. impact of parameters

### Supplementary

Did you face with any technical difficulty when working on this experiment? How did you work it out? Anything you learned from this project?

### Appendix

Materials that are not so important but deserve a presentation in the documents

### Reference

**Be illustrative and concrete: draw plots, talk through**
**experiment result and explain why you got these results.**

