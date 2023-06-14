# Chapter 10: The Ultimate Adventure: Risking Life For Thrills and Adrenaline Rushes

Welcome to the 10th chapter of Amazing In Death series. This time, we will delve into the world of extreme sports and adventure that often require risking one's life for the ultimate thrill. Our story begins with a special guest, Dean Potter, a renowned rock climber, and highliner. Potter is famous for pushing the boundaries of what is possible in his sport by attempting dangerous expeditions.

Lieutenant Eve Dallas finds herself investigating a peculiar case when Potter falls to his death during a BASE jump. While Potter's death appears to be a tragic accident, the inconsistencies surrounding the events leading up to his fall lead Lt. Dallas to suspect foul play.

As her investigation proceeds, Lt. Dallas realizes that Potter's passion for adventure and his relentless pursuit of the ultimate thrill brought him in a world filled with risks and rivalries. While searching for the killer, Dallas must navigate this dangerous world and the individuals who strive for death-defying stunts, making her question where the line between adventure and recklessness lies.

In this chapter, we will learn about the different extreme sports and the risks that accompany them. We will also explore how these sports can become intertwined with criminals and make for lethal conspiracies.

Stay tuned for an action-packed chapter filled with adventure, thrills, and unexpected turns.
# Challenge 10: Facing Danger for the Ultimate Adventure

Welcome to Challenge 10 of Amazing In Death series. In this challenge, you will explore the world of extreme sports and adventure and discover the risks that come with chasing the ultimate thrill. You will also get to know a special guest, Dean Potter, a legendary highliner, and rock climber.

To complete this challenge, you need to write a Python program that simulates a BASE jump. Your program should ask the user for their name and print a message welcoming them to the adventure. Then it should prompt the user to enter the height of a building or cliff they want to jump off. After the user has entered the height, the program should calculate the time the BASE jumper would take to hit the ground.

Your program should also include a safety feature that calculates the minimum allowed height for a BASE jump given the user's experience level. If the user enters a height that is below the minimum allowed height, the program should print a message warning them of the risks involved in BASE jumping from that height.

Finally, your program should print a message that tells the user the outcome of their BASE jump. Depending on the height they entered, the program should print one of the following messages:

- You jumped successfully and landed safely! You are an adrenaline junkie and ready for more challenges.
- You jumped but didn't deploy your chute in time. You didn't make it to the ground alive. Always follow safety protocols.
- You chickened out and didn't jump. BASE jumping requires courage and a passion for challenges.

Good luck in your BASE jumping adventure, and remember that staying safe is the ultimate adventure.

## Example Output

```
Welcome to the BASE jumping simulator, Sarah!

Please enter the height of the building or cliff you want to jump off (in meters): 200

You jumped successfully and landed safely! You are an adrenaline junkie and ready for more challenges.
```
To solve this challenge, we need to write a Python program that simulates a BASE jump. The program should ask the user for the height of the building or cliff they want to jump off and calculate the time it takes for the jumper to hit the ground. The program should also include a safety feature that calculates the minimum allowed height for a BASE jump given the user's experience level and prints a warning message if the user enters a height that is below the recommended level.

We will use Python's built-in `math` module to perform the required calculations. Specifically, we will use the `sqrt` function to calculate the square root and the `ceil` function to round up to the nearest integer.

Here's the breakdown of the code used to solve this challenge:

```
import math

print("Welcome to the BASE jumping simulator!")

# Ask the user for their name and greet them
name = input("What is your name? ")
print(f"Hello, {name}!")

# Ask the user for the height of the building or cliff they want to jump off
height = float(input("Please enter the height of the building or cliff you want to jump off (in meters): "))

# Calculate the time it takes to hit the ground using the formula t = sqrt(2h/g), where h is the height and g is the acceleration due to gravity
time = math.sqrt((2 * height) / 9.81)

# Calculate the minimum allowed height for a BASE jump based on the user's experience level
experience = input("Please enter your level of experience (beginner, intermediate, advanced): ")
if experience == "beginner":
    min_height = 30
elif experience == "intermediate":
    min_height = 50
else:
    min_height = 100

# Print a warning message if the user entered a height below the recommended level
if height < min_height:
    print(f"WARNING: BASE jumping from a height below {min_height} meters is not recommended for {experience} jumpers.")

# Print the result of the BASE jump simulation
if time <= 5:
    print("Congratulations! You successfully landed on the ground.")
else:
    print("Sorry, you didn't deploy your parachute in time!")

```

First, we import the `math` module, which provides access to mathematical functions.

Next, we ask the user for their name and greet them. Then, we ask the user for the height of the building or cliff they want to jump off and store the input as a float variable called `height`.

We calculate the time it takes to hit the ground using the formula `t = sqrt(2h/g)`, where `h` is the height and `g` is the acceleration due to gravity. We use the `sqrt` function from the `math` module to calculate the square root.

We then ask the user for their level of experience and calculate the minimum allowed height based on their answer. We store the minimum allowed height in a variable called `min_height`.

If the user entered a height below the recommended level, we print a warning message to the console.

Finally, we determine the result of the BASE jump simulation based on the calculated time. If the time is less than or equal to 5 seconds, we print a message congratulating the user for successfully landing on the ground. Otherwise, we print a message indicating that the jumper failed to deploy their parachute in time.

That concludes the explanation of the code used to solve this challenge.


[Next Chapter](11_Chapter11.md)