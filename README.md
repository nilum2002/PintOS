Here I only Uplaoded the Threds folder **(src->threads)** . <br>

So please refer the lab introduction pdfs for Pint os installation. <br>
      01. Insall the pint os - [pdf-link](https://github.com/nilum2002/PintOS/blob/master/labpdf/OS%20Prerequisite%20-%20Installing%20Pintos%20OS.pdf)<br> 
      02. Lab Task - [pdf-link](labpdf/Interactive_Shell.pdf)<br> 

These are the steps I used to buid the "Interactive Shell" in Pint os:<br>

First of all I was so confused where I was at start...! <br>
It's simple. I start with the thinking of character by charater. So I make a buffer to store each charater one by one as the input of the user and and print caharaters one by one in one line. Then, When we hit enter the program will undersand the my command and execute it. First you have to understand,we will have to deal with mainly with enter and backspace charaters in the key board.
So the the function 

            int ch = input_getc ();
return a integer value to the relevent keyboard key. 
Then we compare with that integer value with '\r' , '\n' and '\b'(automaticallu converted in to integers... see the code)for get our desired outcome...
For string compare I used the funcition 

      int strcmp(const char *str1, const char *str2);
      
which comes with the <stdio.h> libaray. 



To get start:

      $ make 
      $ pintos --


Good Luck ... ! 
