# Dice-Rolling-Simulator-using-Python-GUI
A Dice simulator is a computation model which can be made by software programs. In this, the user rolls the dice and a random dice number is displayed on the screen.
It works just like the common dice. We can create a dice simulator in many ways using Different Programming Languages.

We are going to create a Dice Simulator using Python using two methods. 
In First method , We will see a simple program which represents the dice simulator. 
In the Second Method , We will implement it through the Python GUI.

### METHOD 1 : Simple Python Program
 #### Import Random Module
 Random Module is an In-Built Python Module which is used to generate Random numbers.
 #### Use Loops
Now, We will use the while loop since we need to roll a dice continuously. For conditions being true , we will print the above statement. Here, We will ask for the input from the user to select between ‘y’ and ‘n’.

#### Conditional Statements
If the user enters the choice as ‘y’ , then a random number will be generated between 1 and 6. Then , we will print the number.

Randint () function : It is used to generate a random number between a given range.

If the user enters the choice as ’n’ , then the loop will break and the program will be terminated. Else part will be executed and it will print ‘Exit’.

#### NOTE : Second print statement is used to show the separation between lines.
![whole](https://user-images.githubusercontent.com/68411214/180997279-c5e0d8d6-7443-4440-84f6-51f7198efebd.png)

![output](https://user-images.githubusercontent.com/68411214/180996112-e1bb50d6-1a51-48f2-9377-9cf5bc3489c2.png)

#### REFER Program : " Simple Python Program for Dice Simulation



### METHOD 2 : Dice Simulator using Python GUI

In this we will use Tkinter to create a Dice Simulator Python GUI.

User needs to click on the roll button and it will generate a random number between 1 and 6.

##### Tkinter : it is a Python Graphical User Interface Library which is used to create GUI apps in a fast and easy way.

To install Tkinter in your system , use the pip install tk command in the Command Line interface or any Python IDE.
Now that Tkinter is installed , Let’s begin.

#### Import Tkinter and Random Package
Random Module is an In-Built Python Module which is used to generate Random numbers.

#### Creating the GUI
Firstly we will create a root widget. Root Widget is a window with a title bar and other decoration provided by the window manager.

##### Geometry () : This method is used to set the dimensions of the Tkinter window and is used to set the position of the main window.

##### Title() : It denotes the name assigned to the tkinter window.

##### Label() : It is a widget that is used to implement display boxes where text or images can be placed.

#### Creating a function
The function dice_roll is used to select one of the values between 1 and 6 and then print it.

##### value : It stores all the unicode values for the face of the dice.

##### res : it stores a random number value from value

##### Config() function: it used to change the text on a label.

##### pack() function : It organizes widgets in blocks before placing them in the parent widget.

#### Creating a Button
The Button widget is used to add buttons in a Python application. When it is pressed it performs sets of functions.

##### mainloop() : It is an infinite loop used to run the application, It waits for the process to take place and performs the actions until it is not closed.

### output
![op](https://user-images.githubusercontent.com/68411214/180996927-10fa1069-ed80-4b39-a5a3-fbb47985b916.png)
![SNAP](https://user-images.githubusercontent.com/68411214/180997183-e2b00cb6-fb06-4e4e-b5a3-fd0732e4fb35.png)


#### Conclusion
We have learned about making the Dice Simulator using python. We implemented it by using two approaches , first by understanding the logic and proceeding in the form of a simple python program.

Secondly we implemented it through tkinter , a Python GUI Library in which we used different widgets and random functions. We also implemented unicode strings for the dice. Now we can play board games even if there is no physical dice.

Cheers !
