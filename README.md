# Minimum Mean Cycle Problem

## Table of Contents
- [Intorduction](#intorduction)
- [Directory Tree](#directory-tree)
- [Description and Usage](#description-and-usage)
- [Requirements](#requirements)
- [Contributor](#contributor)

## Intorduction
Designed an algorithm for finding the Minimum Mean Cycle in a weighted directed graph using dynamic programming. This algorithm is an extension of the Bellman-Ford algorithm that computes single source shortest paths and it is capable of finding the minimum mean cycle in polynomial time. This is the final project of the Advanced Algorithm class in NCTU.

## Directory Tree
<pre>
Minimum_Mean_Cycle/
├─ doc/ ................ 
│  └─ lab1-readme.pdf .. 
├─ src/ ................ 
│  ├─ DistanceList.cpp . 
│  ├─ DistanceList.h ... 
│  ├─ MMC .............. 
│  ├─ Makefile ......... 
│  ├─ Node.cpp ......... 
│  ├─ Node.h ........... 
│  ├─ dumpParser.txt ... 
│  ├─ main.cpp ......... 
│  ├─ parser.cpp ....... 
│  ├─ parser.h ......... 
│  ├─ readme.txt ....... 
│  └─ solution.txt ..... 
└─ testcase/ ........... 
   ├─ case.txt ......... 
   ├─ cycle_1.in ....... 
   ├─ nocycle_1.in ..... 
   ├─ pci_bridge32.in .. 
   └─ usb_phy.in ....... 
</pre>

## Description and Usage
**Problem Formulation**
<!-- $$
\begin{aligned} 
    &\text{Given a directed graph}\ G(V,E)\ \text{and}\ w_e\ \text{denotes the weight of edge}\ e\ \text{. For each cycle}\ c_i \in G, \\
    &\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad 
     w_{c_i}=\sum_{e\in c_i} \frac{w_e}{\left|c_i\right|},   \qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad \\
    &\text{where}\ \left|c_i\right|\ \text{is the number of edges of}\ c_i\ \text{. The minimum mean cycle problem is to find the minimum}\ w_c^* \\
    &\text{so that}\ \forall c_i \in G,\ w_{c_i}\geq w_c^*.
\end{aligned}
$$  -->

<img src="svg/ZRVY3MtRPh.svg"/>

**Usage**



## Requirements
- **C++**

## Contributor
- [Hong-Ming Chiu](https://hong-ming.github.io/)