# Exam_details
Algorithm to find the difficulty of the question.
  To Start with, Question are of 4 types. Listing it below,
  1. MCQ
  2. Fill-ups
  3. Programming
  4. Match the following
 Students attend the questions in the online examination and depending the students capability the code categorize whether the difficulty of the question is Easy, Medium or Hard.
 
 
 PSEUDOCODE:
 // This code is full of JAVA and OOPS
 
 6 Custom Classes are defined
 
 Main Class:
 
 Get the type of question as input 
 
 do..while loop starts to get repeatedly the input until user wants
 
 Pass it into switch case
 
 Display details of the Student with the help pf DetailsOfStudent Class
 
 Depending on the type of Question separate classes executes their function
 
 Counter variable is used for noticing number of Students attended the test
 
 MCQ Class, Fillups Class, MatchIt Class, Program Class:
 
 All classes executes same operation but the type of input differs
 
 ArrayList is used to store the question 
 
 Map corresponds to the CORRECT, INCORRECT, NOT_ATTEMPTED category
 
 static map is created and used for finding the difficulty level of question
 
 Counter variable plays a major role in difficulty of question
 
 Hard is assigned when value becomes less than or equals to 0
 
 
