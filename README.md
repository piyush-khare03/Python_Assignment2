# Python_Assignment2
#_____________________________Question: 1_______________________________________________#

marks = int(input("Enter your marks: "))
if marks >=90:
    print("A")
elif marks >= 80 and marks <= 89:
    print("B")
elif marks >= 70 and marks <= 79:
    print("C")
elif marks >= 60 and marks <= 69:
    print("D")
elif marks < 60:
    print("F")
else:
    print("Something Went Wrong, Please Try again!!")

#_____________________________Question: 2_______________________________________________#

#Creating Data

Std_data = {
    "piyush":91,
    "Toshi":89,
    "Niks":86
    }                                                                         

#Adding New Data

Std_data["Sonika"] = 99

#Updating Data

Std_data.update({"piyush":93})

print(Std_data)

#_____________________________Question: 3_______________________________________________#

file = open ("Notes.txt","r")       #Opening a file name "Notes.txt" in read mode
data = file.read()                  

print(data)                         #Printing data of file "Notes.txt"

file.close()                        #Closing File

#_____________________________Question: 4_______________________________________________#


file = open ("Notes.txt","r+")       #Opening a file name "Notes.txt" in write mode

data = file.read()

print(data)                          #Printing data of file "Notes.txt"


file.write('This is a warning!! be Aware\n')        #Adding new line 


file.close()                         #Closing File

