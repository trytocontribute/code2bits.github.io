---
layout: post
title:  "Code Challenge: HackerRank - Algorithm - Solve Me First"
date:   2017-12-06 00:00:00
author: André Maré
categories: [code_challenge, hackerrank]
---

![soft_skills]({{site.url}}/images/blog_header/78600152_m.jpg)

### Problem Statement
This is one of the first challenges to solve in the Algorithm section of  HackerRank. The first problem focus on reading in values from the "standard input stream", adding the two values together, and then writing the sum out to the "standard output stream".

For a detailed explanation of the problem, read the Solve Me First challenge on <a href="https://www.hackerrank.com/challenges/solve-me-first">HackerRank</a>.

<!--more-->

### Solution
The solution is very simple and consist of reading two values in from the "standard input stream", adding them together and then writing out the sum of the two values to the "standard output stream".

#### Java
The main method reads in two integer values and invokes a method called "<em>solveMeFirst</em>". The result of the method is then printed out. The solveMeFirst method adds the two integer parameters and return it as the result.
 
```java
public static int solveMeFirst(int a, int b) {
	return a+b;
}

public static void main(String[] args) {
	Scanner in = new Scanner(System.in);
	int a;
	a = in.nextInt();
	int b;
	b = in.nextInt();
	int sum;
	sum = solveMeFirst(a, b);
	System.out.println(sum);
	in.close();
}
```


#### Source Code Repository
The source code of the solution can be found on <a href="https://github.com/Code2Bits/HackerRank-Java/tree/master/src/main/java/com/code2bits/hackerrank/algorithms/warmup/solve_me_first">GitHub</a>.



