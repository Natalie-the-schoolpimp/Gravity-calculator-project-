# Gravity-calculator-project-
#Natalie Diaz
11/4/21
#This Program calculates the distance a suspended object falls given
print("This Program calculates the distance a suspended object falls given ")
# Get gravity from user
G=float(input("Enter gravity from user")) 
#Convert string to int
int=6.673*(G) 
#Get fps from user
fps=float(input("Enter fps from user"))
#Convert string to int
int=6.673*(fps)
#Get number of frames from user
f=(G*fps)
#Convert string to int
#Calculate time object is falling
time=f/fps
#Calculate distance in pixels object has fallen
distance=fps*time
print("It will drop",distance,"pixels in",time,"seconds") 
d=0.5*(G*time**2)
#Output time to user
print("The gravity within the suspended object is:",round(distance,2),"P")
