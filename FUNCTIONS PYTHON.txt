#calling a function
print('Hello, world!')
def my_function():
 print("one metre is 100 centimetres")
my_function()
#arguments
def sum (x, y):
 a=x+y
 print("The sum is",a)
sum(15,25)
sum(205, 405)
def product(a, b):
  c=a*b
  print("The product is", c)
product(16,678)
product(17,749)
def sum(d, e, f):
  g=d+e+f
  print("The sum is",g)
sum(10,20,25)
#ARBITRARY ARGUMENTS)
def courses (*units):
  for subject in units:
    print(subject)
courses("BBIT", "BSCIT", "BCOM", "BHTM")
def cars (*types):
  for machines in types:
   print(machines)
cars("Audi", "Mercedes", "BMW", "Volkswagen")
#Arbitrary Keywords
def courses (**kwargs):
  for key,value in kwargs.items():
    print("{}: {}".format(key, value))
courses(first='Big data',second='CCNA', third='HCIA')
#Default Parameter Value
def Kenya (County= "Mombasa"):
  print("I am from" + County)
Kenya()
Kenya("Nairobi")
Kenya("Kilifi")
Kenya("Murang'a")
#Passing a List as an Argument
def my_function(food):
  for x in food:
    print(x)
fruits= ["apple", "banana", "cherry"]
cars={
"Volvo":"XC90",
"BMW":"X5",
"Mercedes":"E250"
}
my_function(fruits)
my_function(cars)
#function to calculate area of rectangle
def area():
  l=(input("Enter value"))
  w=(input("Enter value"))
  a=int(l)*int(w)
  print("area is", a)
area()

#function to calculate the area of a circle
def area():
  p=3.142
  r=(input("Enter value"))
  a=p*int(r)*int(r)
  print("area is",a)
area()
#function to create the volume of a cylinder
def volume():
  p=3.142
  r=(input("Enter value"))
  h=(input("Enter value"))
  v=p*int(r)*int(r)*int(h)
  print("The volume is", v)
volume()