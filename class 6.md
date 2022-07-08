
![3904529](https://user-images.githubusercontent.com/106101235/169898511-08d2bb3c-57d8-49dc-be08-358037af92e1.png)


### Introduction to JavaScript

JavaSript is a lightweight interpreted compiled, multi-paradigm, single-threaded, dynamic coding language. JavaSript helps websites implement functions and is very commonly used in web development. Java and Javascript are not the same language, they have many different semantics, syntax and usage.

##JavaScript Input and Output

One usuage of JavaScript is it's input and outout functions, for ex. 

First name: <input id="first_name">
Last name: <input id="last_name">
<button id="say">Say hi!</button>
 
<hr>
<div id="result"></div>
 
<script>
function say_hi() {
    var fname = document.getElementById('first_name').value;
    var lname = document.getElementById('last_name').value;
 
    var html = 'Hello <b>' + fname + '</b> ' + lname;
 
    document.getElementById('result').innerHTML = html;
}
 
document.getElementById('say').addEventListener('click', say_hi);
</script>

This shows how a typical Html website would give the user a promt for "First name" and "Last name"
This will, in turn output a message saying "Hello 'First name' 'Last name' 

##JavaScript Variables

JavaScript will often use variables, which can be declared with by typing var ex.
var x=5;
var y=6;
var z= x+y;
