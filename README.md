# class student:
def_int_(self,name,id):
self.name=name
self.id=id
self.display()
def display(self):
print ("name:\t",self.name,"id_number:\",self.id)
class Grade(Student):
def_int_(self,name,id,mark,):
super()._int_(name,id)
self.mark=mark
self.calculate()
def calculate(self):
if 90 <=self.mark <=100:
grade="A+"
return grade
elif 85 <=self.mark <90:
grade="A"
return grade
elif 80 <=self.mark <85:
grade="A-"
return grade
elif 75 <=self.mark<80:
grade="B+"
return grade
elif 70 <=self.mark <75:
grade="B"
return grade
elif 65 <=self.mark < 70:
grade="B-"
return grade
elif 60 <=self.mark <65:
grade="C+"
return grade
elif 55 <=self.mark <60:
grade="C"
return grade
elif 50 <=self.mark <55:
grade="C-"
return grade
elif 45 <=self.mark <50:
grade="D"
return grade
elif 40 <=self.mark<45:
grade"F"
return grade
 
class remark(Grade):
pass
def Remark(grade):
if grade =="A+":
return "Excellent"
elif grade =="A":
return "Very Good"
elif grade =="A-":
return "Good"
elif grade =="B+":
return "Remarkable"
elif grade =="B":
return "Satisfactory"
elif grade =="B-":
return "Fair"
elif grade =="C+":
return "Not Bad"
elif grade =="C":
return "Poor"
else:
return "Very Bad"

Name = input("Enter the name of student:\n")
Id = input("Enter student id:\n")
Mark = float(input("Enter the Student mark:"))
Student = Grade(Name,Id,Mark)
R = student.calculate()
print("Name\t Id_Number\t Grade\t Remark\n")
print(student.name,student.id,student.mark,Remark(R))
