# school-management-md
name=input("Enter the name :")
m1=int(input("enter the mark a :"))
m2=int(input("enter the mark b :"))
m3=int(input("enter the mark c :"))
Total=m1+m2+m3
avg=Total/3.0
print(name)
print(Total)
print("avg",avg)
if m1>=35 and m2>=35 and m3>=35:
  print("Result pass:")
  if avg>=90 and avg<=100:
    print("Grade 1")
  elif avg>=80 and avg<=89:
    print("Grade 2")
  elif avg>=70 and avg<=79:
    print("Grade 3")
  else:
    print("no grade")
else:
  : Fail")
