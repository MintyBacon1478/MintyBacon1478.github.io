---
title: Encryption Summary
layout: post
author: ben.munton
permalink: /encryption-summary/
source-id: 1U4xJtE9iiyR4fhOGHAZxAmqbuOyucMBG9cjuBUoCFb0
published: true
---
<table>
  <tr>
    <td>Title</td>
    <td>What we've learnt</td>
    <td>Date</td>
    <td>9/10/17</td>
  </tr>
</table>


<table>
  <tr>
    <td>Starting point:</td>
    <td>A blank Google Sheet</td>
  </tr>
  <tr>
    <td>Target for this lesson?</td>
    <td>To create a program to encrypt, concatenate and decrypt any string of letters that we put into it</td>
  </tr>
  <tr>
    <td>Did I reach my target? 
(add details to "Lesson Review")</td>
    <td> Yes, and it works well. It can do that for any string that we put into it</td>
  </tr>
</table>


<table>
  <tr>
    <td>Lesson Review</td>
  </tr>
  <tr>
    <td>How did I learn? What strategies were effective? </td>
  </tr>
  <tr>
    <td>We were learning about code, and how it could be used. We thought about how to create codes like caesar ciphers, and others like it.  A caesar cipher is when you take a letter in the alphabet, and then make it into the next letter along, for example an A turns into a B, and B's turn into C’s. This means that if you do this to every letter in a sentence, it turns into something that only somebody who knew what to do with the random letters could understand it. We want to build a machine that can do this for us, and then we could input any sentence and get the code, and do it the opposite way round. 

First of all we had to make our normal alphabet, and then next to it in google sheets, we put what every letter would turn into. This could be any combination, it could just be random and have no order, as long as you did not repeat any of the letters.
First we had to put in our individual letters. Then, we took each individual letter and took them, and compared it to what letter it would have become in our table, of what to do with each letter, and outputted each of these letters. We did  this by saying =iferror(vlookup(e2,$A$1:$B$26,2), )
This means that you take whatever is in e2, and then take it to the 2nd column of the grid that we made. It then puts the new letter in underneath. The =iferror((),) means that if there is an error, leave the section blank.

Next you had to put all of this code together, from the separate letters, into a string. This means that you that to "Concatenate" the code, which means to put all of the letters together. To do this, you just did =concatenate(). This means that all of the letters are put together, into a string. 

To decode the code, you had to separate the string into the different letters. You had to take the first amount of letters from the left, then take the rightmost letter of that, to get the letters separated.  Then, you would go back to the grid of letters. And find the right letter, and output it. Then you would concatenate it back into a normal string.</td>
  </tr>
  <tr>
    <td>What limited my learning? Which habits do I need to work on? </td>
  </tr>
  <tr>
    <td>I was able to see how to do all of these sections, and then even if I didn’t, I was able to figure it out, as it was very logical. There was a lot of things to do, but I was able to figure out what code to put in, but with the people around me, we were able to figure it out. </td>
  </tr>
  <tr>
    <td>What will I change for next time? How will I improve my learning?</td>
  </tr>
  <tr>
    <td>Now that I have finished, and my code works well, I do not need to improve it.  This means that next lesson we will probably start something new, and it will be very interesting.</td>
  </tr>
</table>


