## JAVASCRIPT FREECODECAMP CRASH COURSE
### Print and comment
<script>
  console.log("hello world")
</script>

//in line comment
/*   jdewjnclw  */ multiline comment

### declaring variable - 3 ways
1) var name="Angela"        //use anywhere
name="John"      //declare only first time

2) let name="Angela"      //use only in that scope

3) const name="Angela"
constant variables cannot be reassinged

### line terminator
; optional but prefered

### incrementing
myvar++;<br>
myvar--;<br>
mayvar+=1<br>
myvar-=1<br>

### String declaration
single quote or double quote or backtick ``

### Length of string
l=mystring.length;

### Array
arr.push("abc")
arr.pop()   pops last element
#### shift and unshift:
  arr=[1,2,3]<br>
  arr.shift()<br>
  returns first time: 1
  -> (arr:) [2,3]<br>
  arr.unshift()<br>
  -> [1, 2, 3]<br>

### Functions
if you do not use var keyword in a function, then it becomes global automatically, else it is scoped to tht function only
typeof myvar  -> returns type (number, boolean, object, function)

### JSON
JSON is a format for storing and exchanging data in a readable and lightweight manner.
 (lightweight - minimalistic syntax, efficient)
JavaScript Object Notation (JSON)
JSON strings consist of key-value pairs, where keys are strings and values can be any type
often used for sending data between client and server

JSON.stringify(myarr) - converts to string representation
eg: JSON-formatted string

### Equality
=== strict inequality (no type conversion)
&& - and
|| - or

### if else
else if

### switch
switch(val){
  case 1:  <br>
    ans='alpha';  <br>
    break; <br>
  case 2: <br>
    ans='beta';  <br>
    break; <br>
  default:
    ans='gamma'; <br>
    break; <br>
} <br>
return ans

### some functions
alert("abc")
prompt()
parseInt(prompt()

### Case
vname.toUpperCase()

### Array
arr.includes(ele)   checks if ele is present in array

### Adding js to website html
inside body: <script src="script.js" charset="utf-8"></script>




