# lab-8

Write a description of the problem you’re working on
I wanted to focus on the word counter issue in order to build a text box that counts the number of words in the text when it is filled with text.

What are the variables
a. var count, is a reference to the id of the count
var input, is a reference to the id of the textarea
var text, which keeps track of the user’s input, and
var wordCount, which keeps track of the words  

What are the inputs and outputs of the system?
a. The input is the text that the user types into the text box.
b. The wordCount output indicates the number of words in the text box.

Did you use any data structures?
A for loop 

What is the logic for solving the problem?
 The for loop monitors the quantity of space 
characters in the content box and connects that number with the quantity of words in the content report.

Did you use any formulas?
   Any time the software detected the user entering a space key in the text box between words, I simply increased the value of wordCount.
   
   
 
    <!DOCTYPE html>
    <html lang="en">
    <head>
        < meta charset="UTF-8">
        <META HTTP-EQUIV="x=UA-Compatible"IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1>
        <title>Document</title>
    <head>
    <body>
        <h2>Word Count: <span id="count">0</span></h2>
        <textarea id="input" rows="10"></textarea>
        
        <script src="index.js">  </script>
        
    </body>
    </html>
    
    
    //the counter will update as the user enters text
    <head>


    // the counter will update as the user enter text
    
    var count = document.getElementbyId(' count ');
    var input = document.getElementbyId(' input ');    

     //keyup is fired when user's hands have left a key
     input.addEventListener('keyup", function(e){
