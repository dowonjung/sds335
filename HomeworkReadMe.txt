Homework #1

This homework is due before the start of class 9/18/18. Any homework submitted after 1:59pm will be considered late and will recieve a 0. Please see the screenshot on Piazza for instructions on how to submit a copy of this file via Piazza for grading. 


Tasks: 
1.) Copy this homework directory, to your own directory using a method of your choice. Please provide the steps you used to copy the file here: 

$ scp -r /work/03658/vtrue/stampede2/unix_tutorial/homework $HOME

2.) Answer the following with bash commands. Provide both the command you used as well as the answer:
        a.) How many lines are in the file  $ wc -l Homework1.txt, 705 lines
        b.) How many times the word "dog" appears $ grep -oi dog Homework1.txt|wc -l, 5 times 
        c.) What line does the word "elementary" appear on  $ grep -ni elementary Homework1.txt, 80
        
3.) Let's add more chapters to Homework1.txt. How would I add the text from Chapter3.txt? Give the exact command you used..
 
$ cat Chapter3.txt >> Homework1.txt

4.) Now, change the name of Homework1.txt to Hounds.txt. Give the exact command you used.

$ mv Homework1.txt Hounds.txt

5.) Use a single command to create a new, sorted file called nights.txt which contains all the lines from Hounds.txt that have the word "night" in them. 
    a.) Give the exact command you used.
    
    $ grep -i night Hounds.txt > nights.txt

    b.) What is the last line of the new file? 
    
    It was the night before he made his departure for London.
