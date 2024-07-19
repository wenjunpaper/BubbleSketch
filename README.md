# BubbleSketch

* Bubble Sketch: A High-performance and Memory-efficient Sketch for Finding Top-k Items in Data Streams (ACM CIKM 2024)
* Authors: Lu Cao, Qilong Shi, Yuxi Liu, Hanyue Zheng, Yao Xin, Wenjun Li*, Tong Yang, Yangyang Wang, Yang Xu, Weizhe Zhang, and Mingwei Xu 
* Corresponding e-mail: wenjunli@pku.org.cn

# How to run

Suppose you've already cloned the repository.

You just need:

```
$ make
$ ./BubbleSketch (-d dataset -m memory -k k)
```

**optional** arguments:

- -d: set the path of dataset to run, default dataset is CAIDA "1.dat"
- -m: set the memory size (KB), default memory is 400KB
- -k: set the number of top flows, default **k** is 1000

# Output format

Our program will print the Throughput of insertion, AAE, ARE and Precision of these algorithms on the screen.
