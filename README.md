# Practical6
same for 5,13

setting for Jenkins 
 
 Step 3: Create a new Freestyle Project
Go to Jenkins dashboard → New Item
 
Enter name: LocalCICD
 
Select Freestyle project
 
Click OK
 
 
Step 4: Configure the Job
Scroll to Source Code Management
 
Select None (we are not using Git)
 
Scroll to Build
 
Click Add build step → Execute Windows batch command
 
Enter the following (adjust path if needed):
 
 
cd C:\Users\YourName\jenkins-demo\
javac HelloWorld.java
java HelloWorld
 
Click Save
 
Click Build Now
 
Build History → #1 → Console Output
 
Hello, Jenkins CI/CD!
