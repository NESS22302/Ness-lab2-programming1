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



