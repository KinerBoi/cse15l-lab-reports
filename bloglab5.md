# Part 1

Student Kinish Sathish: Hello, When running the code that we were supposed tgo debug for the Lab this wednedsay, I came across the terminal output of me running the bash file, and came to 
realize that this error came to exist in the file code. However, I am completely confused on what the output is supposed to mean. I am also very much confued on how to edit the file in order to 
fix the bug

<img width="1213" alt="Screenshot 2024-03-12 at 5 32 47 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/21d4b635-975b-4eca-88b5-54ca4447b47d">

<img width="771" alt="Screenshot 2024-03-12 at 4 54 11 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/601ebd3d-ff64-484f-9321-b0369af2d0a9">


TA Bob Smith: Well, thank you Kinish for asking your question! Based on the terminal output, there seems to be a very glaring error in the file stated by the terminal line. To help lead you to fixing
the bug on your own, I will ask you: What is a ArrayIndexOutOfBoundsException? Is there anywhere in the code output that states where the errors of the code are situated? Also, in eiditing the code file,
refresh yourself on VIM terminal ediiting that we went over in class earlier this quarter.

Student Kinish Sathish: Oh yeah, that makes more sense thank you very much! The reason that I got the error would be because of the for loop statement, where I increment until the index equals 
`array.length`. As array indexes start at 0, if we incrememnt to the length of the array (which starts at 1), we will end up trying to iterate to an index which doesnt even exist in the array (and thus 
is out of bounds). This is why the error on line 13 is fixed. And as the code line on line 30 uses the mean method to assign the mean of the array to a integer, before the fix it also got marked wrong.
After fixing the code to `for(int i = 0; i < array.length; i++)` through a VIM editor (<i> to start editing, edit through moving cursor, then  <escape> <:> <w> <q> in order to exit VIM with changes saved)
the code ran well and also printed out the mean (rounded down) and the median of the array in the `File.java` file.

Before fixing the bug:

<img width="624" alt="Screenshot 2024-03-12 at 6 03 52 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/2d1c516b-59d8-46cc-9d0d-161e7ef67f14">

<img width="765" alt="Screenshot 2024-03-12 at 6 04 29 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/0bfdc12c-2fce-482d-9e6c-25d51e134aad">

After fixing the bug:

<img width="1191" alt="Screenshot 2024-03-12 at 6 06 32 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/0c4f5da9-147d-4697-8fcd-6dca0d333825">

<img width="423" alt="Screenshot 2024-03-12 at 6 06 56 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/a88016d4-52ee-4432-81eb-589ec67b0fab">

File Structure: 
/Users
    /kinishsathish
        /downloads
            /lab5
              - File.java
              - File.class
              - test.sh
              
<img width="780" alt="Screenshot 2024-03-12 at 6 08 27 PM" src="https://github.com/KinerBoi/cse15l-lab-reports/assets/87410075/7a0b4a68-9afe-4131-849b-9fd3a0c0cbc5">

Part 2:

For the first time, I learned about VIM. I thought that it was really cool that one can edit a file through terminal without even having to go through the file physically is pretty cool in my opinion. 
The ability to create directories and files through terminal through the `touch` command I thought was pretty cool, where instead of just navigating and editing files we can also create them. Essentially, 
the entire idea of being able to do a lot of things through the command line, even logging into the UCSD computers virtually seemed really cool where one didnt need to actually see interface in order 
to perform functions. 




