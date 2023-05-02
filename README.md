Download Link: https://assignmentchef.com/product/solved-comp9032-lab-1
<br>
<span style="font-size: 2.61792em; letter-spacing: -1px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">1.  Objectives</span>




In this lab, you will learn




    AVR assembly instructions  basic assembly programming




<h1>2.  Signing in</h1>




You will be working with your lab partner for all lab exercises. When you arrive at the laboratory for the first time, please sign in with your partner.







<h1>3.  Examining the Host Environment in the Lab</h1>




The host environment is a standard personal computer running the Windows operating system. Take a note of the desktop icons. The icons include AVR Studio which you will be using to edit your program, assemble it into the executable file and debug it. Another icon is the AVRDOC folder, which contains AVR Instruction Set Manual, AVR Instruction Set Summary and ATmega Reference Manual. Those documents are also available on the course website. You are encouraged to use these resources for your lab exercises.







<h1>4.  Save Your Work</h1>




The computers in the lab are also used by other students. So when you finish your lab, please save all your work to your USB memory and DELETE all files associated with your lab if you do not want other students to use your files.







<h1>5.  Programming Style</h1>




The general practice, when you write an assembly program, is to maintain the readability and consistency of your code. For this reason, you are encouraged to adopt the following rules, especially for this course:




<ul>

 <li>Starting each source code file with a heading that includes:</li>

</ul>

o your name so that it is easy to see who is responsible for the file, o the date of last modification and a version number, and  o <strong>the description of what the program does, possibly with a pseudocode for a high level abstraction. </strong>

<ul>

 <li>Including appropriate comments that explain the “why”, not just the “how” of the program throughout the source code.</li>

 <li>Using a sensible layout for your code — to make it easy to see the code structures, instructions and any labels.</li>

</ul>







<h1>6.  Tasks</h1>




6.1 Task 1 (for Week2, due in Week 3)




Manually convert the function described by gcd.c below (i.e. calculating the greatest common divisor of two numbers) into AVR assembly code (<em>gcd.asm)</em>. Assume the size of an integer is 1 byte. You need to produce two designs: 1) for minimum code size and 2) for minimum execution time.







int main(void)

{

int a, b;                                       /* Initialized elsewhere */

<sup>                       </sup>                  while (a!=b)

{                                                    /* Assume a, b &gt; 0 */

if (a&gt;b)

<ul>

 <li>= a – b;</li>

</ul>

else

<ul>

 <li>= b – a;</li>

</ul>

}return 0;                                                                 /* a and b both hold the result */

}







Figure 1: Program gcd.c




Assign register r16 to be the C code variable a and r17 the variable b. <strong>Note, do not initialize these registers within your code.</strong> (You should be able to initialize these values in AVR Studio, refer to lab0).




Assemble and run your program in AVR Studio and show your working program to the lab tutor. Remember to save and delete your work before you leave the laboratory.




6.2     Task 2 (for Week 3, due in Week 4)




Write an AVR assembly program that performs the following function

<em>n</em>

<em>sum</em><em>a</em><em><sup>i </sup></em>,

<em>i</em>1

where n and a are 8-bit unsigned integers and sum is 16 bits. <em>Try to minimize the number of registers used.  </em>




Use macro to increase the readability of your program.




Assemble and run your program in AVR Studio and show your working program to the lab tutor.













NOTE:




Each task is worth 5 marks. All your programs should <u>be well commented and</u> <u>easy to read</u>. Up to 1 mark will be deducted for each program without proper and sufficient comments.




Please have your work marked in your lab class of the due week.


