---
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}
## Static Error Localization
The importance of developing automatic tools to detect program errors has long been recognized by the industry. Advanced type systems and other program analyses have made likely error locations available to programmers. However, those error messages are often verbose and sometimes misleading. Recently, a general framework, [SHErrLoc](http://www.cs.cornell.edu/projects/SHErrLoc/), has came out which takes a more holistic approach to analyze the system of constraints of a program that has a natural graph representation. To compute all inferable path, SHErrLoc adapted a well-studied algorithm for CFL-reachability. However, this traditional dynamic programming style algorithm was highly expensive, which yielded a cubic time complexity. Our recognition was implemented as we created a new, tailored algorithm.The new algorithm we developed was shown to be promising and achieved orders of magnitude speedup. Currently, we are optimizing the algorithm and preparing our results for publication. 
