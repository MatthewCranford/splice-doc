
<!-- A sentence explanation of what the topic/function
 does without being overly technical -->

Splice provides an easy way to modify the contents of an array from any designated index. 

<!-- Use a non-programming illustration of what this is/does -->

 O X O O O O 

 Say I wanted to change the X into a Y...

 0 Y 0 0 0 0

<!-- Possible Uses For This Function: -->

Splice can be used to add, remove, or replace the content of the targeted array's index. This method changes the original array. Also you could store the removed contents of a splice in a variable.


<!-- How to call it with description of what each part does -->



exampleArray.splice(); 
First we designate the array we wish to splice. In this case "exampleArray".

exampleArray.splice(2, 1, "item");
Next we pass in the parameters. 
The first parameter, "2" represents our "start" index in this case 2.
Our second parameter, "1" is our "deleteCount", the number of elements to remove.
Last, our third parameter "item" is the element we wish to add to the array at our "start" index.


<!-- Example scenario(s) in which to use this function and example(s) of it's 
implementation with html and css (if necessary) -->

var serenity = [
  "Jack Sparrow", 
  "Zoe", 
  "Wash", 
  "Inara", 
  "Jayne", 
  "Kaylee", 
  "Simon", 
  "River", 
  "Book",  
  ]

Let's add the proper captain back to the Serenity.

serenity.splice(0, 1, "Mal");

Our array now holds the new element at index 0 and our ship has it's captain back.

 0 : "Mal", 1 : "Zoe", 2 : "Wash", 3 : "Inara", 4 : "Jayne", 5 : "Kaylee", 6 : "Simon", 7 : "River", 8 : "Book" 

 