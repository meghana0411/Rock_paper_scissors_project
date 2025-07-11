"# Rock_paper_scissors_project" 
player=int(input("Enter 1 for Rock, 2 for Paper, or 3 for Scissors: "))
import random
computer=random.randint(1,4)
print("You chose:", player)
print("CPU chose:", computer)
if player==computer:
    print("It's a tie!")
elif (player==1 and computer==3) or (player==3 and computer==2) or (player==2 and computer==1):
    print("The player Won!")
    
elif (player==3 and computer==1) or (player==2 and computer==3) or (player==1 and computer==2):
     print("Computer Won!")


    
