# PYTHON-ASSESSMENT-
#Coding questions
#frequently repeated vowels in given string
n=input()
str="aeiou"
for i in n:
    if i in str and n.count(i)>1:
       print(i)
       break
