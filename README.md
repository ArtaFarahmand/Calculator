# Calculator

### Purpose and Description 
 I have created a calculator as a demo program to demonstrate rapid application development using 
Java Swing GUI and how Java Bean Context API work.


This program uses a Graphical User Interface (GUI) based on Frames to interact with the user.
The program includes a text field, a series of button for the numbers and series of buttons to 
perform the various calculation operations.


 *This program uses the Java Swing API for GUI programming, and requires the*
 *Sun Java SDK version 8.1 or better.*
 
 * Compiling and running instructions
 * Assuming SDK 1.3 (or later) and the CLASSPATH are set up properly.
 * Change to the directory containing the source code.
 * Compile:    javac Calculator.java
 * Run:        java Calculator
 * Document:   javadoc Calculator.java

 ### Classes

public class Calculator extends javax.swing.JFrame
This is the main public class for this application. It extends (inherits from) JFrame
to provide access to Java Swing Frame methods for the GUI.

private class TextFieldHandler implements ActionListener 
Class TextFieldHandler implements ActionListner to provide the event handling
for this application.  It is a private inner class, which gives it access to 
all of the GoodDocs instance variables

 ### Calculator Methods

* txtDisplay()
* public static void main(String args[]) 
* This method is used to execute the application
   * btnOne, Two, Three, Four, Five, Six, Seven, Eight, Nine and Zero 
   * these button method are used to obtain values that are going to be used for 
   * the calculation

 * btnPlus, Subtract, Division, Multiply and Clear 
 * are used to perform the various calculation operation displaying the results 
 * of the calculation on txtDisplay.

 ### TextFieldHandler Methods

public void actionPerformed(ActionEvent event)
This method is required for an ActionListener to process the events
 
 ### Calculator Instance Variables

 * private JTextField to display the results of the calculation.
 * private JButton to obtain calculation values from users and perform various math operation
