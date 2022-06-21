# python_task1.py
import os
import random
def create():
    c_code=[]
    for i in range(4):
        a=random.randint(0,9)
        c_code.append(a)
    return c_code
def u_code():
    ucode1= input('***enter the 4 digit code:***')
    return ucode1

def working():
    generated_code=create()
    for j in range(0,9):
        result=""
        usercode= [int(j)for j in u_code()]
        
        if len(usercode)!=4:
            print('||||please enter a 4 digit code only||||')
            continue
        if generated_code == usercode:
          print('RRRR')
          print ("<<< YOU GUESSED IT CORRECT >>>")
          break 
        for mem in generated_code:
             if mem in usercode:
               if usercode.index(mem)==generated_code.index(mem):
                  result+="R" 
               else:
                   result+="A"
             else:
                result+="W"
        print("the result is ",result)
    else:
            print("sorry you ran out of tries")
            print("the correct code is ")
            for z in generated_code:
               print(z,end='')           
working()
