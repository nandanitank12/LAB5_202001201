# LAB5
###### Name: Tank Nandani Jagdishbhai
###### Student_ID : 202001201
## Objective: Static analysis of random github repositories using Static Analysis Tools

## Repository Analysed


For the Purpose of this lab, 
the repository selected to test various tools is https://github.com/TheAlgorithms/Python

![image](https://user-images.githubusercontent.com/89512213/225582547-a6cc6cec-f78d-45e4-a775-3f4b5d6c4a50.png)


this is repository which selected.

## MYPY

MYPY is static type checker tool for python. It helps ensure that the variables and functions used in the code work correctly. It analyzes the code to check for type errors as well which can occur during run time without actually running the code!

this command is use for Install mypy

```
pip install mypy
```
to check a file and generate a report, we run following command

```
python -m mypy <python filename(s) / foldername(s)>
```

## 1) For all_combinations.py

![image](https://user-images.githubusercontent.com/89512213/225580277-bf014483-074f-448b-8aec-037460ad244b.png)


- this file has no error found in their source files.

To check the entire current directory at once, we can run following command
```
python -m mypy .
```

## 2) For ciphers

![image](https://user-images.githubusercontent.com/89512213/225581156-25a0160d-9c65-48ec-83a4-28b228b50b0e.png)



- This file has shown the error about the numpy.
- Folder cipher has error in numpy module and cipher folder filoe has issues about numpy module and implemation issues in their files.
- Also show the error about numpy implementation and also show the error about libary and module stub.

