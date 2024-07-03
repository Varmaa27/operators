# operators

#arithmetic operators
 #--(+-*/**%//)
x=4
y=2
z=x+y,x-y,x*y,x/y,x%y,x**y,x//y
print(z)

#assignment operators
#--(=,+=,-=,*=,/=)

x=3
print(x,"assignment")

x=3
x+=5
print(x)

x=3
x-=5
print(x)

x=3
x*=5
print(x)

x=3
x/=5
print(x)

x=3
x%=5
print(x)

x=3
x//=5
print(x)

x=3
x**=5
print(x)

#comparison operators
#--(==,!=,>,<,>=,<=)

x=2
y=4
print(x==y,"comparison")
print(x!=y)
print(x>y)
print(x<y)
print(x>=y)
print(x<=y)

#logical operators
#--(and,or,not)

#and
x=6
print(x>9 and x<9,"logical")

#or
x=6
print(x>9 or x<9)

#not
x=6
print(not(x>9 or x<9))

#identy operators
#--(is,is not)

#is
x=5
y=5
print(x is y,"identity")
print(x is not y)

#membership operators
#--(in,not in)

#in
x=["varma","hero"]
print("raju" in x,"membership")
print("varma" in x)

#not in
x=["varma","hero"]
print("raju" not in x)

#bitwise operators
#--(&,^,!,<<,>>)

x=7
y=6
z=(x&y)
print("x=",bin(x),"bitwise-and")
print("y=",bin(y))
print("z=",bin(z))



x=7
y=6
z=(x|y)
print("x=",bin(x),"bitwise-or")
print("y=",bin(y))
print("z=",bin(z))

x=7
z=(x>>y)
print("x=",bin(x),"bitwise-right shift")
print("z=",bin(z))


x=7
z=(x<<y)
print("x=",bin(x),"bitwise-left shift")
print("z=",bin(z))
