# Lab Report 4
By Kinish Sathish

Step 4)

<img width="695" alt="Screenshot 2024-02-27 at 5 14 15 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/04ac8c3a-fa93-4148-9ddf-4057a6fa8c29">
<img width="565" alt="Screenshot 2024-02-27 at 5 15 09 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/201143b0-9a16-4925-aae6-e005dd908f4b">

The command I used to log into the ieng6 computers that UCSD uses `ssh kisathish@ieng6-201.ucsd.edu`. By doing so, I log into my personal ieng6 server set up earlier in this quarter. the -201 is to log into the 201 computer in particular, because that is the computer server that we have been using throghout this quarter. 



Step 5)

<img width="697" alt="Screenshot 2024-02-27 at 5 16 53 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/d1f9368c-2994-4d07-b9b8-0dc66d8cd10d">

The command I used to clone the repository after forking it to my own repository would be `git clone git@github.com:KinerBoi/lab7.git`. This in turn made sure that I had my own version of the repository to make edits on, like eventually editing the `ListExamples.java` file.

Step 6)

<img width="613" alt="Screenshot 2024-02-27 at 5 17 58 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/4f8bb489-cd1f-4361-a84c-03e9646ab899">

The command that I used in the compiling and running the tests would be `bash tests.sh`. This command essentially uses bash script to combine all the commands needed to run the tests into one `.sh` file and then run them using the bash command. Through the terminal output, it is clear that one of those tests have failed and that we need to fix that. 

Step 7)

<img width="392" alt="Screenshot 2024-02-27 at 5 23 50 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/9af809bb-31af-4595-b643-f91239e3a2d9">
<img width="714" alt="Screenshot 2024-02-27 at 5 22 27 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/cfc80fbb-0cab-4b0e-be1f-cdb08b760a9b">
<img width="634" alt="Screenshot 2024-02-27 at 5 32 52 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/d8e60666-c04a-4b39-bf91-0e53480812b8">

The command that I use to be able to edit the `ListExamples.java` file would be `vim ListExamples.java `which pulls up the file into a eidtable format. To actualy edit the file, I bring the cursor to the part where I want to edit, enter the <i> key to actually start editing, change the variable `index1` to `index2` as the instructions tell me to do so, and then to save my changes I hit the <escape> key and subsequently hit the <:><w><q> keys to save my work and exit the java file.

Step 8)

<img width="361" alt="Screenshot 2024-02-27 at 5 36 09 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/8ed65ad4-605b-415d-9f49-458ea668bf21">

To rerun the commands, I press the <up> key on my keyboard until I have command-line for the bash script used in Step 6, and then rerurn the command. By seeing that all the tests pass, I know that the error has been fixed and my changes to the `ListExamples.java ` file have been saved.

Step 9)

<img width="533" alt="Screenshot 2024-02-27 at 5 39 47 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/95dc27ff-3968-4195-bab2-0e1425c37520">

To commit and push my changes (to make them official in my repository), I use the command `git add .` in order to ready up all the files that were changed, and prepare them to be committed. To committ them, I use the command `git commit -m`, with a little message at the end in quotation marks to mark what change I am exactly making. To finaly push these changes to the repository, I use the `git push` method.

