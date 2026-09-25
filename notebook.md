## Table of Contents

- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)
- [Blocks](#blocks)
- [Concepts](#concepts)
- [Vocabulary](#vocabulary)
  - [Headings](#headings)
- [Text Formatting](#text-formatting)
 




## Blocks


Block	What Your Notes Should Include
Hat Block	: Starts a stack of blocks they are shaped to connect to blocks below them and are usually shaped in a way so nothing can be attached on top of them 

Stack / Command : these are gonna be the main components of a stack and are resposible for a majority of the commands in a stack , they are shaped in such a way that they are able to have code stacked op top of and below it as well as usually accepting some sort of reporter or booleon block usually .

C-Blocks : well as the name implies they're shaped like a C this gives =them the abilty to have main/command blocks placed inside them for example one could have a stack of commands go for forever if said 

blocks are placed within that forever command . they can do a vareity of things but often they act as a check to see if somthing is true or false or loops the code stack forever🏭 

Reporter / Oval Block :	as the name implies this oval shaped block repots values in the form numbers and fits inside any oval shaped space in a code block , for example a distance in mm blocks 

Boolean / Hexagonal Block :	these are hexagonal shaped block that at their core return true or false values that's it , they also fit inside any hexagonal shaped space in a code block 

Repeat Block : this is a C shaped block like all other c shaped blocks they contained command/main blocks and get this repeats them for example you could have a move for 200mm block and put that withing a repeat block for whatever amount of time you want it to repeats and it will repeat the action in this case a move for 200 mm block  

Wait Until Block : this block is fairly self descriptive one it waits till a value comes back as true or false then preforms the code stack underneath btw this block is shaped like a standard main/command block it can have block above and below it as well as a slot for a Boolean block which defines what values allow the wait until block to allow a code stack to start 

If Then Block : This is a c shaped block with a slot for a Boolean block and it serves similarly to the wait until block , at its core it waits until a specified value comes back as true then executes a stack of code within that c shaped block , for example you could have a if then block with a if  " parameter 1 " then ' result 1 " 

Forever Block	: This a c shaped block and like all c shaped blocks main/command code can be place inside it , placing code inside a forever block causes that code to loop infinitely for as long as a program is running for example let say your trying to code a arrow that points to a center while spinning to do this you must constantly update the orientation of said arrow in this example using a forever block would be a great move since you dont have to run a bunch of the same code for the same result . 

## Concepts

Sequence : the sequence of events is a simple yet important concept in programing as it tells the computer when to do what this can allow for smooth operation of the code and hence whatever project your working on be it toolpaths for a cnc machines , instructions for a robot or simply code for a game . even though it is a simple concept most dont think to hard about it is a foundational concept for anything including coding .

Parameters : simply put is a place holder variable that when properly defined dictates what data or a value does , for example if you have a value say 800 that value by itself means nothing it not defined by any sort rules but take that same value and put it in the parameter of " move forward for X , Y or Z amount of mm " it has rules to follow instructions to execute , without parameters you essentially have loose values and data 

Loops / Iteration : these are pretty much the same thing the only difference between these two is that a iteration is a loop that only repeats a certain amount of time that aside the concept itself is fairly simple , all it does is loop a segment or piece of code . loops can be used for a variety of purposes whether you need to constantly update a condition or value or simply want to execute the same sequence without making a monolith of a code stack they are really a all purpose tool that can be used for all sorts of things 

Sensors	: without these you are blind , sensors are a important part of robotics they are essential for gathering environmental information , they do this with a array of sensors such as the gyro sensor , eye sensors , distance sensors so on they supply the robot with various data and allows he robot to respond to environmental stimuli.

Booleans & Conditions : put simply Booleans/condition's are a set of values that that can be either a true or false , for example lets say you wire a piece of code that turns on light when it sees the color red you could having something like this " if sensor detect red turn on light if senor detect anything ither then red keep searching "  

Sense → Think → Act : this is really simple its essentially the process on how robots work its senses something then it thinks about that information runs it through the code and from there makes a choice based off the information and parameters given 

Comparisons	: these are basically true or false statements in its simplest form it just basically seeing if one number is bigger then a other then produces a true or false statement from that  example the statement " if X>Y turn right " essentaily compares the values if x and y and sees if X is bigger if it is bigger then it produces a true statement then lets the line of code continue , and if it is not  bigger then X then it produces a false statement and halt or diverts the logic stream im over complicating it but trust me they really are quite simple 

Coordinates	: the coordinates of a robot describe its location and is often in the form of x,y and maybe z these variable's describe different postional values in refrence to a often invisible coordinate plane , most maps on vex vr have a coordinate plane in the back ground that the robot can pull information off of it can see how far it is in relation to the vetrex of the plane so if a robots postion if x=5 and y=5 we know that the postion of the robot is 5 units up and 5 units to the right in relation to the vertex of said plane  

Conditionals : if you have read all the entries up to this point you will often see me using if this then that and maybe if not that then something else that is a conditional in simple terms it is a statment that reqiures specfifc statments to be true that is it .  

Patterns : to know how a patterns effects a robots code we first must know what a pattern is , a pattern is regular repeatable and predictable set of ideas behaviors ect , in coding you will often see that you have to do alot of the same actions those are patterns and luckily for you these are very easy to automate for example if you have to turn right move 200 mm turn left move 200mm and then repeat that if you can see these patterns    
you can take advantage of that and drastically cut down on your code 
## Vocabulary

## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  

This ensures your notes are easy for you (and others) to read later.

Notebook Entry	Terms to Include
VR Robot + Playground : the robot is the thing you control the play ground is the thing you drive around in . 
Programming Language + Project: a programing language is get this the language that code comes in diffrent coding langauges do diffrent things but vex vr is written and based in python a project is just a file with code in it that you write thats it its really really simple .  
Behavior + Command	Behavior, Command
Drivetrain	Drivetrain
Loop + Iteration	Loop, Iteration
Sensor + Bumper Sensor	Sensor, Bumper Sensor
Boolean + Condition + TRUE/FALSE	Boolean, Condition, TRUE, FALSE
Distance Sensor + Threshold	Distance Sensor, Threshold
Coordinate Plane + X/Y Coordinates	Coordinate Plane, X-axis, Y-axis, X-coordinate, Y-coordinate
Location Sensor	Location Sensor
Comment	Comment
Eye Sensor	Eye Sensor
Conditional Statement	Conditional Statement

---

## Headings

**When to use:** Organize your notebook into sections (like days, topics, or projects).  

- `#` for the notebook title (use once at the top).  

- `##` for each day or major topic.  

- `###` for subsections (like "Notes", "Practice", "Reflections").  

# Example:

# My Coding Notebook

## Day 1

### Notes

### Practice

# Text Formatting

When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

# Example:

**Class** = a blueprint for objects  

*Remember:* always test your code  

Use `System.out.println()` to print

 

# Code Blocks

When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

# Example:

```java

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello World!");

    }

}

```

# Lists

When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

# Example:

Define the class
Write the main method
Test your program
Variables

- Loops

- Conditionals

 

# Checklists

When to use: Track progress on assignments or tasks.

# Example:

[x] Complete coding warm-up

- [ ] Finish project draft

- [ ] Reflect on learning

 

# Blockquotes

When to use: Call out notes, reminders, or teacher comments.

# Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

# Tables

When to use: Compare values, track progress, or organize data neatly.

# Example:

| Task        | Status   | Notes          |

|--------------|------------|-----------------| 

| Homework 1  | Done #  | Submitted      |

| Homework 2  | Pending  | Needs review   |

 

# Links & Images

When to use: Add references, resources, or visuals.

# Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

To make an image that is a link, paste the image, then add the following before it, replacing website address with the link:

<a href="website address">

And after the image info, add: </a>

# Collapsible Sections

When to use: Hide solutions, extended notes, or extra details.

# Example:

<details>

  <summary>Click to reveal solution</summary>

  

System.out.println("Answer: 42");

</details>

 

# Footnotes

When to use: Add references or side notes without cluttering the page.

# Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

# Style Rules

Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

# Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.

