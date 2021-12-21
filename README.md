# Module 3 Lab Guide (part 1)
## Getting Started
[Lab Introduction Video](https://youtu.be/ia9fwrAmMHs)  
[Code Style and Code Quality Requirements Video](https://youtu.be/LgCIyZesyig) 

### Code Style Requirements
Please review the [CS121 Style Guide](https://docs.google.com/document/d/1LWbGQBKkApnNAzzgwOSvRM03DmhYWx5yEfecT2WXfjI/edit?usp=sharing) and apply it in all lab activities and projects this semester. Coding Style will assessed as part of your lab and project grades.

### Code Quality Requirements
- Code must compile without warnings using openjdk11
- Code must run without errors or warnings on safe-path and edge test cases
- More to come as we learn about input validation and exception handling
## Lab Warmup - AccountGenerator (Required)
[Walkthrough Video](https://youtu.be/KjMb8Qth3dM)
### Problem Description
Write an application that prompts for and reads the user's first name and last name (separately) using a Scanner. Then print a string composed of the first letterof the user's first name, followed by the first five characters of the user's last name, followed by a random number in the range of 10 to 99. All letters should be converted to lowercase before being displayed. Assume that the lastname is at least five letters long.  Similar algorithms are sometimes used to generate usernames for new computer accounts.  Your program should match the expected output below, except with a different randomly generated number. 

#### Expected Program Output (with sample user input)
```
Enter your first name: Luke
Enter your last name: Hindman
Username: lhindm83
```

### Implementation Guide
1. Expand the folder named AccountGenerator and create a new file named AccountGenerator.java
2. Design a program to satisfy the requirements in the Problem Description and enter the program code in AccountGenerator.java
3. Test the program with the sample user input using the run link above the main method
4. Commit the changes to your local repository with a message stating that Lab Warmup is completed.
5. Push the changes from your local repository to the github classroom repository.



## Lab Activity 1 - SphereCalculator (Required)
### Problem Description
Write an application that reads the radius of a sphere from the user using a Scanner and prints its volume and surface area.  Use the following formulas, in which r represents the sphere's radius.  Print the output to four decimal places using the %f format specifier with the printf() method presented in the reading.  Your program should match the expected output below.

<img src="images/volume-and-surface-area-formula.png" alt="Sphere Formulas" width="350">

#### Expected Program Output (with sample user input)
```
Enter the sphere's radius: 150
Volume: 14137166.9412
Surface area: 282743.3388
```

### Impementation Guide
1. Expand the folder named SphereCalculator and create a new file named SphereCalculator.java
2. Design a program to satisfy the requirements in the Problem Description and enter the program code in SphereCalculator.java
3. Test the program with the sample user input using the run link above the main method
4. Commit the changes to your local repository with a message stating that Lab Activity 1 is completed.
5. Push the changes from your local repository to the github classroom repository.

## Coding Journal (Optional)
Keep a journal of your activities as you work on this lab. Many of the best engineers that I have worked with professionally have kept some sort of engineering journal. I personally packed notebooks around with me for nearly 8 years before I began keeping my notes electronically.   

Your journal can track ideas, bugs, cool links, code snippets, shell commands, rants, or simply a reflection on what worked well or not-so-well with this lab activity. I will not be grading the content of your journal, but I will expect at least two timestamped journal entries of at least a 75 to 150 words each added to the provided Journal.md file.  The purpose of this component is to help develop the habit of taking notes and creating documentation while you code. The more detail you provide the better as that will help you if you ever need to refer back to this project in the future.

## Markdown Resources
Markdown is a notation that is used to format text documents.  It is widely used in Software Development shops around the world, which is why we're asking you to use it in your lab documentation.  

Github provides a guide for getting started:  [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
