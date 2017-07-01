# BigData_Session2_Assignment1
*************
TASK 1 ------->>>>>>>>>

(i) Check whether /user/acadgild directory exists or not in the HDFS.
(ii) If it doesn't exist, then create this, if it exists, then create a directory /user/acadgild/hadoop

SOLUTION FOR TASK 1 ------->>>>>>>>>

Screenshot 1.1 : It shows /user/acadgild directory exists in HDFS.

Screeenshot 1.2 : It lists contents of /user/acadgild directory and since hadoop directory does not exist inside it, therefore, mkdir command creates hadoop directory.

Screenshot 1.3 : It lists /user/acadgild directory which shows hadoop directory is now present inside it.

**********

TASK 2 ------->>>>>>>>>

(i) Create a file in HDFS under directory /user/acadgild/hadoop with name word-count.txt.
Whatever we type on screen should get appended to the file.

SOLUTION FOR TASK 2 ------->>>>>>>>>

Screenshot 2.1 : It shows touchz command creates a zero length file.

Screenshot 2.2 : If we use cat command after touchz command, it shows nothing because touchz creates zero length file, so to add content to the file, appendToFile command is used, which takes input from user and by pressing ctrl + d, we can stop providing the input, now if we use cat command again, it displays contents of file.

***********
