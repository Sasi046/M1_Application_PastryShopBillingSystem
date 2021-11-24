# M1_Application_PastryShopBillingSystem

#  Code-Inspector Badges

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/8cdfca107f2d460dadc1f134b6dbc2dd)](https://www.codacy.com/gh/Nirmalrg2898/M1_Application_PastryShopBillingSystem/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Nirmalrg2898/M1_Application_PastryShopBillingSystem&amp;utm_campaign=Badge_Grade) 


[![Unit Testing - Unity](https://github.com/Nirmalrg2898/M1_Application_PastryShopBillingSystem/actions/workflows/unity.yml/badge.svg)](https://github.com/Nirmalrg2898/M1_Application_PastryShopBillingSystem/actions/workflows/unity.yml)


[![Code Quality - Static Code - Cppcheck](https://github.com/Nirmalrg2898/M1_Application_PastryShopBillingSystem/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/Nirmalrg2898/M1_Application_PastryShopBillingSystem/actions/workflows/cppcheck.yml)

### Introduction

The source code of Pastry Shop Billing System Project has been written in C programming language without of the use of any graphics. The code is complete, totally error free. It is to be compiled in Visual studios using GCC compiler.

we can use this application to keep the product records such as name, code, prize, quantity, company etc. of your regular stocks. Moreover, if we have a new product, we can add and edit the account at any time.

### User Defined Functions Used

Although graphics has not been used in this project, the application of user defined functions and structures have been effectively used here. The major user defined functions used in this C project are:
1. `void input()`                                                                                                                  
2. `void writefile()`                                                                                                                  
3. `void search()`                                                                                                                     
4. `void output()`

The function `void input()` is used to add the new customer account i.e. with the help of this functions the parameters such as name, code, prize, quantity, company etc. are asked and entered. Another function `void writefile()` has been utilized to create a file on hard disk of computer for storing the information and data of a customer.

The function `void search()` has been used to look for previously stored accounts either by name or by number of the customer. The fourth and the last user defined function used in this Pastry shop billing system Project in C is `void output()` which has been defined to show the result as console output.

In Pastry Shop Billing System, structure has used to group the data type in single unit. The date variables (`day`, `month` and `year`) have been grouped in the structures named date where as other variables such as name, code, prize, quantity, company etc. are grouped under another structure named account.

## Functions 
##### Pastry Shop Billing System application is so simple to use. In order to use the application, click at the exe file and then, you will have six options to:

| Feature Id | Feature |
| -----------|---------|
|F_01| Adding the Products  |
|F_02| Deleting the Products  |
|F_03| Modify the Products |
|F_04| Read the Items |
|F_05| Search the Items |
|F_06| Exit |

As per your need, enter 1, 2, 3, 4, 5 or 6 and follow the instructions provided by the application itself.

### Features

It can hold any number of products and product can be added to the program at any time.
The programming of simple calculations such as calculation of due amount, balance etc. have been embed in the code of project.
The Pastry Shop billing System project in C gives you the facility of searching the account by two ways, either by name of the product or by the number of product.
The product stocks is shown in read system .
If you have nothing to do with the program, you can directly exit from the main menu.

## Folder Structure
Folder               | Description
-------------------  | -----------------------------------------
`1_Requirements`     | Documents Detailing requirements and research.
`2_Architecture`     | Documents Specifying design details.
`3_Implementation`   | All Code and Documentation.
`4_Test Plan`| Test Cases.

## Integrated Tools to GitHub
* [Codacy](https://www.codacy.com/)


## Challenges Faced and How Was It Overcome

1.GCC erorr in windows and linux: installed the gcc msys64 mingw64 properly.

2.Generation of makefile: To overcome this problem research on makefiles was done.

3.Unity testing: Initially a few testcases did not pass, to overcome this issue debugging of program was performed.

## Learning Resources

1.[gcc makefile](https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html#zz-2.1)

2.[github workflow](https://www.programiz.com/c-programming/c-dynamic-memory-allocation)

3.[structure in c](https://www.studytonight.com/c/structures-in-c.php/)


