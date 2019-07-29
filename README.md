# Login-system
Login system with python


from colorama import * 
init()



y = input("do you have a account? select y/n: ")

if y == "y":
    while True:
        Email = input("Enter you Email:")
        Password = input("Enter you password:")
        ConfrimPassword = input("Confrim your password:")
        if Password == ConfrimPassword:
            print("login successful")
            break
        if Password != ConfrimPassword:
            print("Incorrect password")
            break
while True:
    input()
if y == "n":
    while True:
        NewEmail = input("Enter new email:")
        Newpassword = input("Enter new password:")
        ConfriPassword = input("Confrim password:")
        if Newpassword != ConfriPassword:
            print("Incorrect password, please try again")
            break
        if Newpassword == ConfriPassword:
            print("register success")
            break
while True:
    input()        
        
