# library_EDA
Exploratory Data Analysis & Implementation/Testing of New Features

Contains an IPYNB file, x3 CSV files (books.csv, bookloans.csv & members.csv) as well as examples of the generated JSON files.

Tasks outlined in the .ipynb file are outlined again below:

1. 
'Provide code that will allow a member to borrow a book, recording the results as a new bookloan. 
You can provide both Book and Member classes with a method scan() which will return the id of an instance of each respectively. 
Do not worry about representing a membership card. Cards can be an attribute of Member.
Use dummy data to test the code and state the preconditions and postconditions of the operation in a docstring.'

2. 
'Provide code that will allow a member to return a book, again ensuring that necessary data is stored. 
Test the functionality with appropriate dummy data and again provide pre and postconditions as a docstring.'

3.
'Provide functionality that will allow a member of the public to apply for membership. This will involve the storage of information on the membership request. 
Each day, a list of new member details is sent to an external print company who produces membership cards. Cards are delivered to the library approximately three days later, when the membership card number is recorded. 
The format of the card number is made up of the membership number followed by a single digit indicating the sequence number of the card associated with the member. 
1 means the first card issued to the member, 2 the second and so on. There is an obvious flaw here, but you can ignore it for purposes of the exercise.'

4.
'Provide functionality to allow a member to reserve a book. Assume that they have the number of the book available. 
This will require permanent storage as it may be some time before a book becomes available.'

5.
'Using appropriate patterns, implement a notification system along the lines described in the Preamble to this assignment. 
You can assume that all notifications are sent by email, providing a test sendEmail() method which merely prints to the console the message passed as an argument.
Test the system and show or describe how it is capable of coping with the situations described in the preamble and how it might be sufficiently flexible to deal with future notification requirements.'
