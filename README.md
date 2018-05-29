# firstcode


print("SIGN UP")

FirstName = input("Enter your first name: ")
SecondName = input("Enter your second name: ")
UserName = input("enter a user name: ")
PassWord = input("enter your password: ")
EmailAddress = input("Enter your email address: ")
SavedUserName = UserName
SavedPassword = PassWord

print("Thanks for signing up. Please login to continue")
print("Login")



count = 0
Loop = False

while Loop == False:
    username = input("username: ")
    password = input("password: ")
    count+=1

    if username == SavedUserName and password == SavedPassword:
        print("you have successfully logged in You tried"+str(count)+"times")
        break
    else:
        print("wrong username or password. Please try again")
    if count ==3:
        print("you have been looked out. Please cpntact the administrator")
        
        
    
    



        
    











