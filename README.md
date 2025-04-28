# treasure-island-
print("welcome to treasure island your mission is to find the treasure")
direction=input("help us with the direction,left/right")
if direction=="left":
    print("go to next level")
    level_1=input("swim/wait")
    if level_1=="wait":
       print("next level HURRAY!") 
       level_2=input("which door?,red,blue,yellow")
       if level_2=="yellow":
          print("you win ! :)")
else:
    print("game over")    
        
