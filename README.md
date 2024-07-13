print("Welcome to the Adventure Game!")  

  

name = input("What is your name? ")  

  

print("Hello, " + name + "! You are on a quest to find the legendary treasure.")  

  

print("You are standing in a dark forest. There is a path to your left and a path to your right.")  

  

path = input("Which path do you choose? (left/right) ")  

  

if path == "left":  

  print("You walk down the left path and find a river. There is a boat, but it's broken.")  

  fix_boat = input("Do you want to fix the boat? (yes/no) ")  

  if fix_boat == "yes":  

    print("You fix the boat and cross the river. You find a chest filled with gold!")  

  else:  

    print("You can't cross the river and get eaten by a dragon. Game over!")  

else:  

  print("You walk down the right path and find a cave. There is a dragon inside!")  

  fight_dragon = input("Do you want to fight the dragon? (yes/no) ")  

  if fight_dragon == "yes":  

    print("You fight the dragon and win! You find a chest filled with gold!")  

  else:  

    print("You run away and get lost in the forest. Game over!")  

  

print("Thanks for playing, " + name + "!")     
