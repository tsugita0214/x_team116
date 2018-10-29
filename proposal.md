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
People often have difficulty spending money wisely or knowing what they can afford. It is easy to come up with a list of
things that you want, but knowing what combinations you can actually have is a harder task.

We are proposing a program that would accept a list of items (and corresponding prices) that the user would ideally like to buy.
Our program could sort the items in ascending or descending order, but that is not the only functionality. If the user specifies
a budget, we will be able to help them determine which subset of items they can afford. The user will see all of their items listed on our GUI, and they can click those that they would like to be a part of the subset they can afford. Items that are too expensive to be
added to the "basket" of items will be grayed out. When the user is done selecting the subset of items, they can save the subset for later, or output it to a "shopping list".

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
- Smart Purchase Plannner


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
  - The output #1.
    - One component of the program is to be able to display a list of items in ascending or descending order.
      - example of items list with ascending order of their prices after you put items in the program.
        - a pair of Nike shoes: $100
        - a warm jacket: $150
        - a fast bicycle: $200

      - example of items list with descending order of their prices after you put items in the program.
        - a fast bicycle: $200
        - a warm jacket: $150
        - a pair of Nike shoes: $100


  - The output #2. 
    - A feasible subset of the items the user submitted that fits within their budget. The user could save this subset or output it to a "shopping list".
      - example of a feasible subset
        - Assume the user enters a budget of $300, and enters the same items as above. $100 Nike Shoes, a $150 jacket, and a $200 bike.
        - Further assume they click on the shoes and the bike. The program recognizes that their $300 budget has met, so the jacket is grayed out.
        - The user could elect to save this subset or output it to a shopping list.

        - Your Shopping List:
        - a pair of Nike shoes: $100
        - a warm jacket: $150

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
  - The list of items paired with their prices to make a list.
  - The budget.
    - Example Input:
        - a pair of Nike shoes 100
        - a warm jacket 150
        - a fast bicycle 200
        - Budget: 300

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
Simple GUI with text entry fields for items/prices and the budget. The output on the GUI would be the list of items and prices with checkboxes next to each item. The checkboxes would enable/disable depending on if the item could be added to the subset without exceeding the budget. There would be buttons to save the list or output it as a "shopping list". "X" buttons next to each item in the list would also exist so the user could delete an item. An "arrow" button to sort the list in ascending or descending order would be near the top of the list.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
Name each interface or class and briefly describe its function or purpose.
 - Item.java (Custom): This class will instantiate item objects. It will need to implement comparable to allow for sorting, which will be based on the price. These objects have a name and price. They also have a "selected" field to determine if they are selected by the user when making a basket of items. A more advanced version of this project could see the item class storing more information such as a description field, what store the item is located at, or a priority number for how badly the user wants this item.
 - Storage.java: The items would be stored in BST.
 - Main.java: The main class would need to generate the user iterface. Like the Dorm Designer CS300 assignemnt, existing GUI packages would need to be imported to make this work.
 - Test.java: The test class which tests the Storage class functionality for basic BST operations such as insert, delete, search, get, isEmpty. Also it tests about listing items inside in ascending order and descending order, list the combinations of items that you can get for certain amount of budget.



## Edit and Submit this file and any figures referenced by this document.

