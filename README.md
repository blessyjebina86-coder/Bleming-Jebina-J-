m1=int(input("Enter a mark 1:"))
m2=int(input("Enter a mark 2:"))
m3=int(input("Enter a mark 3:"))
m4=int(input("Enter a mark 4:"))
m5=int(input("Enter a mark 5:"))
total=m1+m2+m3+m4+m5
avarage=total/5
print("Total marks=",total)
print("avarage=",avarage)
if avarage>=90:
    print("Grade : A")
elif avarage>=75:
    print("Grade : B")
elif avarage>=50:
    print("Grade : C")
else:
    print("Grade : Fail")
