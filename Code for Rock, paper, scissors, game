import random
option=["rock","paper","scissors"]
you_win=0
computer_win=0
tie=0
while True:
    b=random.choice(option)
    a=input (" choose from rock,paper, scissors, exit:").strip().lower()
    if a=="exit":
        print ("thanks for playing,🙏🙏")
        break 
    elif a=="":
        continue 
    elif a==b:
        tie+=1
        print (" oh it's tie😂",tie,"times")
    elif a not in option:
        print ("invalid entry 🚫")
    elif (a=="paper"and b=="rock")or(a=="rock"and b=="scissors")or(a=="scissors"and b=="paper"):
        you_win+=1
        print ("you win😄😄🎉🎉",you_win,"times")
            
    else:
        computer_win+=1
        print (" computer win 🤖🎉💃",b, computer_win,"times")
 
