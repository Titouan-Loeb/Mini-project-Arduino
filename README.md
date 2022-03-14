# Mini-project Arduino - Making a simon
<p align="center">
  <img src="https://user-images.githubusercontent.com/3193712/44806323-03658480-ab9d-11e8-86b9-34c64f2b5966.gif" width="400"/>
</p>

## Introduction
Now that you know more about arduino, let's try to do a real project: a Simon! (you can try it [here](https://basisonderwijs.online/digibordtools/simon.html))

This project will be less guided than the workshop, but don't worry, we are still here to help you. Feel free to ask any question!

## Setup
To carry out this mini-project, you need to create an account on [Tinkercad](https://www.tinkercad.com).

**When you are logged in:**
* On the left of your dashboard, click on "**circuts**"
* And then, click on "**Create a circut**"

## Milestone n°1: Setup your colors
**Instruction**: The first thing you want to do is to have 4 buttons and 4 LEDs.
Each button correspond to an LED and each time you push a button its LED should turn on for a choosen amount of time, at the same time you should play a sound which depends on the button you pushed.

<details>
    <summary> 🛠 Required material:</summary>

* Arduino
* BreadBoard
* Cable USB
* Jumpers
* 4 LEDs
* 4 Buttons
* 4 to 8 Resistors
* 1 Piezoelectric sensor

</details>

>:bulb: You can change the color of the LED

## Milestone n°2: Computer's turn
**Instruction**: Now you want the computer to chose ramdomly a color and play it. When its done let him repeat the sequence and add a color at the end. Make this a loop that never ends.

🛠 No required material

## Milestone n°3: Player's turn
**Instruction**: Finaly, you want to be able to play. After the computer's turn let the player to try to repeat the sequence. Check if the sequence is correct, if it is not, stop the game and turn on an led to indicate that the game is over

<details>
    <summary> 🛠 Required material:</summary>

* 1 LED
* 1 Resistor

</details>

## BONUS
Here are few things that you can add if you have finished this mini-project:
* Try to read all the buttons states only by reading on a analog input pin.
* Increase the speed while the sequence is getting longer.
* Replace the led that tells when the game is over with a RGB LED that indicates who's turn is it and when the game is over using different colors.

Super c'est fini
