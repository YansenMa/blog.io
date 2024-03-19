---
layout: post
title:  "Check Permutation"
tags: algo, array 
mathjax: on
---

**Given two strings, write a method to decide if one is a permutation of the other**

```cpp
#include<iostream>
#include<algorithm>

using namespace std;

bool checkPermutation(string s1, string s2);
int main(){
	string input1 = "abcdefg";
	string input2 = "abcdefa";
	cout << checkPermutation(input1, input2);
return 0;
}


bool checkPermutation(string s1, string s2){

	if(s1.length()!=s2.length()) return false;
	
	sort(s1.begin(), s1.end());

	sort(s2.begin(), s2.end());

	cout << "sorted s1 is:" << s1 << endl;
	cout << "sorted s2 is:" << s2 << endl;
	return s1 == s2;

}

```