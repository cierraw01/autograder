# autograder
Autograde students' assignments

## Files in your directory
* Trial zip folder of student assignments from Blend **290224_Library_submission.zip**
* If the assignment takes in a txt file to read **demo.txt**
* Java file to print the classes and methods **ReflectionClassesMethods.java**
* Java file to run the student's main method **ReflectionMainMethod.java**
* Java file to run extra tests for the student's program **ReflectionDemoTests.java**

## Main.java


## Submission.java
* Field **String studentName**
* Field **String directory**
* Field **ArrayList<String> files**
* Class constructor **Submission()**
* Method returns void **setStudentName(String n)**
* Method returns void **setDirectory(String n)**

## JarTasks.java
* Method to print files in current directory and returns void **listDir()**
* Method to print files in a zip folder and returns void **zipList()**
* Method given String of zip folder of student assignments **String zipFilename** to separate each student's files into their own subdirectory named **[StudentName]_dir**  and returns arraylist of objects of student submissions **ArrayList<Submssion>** **zipBurst(String zipFilename)**
* 
