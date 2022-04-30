# JUnit4 .jar Files

## Instructions
1. Download the repo .zip to your local machine
2. Unzip the file
3. Move the new folder's contents to your project folder
4. In Intellij, under 'File', click on the 'Project Structure' selection
5. in the left column, select 'Libraries'
6. At the top of the center column, click on the '+' icon
7. Select 'Java' in the pop-up window
8. Use the pop-up window to navigate to the location of the new folder you previously moved into the project folder
9. Select both files and click on 'Open'
10. The files should appear in the right column and a new file in the center column named 'junit-4.13'
11. Click the 'Apply' button and then the 'Ok' button
12. In your project folder or module folder, create a new directory called 'test'
13. Right click on the new 'test' folder and on the bottom of the pop-up window, select 'Mark Directory As', then in next pop-up window, click on 'Test Sources Root'
14. Reopen the 'Project Structure'
15. In the left column, select Modules and in the right column and ensure the checkbox to left of 'JUnit4' is checked and 'Test' is selected in dropdown menu to the right 
16. Click the 'Apply' button and then the 'Ok' button

### Test Files
1. For each of your Java Classes, right click on the Class name and in the pop-up window select 'Generate...', then in the new pop-up window select 'Test...' 
2. In the 'test' folder, if the Class was in a package, a same named package will have been created with a Class of the same name, except the name appended with 'Test'
3. You can now create test methods with in the -Test Class to test the methods from the Java Class to ensure they perform as expected
