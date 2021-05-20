Lab1 Report
================================

Title: Dependency Analysis and Dependency Graph on EnglishPal

Author: 黄文心、朱彩凤、朱倩

Date: 2021/5/20

Inroduction
==================

We want to avoid the Big Ball of Mud antipattern in our software application.So we do the dependency analysis and dependency graph for project EnglishPal.



# Materials and Methods

EnglishPal is based on python. In this experiment, we do dependency analysis and draw dependency graph about it. We use Snakefood[1] tool to generate module level dependency graph, and use Mermaid tool to draw class / function level dependency graph.



# Results

- The module-level dependency graph of EnglishPal
  - Code: [EnglishPalDependency(Graphviz).txt](https://github.com/Blue-ljj/LanLab1-Report-Docs/blob/master/EnglishPalDependency(Graphviz).txt)
  - PDF: [snakefood.pdf](https://github.com/Blue-ljj/LanLab1-Report-Docs/blob/master/snakefood.pdf)
- The class/function-level dependency graph of EnglishPal
  - Code: [mermaid.txt](https://github.com/Blue-ljj/LanLab1-Report-Docs/blob/master/mermaid.txt)



# Pros&Cons

- Pros: The project has low complexity and clear framework,so it's easier to maintain the code later.
- Cons: Hinder technological innovation,and there are still many bugs in the project that need to be improved.



# Discussions

The Snakefood tool can analyze dependencies in project code, but only at the module level. Mermaid can plot the dependency of our input into a function level dependency graph.

Through the dependency analysis and the drawing of the dependency graph of EnglishPal, we can see the framework structure of the project more clearly, which provides convenience for the maintenance and update of the code in the future.



# References

[1] [Snakefood User Manual](http://furius.ca/snakefood/doc/snakefood-doc.html)

[2] [Graphviz Online](https://dreampuf.github.io/GraphvizOnline/)

[3] [A Brief Guide How to Write a Computer Science Lab Report](https://thehackpost.com/a-brief-guide-how-to-write-a-computer-science-lab-report.html)

[4] [Read the Docs](https://readthedocs.org/ )`