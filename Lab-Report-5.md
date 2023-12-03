## Lab Report 5
 --- 

# Student Problem

---

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/58a2e23a-1666-4177-973f-ee516c1e2f98)

Hello, I am confused about my error here. I am not sure why my my output is not the expected as I am using the compareTo method that checks the values of the letters. 
Am I not supposed to use it?


# TA Response

---

Hi, why would you think CompareTo is not supposed to be used? Maybe looking at some documentation could help here: [Resource](https://docs.oracle.com/javase/8/docs/api/java/lang/Comparable.html)

# Student Response

---

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/d72f5bd1-2377-46eb-a41e-6ffc362ee63b)


Hello, I looked at the documentation and I realized my mistake. I misunderstood how to use the compareTo value and thought of it in a reverse way to the actual way. So instead of if index2 being greater than index1 as the way I saw it, it was actually index1 greater than index2.

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/7005f469-4533-428a-9435-50e93a5049f9)

# SetUp
---

*File Structure:*

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/9928fdd6-fa38-4dcd-a634-b0a0e39c6cad)

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/bb02e57e-c972-47e2-a4b4-b8dc711dac66)


*Contents of Files:*

**hamcrest-core-1.3.jar**


![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/a0864e64-f089-418d-9ab8-d486e5fc9e1d)


![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/2f4f6703-6a47-44a1-8328-2a50c55aff03)

**junit-4.13.2.jar**


![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/8d8bc5e9-35d1-433c-bcbe-e5b28df7677d)


**test.sh**

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/a295262d-44bd-4d1c-ad66-4f786daeccfc)


**ListExamplesTests**

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/47fb9bb0-1a21-4249-9e3f-d082a91d6558)

**ListExamples**

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/65229a03-da2b-4a1d-b5e8-402ade0e7744)

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/35bbec4d-5106-4061-af02-3593924cb3e6)


*Command to cause bug:*

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/12089bcd-2d1e-4b78-864c-da813f1cb83d)


*Description of bug:*

The edit that is needed is to change the comparison in the conditional from > to < at line 29 of ListExamples.java.

# Part 2 - Reflection 

---

Something that I learned that I found really intresting and look forward to applying to my coding career is working with files and code exclusively through a terminal. I did not know of a way to work with code 
with just terminal commands and bash commands, so I am excited to apply this in the future. I hope that my experience with this in this class will help me with future CSE courses such as CSE30. 






