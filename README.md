# BubbleSketch

BubbleSketch is adaptive to finding Top-k elephant flows. There are also several well-known algorithms, including Lossy Counting, Space-Saving, Augmented Sketch, Heavy Keeper, etc. Experimental results show that our BubbleSketch achieves high precision in finding Top-k elephant flows.

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
