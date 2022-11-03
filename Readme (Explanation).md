# Java---1-Object-Declaration-Object-Creation-
In this section, we will try about "how to create Object Declaration and Object Creation in Java"

 # Object Declaration
 You can use this syntax
 (class name) (object name);
 
 Example:
  
 JFrame myWindow;
 
 In object declaration what should you do, you must to make sure, always name it your object.
 With valid "identifier", you can create name object.
 The identifier can include set of(alphabet, number, underscore(_), and dollar ($)).
 Remember, the first character, can't with number.
 
 Example:
 
 JFrame myWindow; //VALID IDENTIFIER
 
 JFrame mywindow; //VALID IDENTIFIER
 
 JFrame MYWINDOW; //VALID IDENTIFIER
 
 JFrame my_Window; //VALID IDENTIFIER
 
 JFrame my_Window1; //VALID IDENTIFIER
 
 ________________________________________________________________________________________________________________
 
 NOT VALID : JFrame 1myWindow;
 
 
 # Object Creation
 You can use this syntax:
 
 (object name) = new (class name)([arguments]);
 
 Example :
 
 myWindow = new JFrame();
