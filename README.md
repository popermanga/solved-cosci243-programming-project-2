Download Link: https://assignmentchef.com/product/solved-cosci243-programming-project-2
<br>
5/5 - (1 vote)

Your goal is to implement an application that reads a file, modify its content, and writes the modification back to the same file. The file includes 3 lines of integers. The first line indicates the number of integers on the third line. The second line indicates which integer on the third line has been selected (active). And the third line lists all the integers (maximum of 10).

Your application should have a menu that is constantly displayed on the screen (see the menu below). Right below the menu, the program should display list of all integers in the file (third line). Also it should show which integer is currently selected (active).

The user should be able to select a menu item by entering its associated key or by pressing one of the indicated extended keys on the keyboard.

“Select Down” selects the next item in the list. If the last item is selected, this option selects the first item in the list. “Select Up” selects the previous item in the list. If the first item is selected, this option selects the last item in the list.

“Move Down” moves the selected item one position down. If the last item is selected, moving down will not be possible. “Move Up” moves the selected item one position up. If the first item is selected, moving up will not be possible.

“Insert” will insert an integer before the selected item and makes the newly inserted item active. The integer is typed by the user. If the list is full, insertion will not be possible. Do not accept incorrect values.

“Delete” deletes the active item.

“Sort” sorts the list in ascending order. The active item after the sort is same as the active item before the sort.

“Jump from” changes the color of the active item so it can be moved to new location. “Jump to” moves the colored item to new active location. “Cancel Jump” turns of the color and disables moving to new location.

“Exit” ends the application.

Make sure to use the top-down design to break your program to many simpler tasks (at least one function per task). Do not use global variables. Make sure to check the special cases. Example: list is full or list is empty.

Your program should copy the content of the file into an array and variables when you start the program. The program write back the content of the array and variables into the file when you exit the program. When you are using the program, you should modify the array and variables and not the file.

Make sure to test your program completely before submission. Do not forget to add comments. Submit your well-documented C++ program via Canvas.

Menu:

Select Down …. “1” or “Down Arrow” key

Select Up …… “2” or “Up Arrow” key

Move Down …… “3” or “Page Down” key

Move up …….. “4” or “Page Up” key

Insert ……… “5” or “Insert” key

Delete ……… “6” or “Delete” key

Sort ……….. “7” or “F2” key

Jump from …… “8” or “Right Arrow” key

Jump to …….. “9” or “Left Arrow” key

Cancel Jump …. “q” or “Esc” key

Exit ……….. “x” or “F1” key