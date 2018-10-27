---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}
## Static Error Localization
The importance of developing automatic tools to detect program errors has long been recognized by the industry. Advanced type systems and other program analyses has made likely error locations available to programmers. However, those error messages are often verbose and sometimes misleading. Recently, a general framework, [SHErrLoc](http://www.cs.cornell.edu/projects/SHErrLoc/), has came out which takes a more holistic approach to analyze the system of constraints of a program that has a natural graph representation. The framework is shown to be significantly more accurate than the existing tools. To compute all inferable path, SHErrLoc adapts a well-studied algorithm for Dyck-CFL-reachability. However,this traditional dynamic programming style algorithm is expensive which exhibits a cubic time complexity. Our insight is that solving the all-pairs Dyck-CFL-reachability is unnecessary. This motivate us to design a new algorithm for the specific problem. We designed a context free language path finding algorithm based on depth-first search. Given a start node, the algorithm computes all Dyck-reachable informative path during a single graph traversal. The new algorithm is shown to be promising and achieves order of magnitude speedup(square time complexity). Currently, we are optimizing the algorithm and preparing our result for publication. 
