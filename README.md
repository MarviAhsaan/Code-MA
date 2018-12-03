# Code-MA
print("Hello, World!")
print("The game is about to start...")
print("Booting up...")
print("...")
print("...")
print("...")
print("Ready")
print()        # <- blank line
name = input("Hi there. What's your name? > ")
print()
print("Hi,", name, "--- Welcome to The Mars Adventure Game.")
print("Yesterday, you received a call from your good friend at NASA.")
print("They need someone to go to Mars this weekend, and you've been chosen.")
print()
print("Are you excited? Type Y or N")
excited = input("> ")
excited = excited.upper()
print("How many suitcase you'r are bringing?")
num_suitcases=input(">")
num_suitcases=int(num_suitcases)
if num_suitcases >= 2:
    print("That's way too many. You'll have to pack more lightly.")
else:
    print("Perfect. You'll certainly fit in the spaceship!")
    print("Please try to fit your stuff into 2 suitcases.")
    print("You're allowed to bring one companion animal with you.")
    print("What kind of companion animal would you like to bring?")
    companion_type=input(">")
    print("What is your companion's name?")
    companion_name=input(">") 
    companion_name=companion_name.title() 
    print("Cool, so you're bringing {} the {}".format(companion_name,companion_type))
    print()
    print("NASA has a interior design team offering to outfit your space ship.")
    print("You have a couple of options for the interior decor of your ship.")
    print()
    print("Your options are:")
    print(" A  Sleek, modern minimalism")
    print(" B  Retro/vintage space age")
    print(" C  SF Hippie chic")
    
print("Which decor would you like? Choose A, B, or C.")
decor_choice = input("> ")
decor_choice = decor_choice.lower()
decor_choice = decor_choice.strip()
if decor_choice == "a":
    decor = "modern minimalist"
elif decor_choice == "b":
    decor = "retro"
elif decor_choice == "c":
    decor = "hippie chic"   
    print("I can see it now:")
    print(name, "and", companion_name, "surfing the celestial abyss ...")
    print("in a", decor, "spaceship.")
    print(name, "-- the day is here!")
    print("You crawl into the spaceship with", companion_name)
    print("Brace for take off!")
import time
timer = 5
while timer > 0:
    print(timer, "...")
    time.sleep(2)
    timer = timer - 1
print("*** LIFTOFF ***")
