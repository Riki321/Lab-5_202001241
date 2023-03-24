# Lab-5_202001241
### Name: Parikh Riki Anilbhai
## Student ID: 202001241

### For static tool anaysis I will use <b>mypy</b> tool.
## Reference Git Repository: (https://github.com/arrobalytics/django-ledger)

## what is mypy tool and how to use it:
Mypy is an optional static type checker for the Python programming language. It allows developers to specify the types of variables, function arguments, and return values in their Python code, and then checks that the code is consistent with those types. Mypy can catch certain types of errors early, before the code is executed, which can make it easier to catch bugs and improve the overall quality of the code.

Mypy uses a syntax similar to Python's type hinting syntax, introduced in Python 3.5, to specify types. While Python is a dynamically typed language, mypy allows developers to add static typing to their code to make it more robust and easier to maintain. Mypy can also be integrated with popular text editors and IDEs, making it easy to use as part of the development workflow.
## Process:
### 1. install mypy using command: `python -m pip install mypy`<br>
![image](https://user-images.githubusercontent.com/79001372/227493562-d6b8a88b-e27c-44c4-b14a-e8dc0df11376.png)
-----
### 2. Run the following command for analysis of code: `python -m mypy <path_of_file>`<br>
![image](https://user-images.githubusercontent.com/79001372/227493988-2bb25c8e-9f01-4c6e-bb55-9f9917817c0c.png)
-----
### 3. errors:<br>
![image](https://user-images.githubusercontent.com/79001372/227474222-949724e1-ca59-4d83-a122-d1c0704d6f5d.png)
### The error[import] shows that the modules are not found because in are local system we did not install those modules.<br>
-----
![image](https://user-images.githubusercontent.com/79001372/227481117-8dd8d9b3-4db2-4ac3-b291-07853cf4be01.png)<br>
### The error[import] shows that the modules are not found and also show the tips.<br>
-----
![image](https://user-images.githubusercontent.com/79001372/227488524-cdcd5718-56c3-4264-9556-3c245040d93b.png)<br>
### The error[syntax] is the syntax error.<br>
-----
![image](https://user-images.githubusercontent.com/79001372/227492291-2378a062-edeb-4c87-92d0-a1453f7035cd.png)
### error[return-value] shows what is the return type and what is return type expacted
-----
![image](https://user-images.githubusercontent.com/79001372/227487102-a8f0d780-bb64-433d-afff-3b3f50806cc7.png)<br>
### the succsessful excuation of the file.<br>
-----



