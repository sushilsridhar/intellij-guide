# IntelliJ Guide

### Fast Coding

1. Command + N - generate constructor, getter setter    
2. Control + I - overide methods
3. fn + shift + f6 - rename file
4. control + option + o - optimize imports

### IDE Errors

1. Invalidate cache and restart - Incase of IDE errors  
File -> Invalidate caches and restart, this will fix any errors in the project that was caused by IDE.  
(eg. could be a error in pom.xml or dependencies are downloaded, yet IDE shows package not found error when it is imported in the java file)

2. Synchronize - sync with local workspace
File -> Synchronize, synchronize local work space with IntelliJ, incase of switching branch using terminal (the one that is outside of IntelliJ).


### Code

1. Scratch File  
File -> New -> Scratch File, save tryouts or unwanted code temporarily in scratch files, it is not added in version control.
Project Tool Window on left side - switch to Scratches view - to view only scratch files

2. Inspect code - Warnings, spellings errors and code improvements  
right click on the java file, Analyze -> inspect code, to view all the warnings, spelling errors and minor code improvements that can be done.

3. Format xml file or any file  
Code -> Reformat Code, I mainly use it to format xml files, life saver.

4. Optimize the import statements  
Code -> Optimize imports, We can enable this by default for every commit, in the git window. 

5. Navigate to a particular line  
command + L, enter the line number

6. View contents of a class in the same window  
option + space, the contents of the class can be viewed as a pop up, easier to view what's inside a library class (eg: Timestamp class in java)

7. View all methods in a class  
Command + function 12, to see members of the class, useful while analyzing at library classes

8. View method hierarchy  
control + H


### Git

1. Annotate - Find who commited a particular line  
double click on the space where line number of the java file is displayed, select annotate.


### Searching

1. Search by variable or method name  
option + command + O

2. Search by class name  
Command + O

3. Search by file name  
Command + shift + O

4. Search everywhere  
click shift twice (double shift)

5. View Recent files  
Command + E


### Visuals

1. Presentation mode    
View -> Enter Presentation mode, useful for demos

2. Distraction Free mode     
View -> Enter Distraction free mode, enables full screen with only the code in the file visible

3. Increase/Decrease Font size    
Command + shift + A, type font, you can see options to increase/decrease font size

4. Packages and Scratches view  
Project Tool Window on left side - switch to packages view - to view only code related files
Project Tool Window on left side - switch to Scratches view - to view only scratch files

5. Split screen - have two java file side by side   
Double click on the file, select split on right.


### Dashboard

1. Run Dashboard for microservices spring boot  
View -> Tools Window -> Run dashboard, usefull for running/managing multiple microservice spring boot apps


### Debugging

1. Monitor a variable through out the debugging session  
left click on the variable and click Add to watches

2. Access all debug points  
click on favourites tab on left bottom, or left click on the debug point icon and click more 
