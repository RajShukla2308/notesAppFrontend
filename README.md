# notesAppFrontend

This Repository includes front end code for NotesApp

Steps for making the code work:

1)Make a folder of your choice in  your desktop, open this folder in visual studio code , right click on the folder and press 'Open in terminal'.

2)In the terminal , type 'ng new notesapp';

3)it will install all the dependencies for the project including 'node modules' folder.

4)Change the 'src' folder of project with downloaded 'src' folder.

5)Go to app folder, open it with terminal and type the command 'ng serve --o'. It will launch the project

 Note - a) If css or bootstrap is not working , open angular.json file and add the dependency "../node_modules/bootstrap/dist/js/bootstrap.min.js" in scripts property.
        b) open src folder , add the following command in styles.css ==  @import "~bootstrap/dist/css/bootstrap.css";
