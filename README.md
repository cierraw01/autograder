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
* Method adds String file to **ArrayList<String> files** and returns void **addFiles(String f)**
* Method returns **String studentName** **getStudentName()**
* Method returns **String directory** **getDirectory()**
* Method returns String [studentName] - dir :[directory]: files :[files.get(0)], [files.get(1)], ..., [files.get(n)] **toString()**

## JarTasks.java
* Method to print files in current directory and returns void **listDir()**
* Method to print files in a zip folder and returns void **zipList()**
* Method given String of zip folder of student assignments **String zipFilename** to separate each student's files into their own subdirectory named **[StudentName]_dir**  and returns arraylist of objects of student submissions **ArrayList<Submssion>** **zipBurst(String zipFilename)**

## ProcessLab.java
* Method given String name of text file and returns String of the text file's content **getTemplate(String file)**
* Method given name of directory **String stringDir** and name of java file to run **String mainFile** and returns String output of the java file **getSubmissionOutput**
* Method given two Strings of names of text files and returns boolean value of comparing their content **getComparison(String template, String mainFile)**
* Method to move a copy of a file into each student's subdirectory after given ArrayList<Submssion>, Path of file, and String name of file and returns void **moveFileIntoSubdir(ArrayList<Submission> labs, String fileSrc, String fileRefl, Path src, Path srcRefl)**
