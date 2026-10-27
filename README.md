#Q1
print("Hello JKLU")
print("I am learning python")
#Q2
Name=input("Enter Name :")
Branch=input("Enter Branch :") 
print("Welcome!",Name,Branch)
#Q3
Len=int(input("Enter Length : "))
Wid=int(input("Enter Width :"))
Area=Len*Widprint(Area)
#Q4
Length=int(input("Enter Lenght (in Feet) :"))
Width=int(input("Enter Width (in Feet) "))
Area_feet=Length*WidthArea_met=Area_feet/3.281
print("Area in Meters :", Area_met)
#Q5
X=int(input("Enter a +ve Number X :"))
Y=int(input("Enter a +ve Number Y :"))
if X<0 or Y<0:    
print("Invalid Input")
elif Y%X==0:   
print("Y is divisible by X")
else:   
print("Y is NOT divisible by X")   
#Q6
Num=int(input("Enter a number :"))
if Num%2==0:   
print("Number is Even")
else:  
print("Number is odd")  
#Q7
rad=int(input("Enter Radius of Circle :"))
if 
rad>100 or rad<1:   
print("Invalid Input")
else:   
print("Area of circle :", 3.14*rad**2) 
#Q8
Temp_Cels = float(input("Enter temperature in Celsius :"))
Temp_fahr = (Temp_Cels * 1.8) + 32Temp_Kel = Temp_Cels + 273.5
print("Temp In Celsisu :", Temp_Cels)
print("Temp in Fahr :", Temp_fahr)
print("Temp in Kelvin :", Temp_Kel)
#Q9
seconds=int(input("Enter seconds(1-86400)"))
if 1<=seconds<=86400 :  
hours=seconds//3600   
minutes=seconds%3600    seconds=seconds%60
print(hours,":",minutes,":",seconds)
