# rock-_paper_scissor
import random
user_choice=int(input("enter choice 0 for rocks,1 for paper,3 for scissor"))
if user_choice>=3 or computer_choice<=0:
  print("invalid choice")
else:
computer_choice=random.randint(0,2)
  print("computer_choice")
  if computer_choice==user_choice:
    print("draw")
  elif computer_choice==0 and user_choice==2:
    print("lose")
  elif user_choice==0 and computer_choice==2:
    print("win")
  elif computer_choice> user_choice:
    print("lose")
  elif user_choice> computer_choice:
    print("win")

  
