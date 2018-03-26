import sys
def register():
    students = []
    mark = []
    
    students = input("Please enter the student name: ")
    mark = int(input("Enter mark between 0 and 10"))
    # enter marks for each student
while True:            
    register()
    students = input("Please enter the student name: ")
    mark = int(input("Enter mark between 0 and 10"))
    done=True
    if done:
        register_next = input("Do you want to register next student Y/n?")
    else:
        ("Thank you for registering, please call again!")
        break
