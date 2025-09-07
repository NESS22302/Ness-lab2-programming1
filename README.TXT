Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.


anwser to questions

2. What value is returned if you get the machine’s balance after it has printed a ticket?

the value returned is 0.

5. Create another ticket machine for tickets of a different price; remember that you have to supply this value
when you create the machine object. Buy a ticket from that machine. Does the printed ticket look any
different from those printed by the first machine? If so, what is different?

##################
# The BlueJ Line
# Ticket
# 5 cents.
##################

##################
# The BlueJ Line
# Ticket
# 10 cents.
##################

##################
# The BlueJ Line
# Ticket
# 50 cents.
##################

##################
# The BlueJ Line
# Ticket
# 1000 cents.
##################

the only thing that has changed is the number of money example in one it says 5 cents in another is says 10 cents that is the main difference.

6. Write out what you think the outer wrappers of the Student and LabClass classes might look like; do
not worry about the inner part.

public class Student
public class LabClass

7. Does it matter whether we write public class TicketMachine or class public TicketMachine in the outer
wrapper of a class? Edit the source of the TicketMachine class to make the change, and then close the
editor window. Do you notice a change in the class diagram?
What error message do you get when you now press the Compile button? Do you think this message
clearly explains what is wrong?
Change the class back to how it was, and make sure that this clears the error when you compile it.

yes it matters. when you change the outer wrapper from public class TicketMachine to class public TicketMachine the code shows a error.
if you close and press compile it brings you to the editor and shows you what the error you wrote is and you need to change it back to what it was before you changed it.

8. Check whether or not it is possible to leave out the word public from the outer wrapper of the
TicketMachine class.

it is possible to leave out the word public from the outer wrapper of the TicketMachine class.

9. Put back the word public, and then check whether it is possible to leave out the word class by trying to
compile again. Make sure that both words are put back as they were originally before continuing.

it does the same thing as number 7.

10. From your earlier experimentation with the ticket machine objects within BlueJ, you can probably
remember the names of some of the methods – printTicket, for instance. Look at the class definition in
source code and use this knowledge, along with the additional information about ordering we have given
you, to make a list of the names of the fields, constructors, and methods in the TicketMachine class.
Hint: There is only one constructor in the class.

price ballance total is fields of TicketMachine.
the constructors of the TicketMachine is: TicketMachine.
the methods in TicketMachine is getPrice getBalance insertMoney.

11. What are the two features of the constructor that make it look significantly different from the methods
of the class?

the 2 main features is that the name of the constructor will alaway be the same as the class name and theres no return type.

12. Given that the type of the price field is int, what do you think is the type of each of the following fields? anwsers is in ()

private (int) count;
private (Student) representative;
private (Server) host;

13. What are the names of the following fields? anwsers is in ()

private boolean (alive);
private Person (tutor);
private Game (game);

14. From what you know about the naming conventions for classes, which of the type names in Exercises
2.12 and 2.13 would you say are class names?

Student Server Person and Game.

15. In the following field declaration from the TicketMachine class private int price; does it matter which
order the three words appear in? Edit the TicketMachine class to try different orderings. After each
change, close the editor. Does the appearance of the class diagram after each change give you a clue as to
whether other orderings are possible? Look at any error messages that the editor shows you by moving
the cursor over the error indicator. Make sure that you reinstate the original version after your
experiments!

yes identifier expected is the error when i put int after price. same thing is said when int is put as the first word.
when private is at end it says both expected ; and illegal start of type. other ordering are not possible.

16. Is it always necessary to have a semicolon at the end of a field declaration? Once again, experiment via the
editor. The rule you will learn here is an important one, so be sure to remember it.

it is alwasy necessary to have a semicolon at the end of a field.*** important to remember ***

17. Write in full the declaration for a field of type int whose name is status.

private int status; is the anwser.

18. To what class does the following constructor belong? public Student(String name)

anwser is Student.

19. How many parameters (inside the parentheses after Book) does the following constructor have, and what are their types?

public Book(String title, double price) Book is the constructor and String is the type. there are 2 parameters.

20. Do you think the values of the constructor’s parameters will need to be stored somewhere persistent? Can
you guess what types some of the Book class’s fields might be, from the parameters in its constructor?
Can we know anything for sure about the names of its fields?

no. the types are price and number of books. the name of its fields are anything after book.

21. Suppose that the class Pet has a field called Name that is of type String. Write an assignment statement
in the body of the following constructor so that the name field will be initialized with the value of the
constructor’s parameter.
public Pet(String petsName)
{
 ...
}

there is 1 parameter.*******

22. Challenge exercise The following object creation will result in the constructor of the Date class being
called. Can you write the constructor’s header? Try to give meaningful names to the parameters.
new Date("March", 23, 1861)

my anwser is new Date("January", 1, 2026) New Years

23. Compare the header and body of the getBalance method with the header and body of the getPrice
method. What is the one difference between the headers and the one difference between the bodies?

the names of the headers and the body each read different files.

24. If a call to getPrice can be characterized as “What do tickets cost?” how would you characterize a call to
getBalance?

how many tickets are there.

25. If the name of getBalance is changed to getAmount, does the return statement in the body of the
method also need to be changed for the code to compile? Try it out within BlueJ. What does this tell you
about the name of an accessor method and the name of the field associated with it?

in BlueJ when changed and then compiled there is no error to the code it is the same as it was before.

26. Add the getter method getTotal to the class TicketMachine to return the value of the total field. Check
that you have done this correctly by calling the method when there are different amounts in the total
field.

no error is shown.

27. Try removing the return statement from the body of getPrice. What error message do you see now when
you try compiling the class?

when removing the return statement and compiling it it shows error and says not a statement.

28. Compare the method headers of getPrice and printTicket from the TicketMachine class. Apart from
their names, what is the main difference between them?

each body does a different code ones prints one shows the price without printing the other prints everything.

29. Do the insertMoney and printTicket methods have return statements? Why do you think this might be?

no. because actions dont return a value.

30. Create a ticket machine with a ticket price of your choosing. Before doing anything else, call the
getBalance method on it. Now call the insertMoney method and give a non-zero positive amount of
money as the actual parameter. Now call getBalance again. The two calls to getBalance should show
different outputs, because the call to insertMoney had the effect of changing the machine’s state via its
balance field.

yes the ballance number changes when the insert money changes depending on how much the cost of a ticket is.

31. Complete the body of the following method, whose purpose is to add the value of its parameter to a field
named score.
/**
* Increase score by the given number of points.
*/
public void increaseScore(int points)
{
// TODO: Increase score by the value in points.
}

******

32. The addCredits method is from the Student class in the lab-classes project from Chapter 1:
public void addCredits(int additionalPoints)
{
credits += additionalPoints;
}
Is the addCredits method a mutator/action? If so, how could you demonstrate that with a Student object? Try
it out.

yes. by adding the amount of homework the student has to do.

33. Complete the following method, whose purpose is to subtract the value of its parameter from a field
named price.
/**
* Reduce price by the given amount.
*/
public void discount(int amount)
{
// TODO: Subtract amount from price.
}

******

34. Write a setter method for a field called age which is of type int. Give the parameter the name
currentAge.

setAge currentAge. ******

35. Write a setter method for the following field:
private boolean alive;

******



