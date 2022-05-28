# User-Interface-Specification-Document
 user interface specification document in English for the user management screen

- Requirements

Ability to add new User with rectangle shape +New User button on the top left of the page 

Ability to save user with rectangle shape Save User button on the top right of the page

Ability to hide disabled user with tick button that writes 'Hide Disabled User' 
right to the button

Right half of the page should include New User header row and below that there must be four input rows, one select row and one tick button one under the other.

Left half of the page should include an SQL like table which shows the users and information about them

 - Details 

new User with rectangle shape +New User button on the top left of the page 

rectangle shape Save User button on the top right of the page

tick button that writes 'Hide Disabled User' 
right to the button

New User header row, below that four rows for inputs, below these one select row, below that one tick button at the right half of the page

First input row   Username: Input

Second input row   Display Name: Input

Third input row    Phone: Input

Fourth input row   Email: Input

Selection row      User Roles:  Guest or Admin or SuperAdmin

Tick button      Enabled:  tick square or not

 SQL like table which shows the users and information about them at the left half of the page
 
 Attributes of first row of table    ID   User Name    Email     Enabled  
 
 First Column is ID Column which starts with 1 and increase one by one as more users added
 
 The other columns show input taken from user as output
 
 Enabled Column shows the results as true or false
 
 - Beginning of the program
 
 At the beginning of the program, users are only able to see the +New User button, Hide Disabled User button and Save User button at the top of the page. 

- Behaviour of the page

1- '+New User' button is clicked 

2- Input section at the half right of the page shows up.

3- After the inputs given, user roles chosen and enabled button ticked or not, the user click 'Save User' button 

4- Table that contains inputs of the new user shows up at the left half of the page. If 'Hide Enabled User' button is ticked 
then only enabled button ticked users' information will be shown in the table. If 'Hide Enabled User' button is not ticked all of the users will be shown
in the table whether enabled button ticked or not during filling the input section.

5- Input section at the half right of the page disappears.

6- Go to the first behaviour and Loop




 



  
