# feladat
import turtle   
t = turtle.Turtle() 
t.color("red")
nagy = 10
kor = 10  

for i in range(1, kor + 1, 1): 
    t.circle(nagy * i)
