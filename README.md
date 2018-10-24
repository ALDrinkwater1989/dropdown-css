# learning goals
1. to create a simple webpage with a nav bar and a button for a dropdown menu.
2. to create the dropdown menu
3. To style the menu so it looks and acts correctly when hovered over
4. To style the button so that it acts correctly when hovered over
5. To position the list so that it was hidden until the button was hovered over and then transition into the correct place smoothly


## In the HTML file

* We created a nav bar with the class navDefault
* we then created a button call DropDown
* After that we created an unordered list with the class called 
* Within the unordered list we created 4 list elements with the class dropDownItem
* Within these list elements we created Anchors called dropDownLink

## In the css file
* In the css we used the classed we created in the HTML file to set the colour, background color and how we wanted the list to look.
* Once this was done we styled what would happen when we hovered over each list item. we made it invert the font colour and change the background colour to be grey, the same as the nav bar
* We also styled what would happen to the button when it was hovered over, so that it would sutbly change the background colour.
* After that we set the position of the list so the bottom element was sitting on top of the button.
* Once this was done we hid the list under everything else using the z-index tag in the CSS to make it be at the bottom
* We also created a smooth transition animation for the list when the button was hovered over to place the list in the correct position.