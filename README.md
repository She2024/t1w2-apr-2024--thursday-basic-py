## Control Flow
Order in which ines of code are executed in a program

## Sequential control flow
Exectution of code statements on after another, in the order they appear in the program

# Conditional control flow / control flow
Excecution of code statement based on some input

if tomorrow is Saturday 
    set alarm for 7 
if tomorrow is Tuesday 
    set alarm  for 6 

# Boolean Data Type re-visit
Data type that has two values:    True or False. Boolean values are used to contro the flow of the program. 

# Comparison Operators / Relational Operators
Decised the relationship between the operands. Result of comparision is a boolean value (True/ False)

if tomorrow == Saturday 
    set alarm for 7 
if tomorrow == Tuesday 
    set alarm  for 6 

# If, elsif, else
Simplest form of AI (you could say that)

'if' checks the condition, if true the intended blocks get executed, if false, it skips the intended blocks.

# pass
Does nothing, just ... passes... for now.

day_number - 3

match day_number:
    case 1: 
        pass
    case 2: 
        day_name ="Tuesday"
    case 3: 
        day_name ="Wednesday"
    case 4: 
        day_name ="Thursday"

print(day_name)


# Boolean Operators
AND, OR , NOT. operands need to be boolean as well. Output condition needs to be true or false
a = True 
B= False
result = a and b
print (result) would be Flase

Or 
a = True 
B= False
result = a or b
print (result) would be 

NOT
a = True 
B= False
result = a not b
print (result) would be True

# nested if
age = 20
has_permission = False

if age >=18:
    if has_permission:
        print("Access granted.")
    else:
        print("Access denied.")   
else:
        print("Access denied.")   
if age >=18 and has_permission:
     print("Access granted")   
else:          
     print("Access denied.")   

# Ternary Operator
COndense into one line
"result" if (condition) else "result"  

age = 20
has_permission = False

if age >=18:
    if has_permission:
        print("Access granted.")
    else:
        print("Access denied.")   
else:
        print("Access denied.")   
if age >=18 and has_permission:
     print("Access granted")   
else:          
     print("Access denied.")   

print("Access granted." if age >=18 and has_permission else print"Access denied.")    

# Match-case 
Control flow, similar to switch statements in other langauges
ay_number - 3

match day_number:
    case 1: 
    day_name ="Monday"
    case 2: 
    day_name ="Tuesday"
    case 3: 
    day_name ="Wednesday"
    case 4: 
    day_name ="Thursday"

print(day_name)

# Activity

write python script 
90-100: A
80-
