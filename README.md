# face_recognition_system

Step 1 : Download and Install latest version of python and visual studio code

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Step 2 : Download and Install latest version MySQL (While installing on the first page choose full download)

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Step 3 : Extract the project zip file

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Step 4 : Install Following Packages from cmd (Copy and paste following command in cmd prompt) :

pip install numpy Pillow tk pandas opencv-python opencv-contrib-python mysql-connector-python cx-Freeze

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Step 5 : Open the extracted folder with visual studio code

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Step 6 : Change the password of MySQL Connection

- Click on Search from Side Bar on Visual Studio Code
- Search for "BlackBerry@0314" and below it put the password that you had already entered while installing MySQL.
- Click on replace option which is the icon beside the textbox where you just entered your MySQL password.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Step 7 : Open MySQL Workbench and create a new schema with name "face_recognition".

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Step 8 : Import Database files

- Select Server from the menu.
- Click Data Import and choose the import option as 'Import from Self-Contained file'
- Select the database file named 'register' which is located in project folder inside database folder
- Select the Default Target Schema as face_recognition from the drop-down arrow
- After doing all click on import
- After successfully importing register database file do the same for student database file

------------------------------------------------------------------------------------------------------------------------------------------------------------------

You have successfully completed the setup for the Face Recognition and Motion Detectio using OpenCV now feel free to run the project from visual studio code (The main file of this project where the system start from is 'Face Recognition Software.py').

------------------------------------------------------------------------------------------------------------------------------------------------------------------
