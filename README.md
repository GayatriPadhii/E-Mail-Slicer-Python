#collecting email from user
#split the email using the @,the first part as user name and the second part using domain name
#split domain using .com
#www@hello.com
#www and com are sliced off to get the username
def main():
    print("Hello")
    print("Welcome to Email Slicer")
    email_input=input("Enter your desired email address: ")
    (username,domain)=email_input.split("@")
    (domain,extension)=domain.split(".")
    print("Username of the email id is:" ,username)
    print("Domain name is:",domain)
    print("Extension name:", extension)
while True:
    main()

