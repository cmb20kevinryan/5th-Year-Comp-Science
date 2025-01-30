#5th Year March Assessment - Kevin Ryan
#Q1
for i in range(1, 21):
    print(i)

#5th Year March Exam
#Q2
total = 1

while total > 1 and total < 50:

#5th Year March Assessment - Kevin Ryan
#Q3

name = input("Enter your name: ")

for i in name:
    print(i)

#5th Year March Assessment - Kevin Ryan
#Q4
#(i)
print("***********************************")
print("**Welcome to your Library Account**")
print("***********************************")
print("Option 1:           Return a book"  )
print("Option 2:           Borrow a book"  )
print("Option 3:           Exit"           )

#(ii)
username = "Kevin142"
password = "8521"

userTry = input("Enter your username: ")
passTry = int(input("Enter your password: "))

#(iii)
while userTry != username:
    input("Enter your username: ")
    
#(iv)
count = 0
while passTry != password:
    passTry = int(input("Enter your password: "))
 while passTry <3:
    if password != passTry:
        count+=1
print("Account is blocked")
