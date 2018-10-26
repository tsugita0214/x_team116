# X-Team 116 Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description
Mr. A has  purchase problem. He buys many tnings that he does not even use once he is out for shopping.
So he decided to make a program where he can put items with their prices in any order.
The program can also print out items in asending order or descending order of price.
On top of that, it can also print out items up to certain amount of money in total in both ascending order or descending order, so that he no longer spends more than what he specifies beforehand.

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
Smart Purchase Plannner


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
### The output #1. 
Items list of what you want to purchase in both ascending and descending order of their prices.
(You specify call the function specifying which order you would like)

#### example of items list with ascending order of their prices after you put items in the program.
a pair of Nike shoes: $100
a warm jacket: $150
a fast bicycle: $200

#### example of items list with descending order of their prices after you put items in the program.
a fast bicycle: $200
a warm jacket: $150
a pair of Nike shoes: $100


### The output #2. 
Items list of what you want to purchase in both ascending and descending order of their prices up to the budget.

#### example of items list with ascending order of their prices after you put items in the program.
(You specify budget and call the function)
The budget is $300:
a pair of Nike shoes: $100
a warm jacket: $150

#### example of items list with descending order of their prices after you put items in the program.
The budget is $300:
a fast bicycle: $200
a pair of Nike shoes: $100

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
- The list of items paired with their prices to make a list.
- The budget.

a pair of Nike shoes 100
a warm jacket 150
a fast bicycle 200

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
Command line interface


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
Data store: AVLTree
User Interface: Main.java which accepts user inputs and call function according to the inputs and gives back output if necessary.


Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

