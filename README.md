# code-byte
about coding
#login page
<!DOCTYPE html>
<html>
<head>
    <title>        
        heading
    </title>
    <link rel="stylesheet" href="title.css">
    </head>
    <body>
       <div><h1> CODE BYTE </h1>
        <h2>Practice makes man perfect...</h2></div>
        <button><a href ="file:///C:/Users/PRADEEP%20KUMAR/project.html">Login</a></button>
    </body>
</html>
#css
h1{
    text-align: center;
    color:aliceblue;
   font-size: 100px;
   text-decoration: underline;
}
button{border-radius:100px;
    border: solid;
    background-color: rgb(39, 242, 8);    
    border-color: rgb(9, 198, 251);
    font-size: calc(30px);
    margin-top: 300px;
    margin-left: 5cm;
    padding-top: 0.5cm;
    padding-left: 2cm;
    padding-bottom: 0.5cm;
    padding-right: 2cm;
    cursor:pointer;
 }
 button a{
    text-decoration: rgba(0, 0, 255, 0.823);
 }

button:hover{
    background-color: gainsboro;
    transition: 1.5s;
}
body{
    background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRj_HT4-iFBc-ABb6vvQQxZZOlxGRDhm9rLRQ&usqp=CAU);
    background-repeat: no-repeat;
    background-size: cover;
}
h2{
    color: aliceblue;
    text-align: center;
    margin-left: 20cm;
    
}
#Main page
<!DOCTYPE html>
<head>
    <title> Coding Practice</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>CODE BYTE</h1>

    <div class="top">
        <a class="active" href="#home">HOME</a>
    <a href="#about">ABOUT</a>
    <br>
    </div>
    <br>
    Username:<input type="text" name="username"></div>
    <div class="navbar">Time Limit-45min</div>
    <br>
    <h2>Python</h2>
    <button class="btn"> <a class="courses" href="file:///C:/Users/PRADEEP%20KUMAR/courses.html">Courses </a></button> <button class="bbtn"> <a class="tests" href="file:///C:/Users/PRADEEP%20KUMAR/Test.html">Take Test</a></button>
</body>
</html>
#css
h1{
    background-color:rgba(100, 223, 223, 0.805);
    text-align: center;
    font-family: 'Courier New', Courier, monospace;
    border-style: dotted;
}


.top{
    background-color: aquamarine;
}

.top a.active{
    background-color: blue;
    color: azure;
}
h2{
    text-align: center;
    background-color: antiquewhite;
}

body{
    background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSFVzTNyv874BQq1qnYWq-dhXqMEWfTCc1sKA&usqp=CAU);
    background-repeat: no-repeat;
    background-size: cover;
}
.navbar{
    text-align: right;
}
.btn{
    margin-top: 10px;
    margin-left: 170px;
    border-radius: 20px;
    padding: 170px;
    padding-right: 200px;
    background-color: cyan;
    border: solid;
    font-size: 40px;
}

.btn:hover{
    background-color: rgb(64, 125, 177);

}
.bbtn{
    margin-top: 40px;
    margin-left: 170px;
    border-radius: 20px;
    padding: 170px;
    padding-right: 200px;
    background-color:cyan;
    border: solid;
    font-size: 40px;
}
.bbtn:hover{
    background-color: rgb(64, 125, 177);
}
.bbtn a{
    text-decoration: none;
}
#courses page
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="courses.css">
    </head>
    <body>
        <h1> DATA TYPES </h1>
        <h2> Lets start...!</h2>
        <h3>
           <div> Computer programming is all about processing data.</div>  <div>In computer programming, the data is always represented in the binary form (0's and 1's), i.e. groups of Bits called as Bytes.</div>

<div>In the real world, we come across different types of data like age of a person(integer), number of rooms in a house (integer), price(floating-point number), height (floating-point number), Names of people, places and things (strings), inventory list (list) etc.</div>

<div>For easier and efficient processing, the data is classified into different types (data types)</div>

<div>In Python, like in all programming languages, data types are used to classify data to one particular type of data.</div>

<div>The data type of the data determines :</div>
<div>1.Possible values it can be assigned.</div>
<div>2.Possible operations that can be performed. (Arithmetic operations can be applied on numeric data and not strings)</div>
<div>3.The format in which it is stored in the memory.</div>
<div>4.The amount of memory allocated to store the data.</div>
<div>Some of the built-in data types supported in Python are:</div>

<div>1.Number</div>
<div>2.String</div>
<div>3.List</div>
<div>4.Tuple</div>
<div>5.Set</div>
<div>6.Dictionary</div>
<div>In Python, every value has a data type.</div> 

<div>A variable in Python can hold value of any data type.</div>

<div>The same variable in Python can refer to data of different data types at different times.</div>
        </h3>
        <button class="prev"> <a class="prev" href="file:///C:/Users/PRADEEP%20KUMAR/project.html">Previous</a></button> <button class="menu"><a class="menu" href="file:///C:/Users/PRADEEP%20KUMAR/title%20page.html">Main Menu</a></button>
    </body>
</html>
#css
body{
    background-color: black;
}
h1{
    color: aliceblue;
    text-align: center;
    text-decoration: underline;
    font-size: 60px;
}
h2{
    color: aliceblue;
}
h3{
    color: aliceblue;
}
.prev{
    border-radius: 10px;
    padding: 10px;
    background-color: aliceblue;
    color: black;
    font-size: larger;
}
.prev:hover{
    background-color: aqua;
}
.menu{
    border-radius: 10px;
    padding: 10px;
    margin-left: 0.5cm;
    background-color: aliceblue;
    color:black;
    font-size: larger;

}
.menu:hover{
    background-color: aqua;
}
.prev{
    text-decoration: none;
}
.menu{
    text-decoration: none;
}
#tests page
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="Test.css">
    </head>
    <body>
        <h1> Exercise </h1>
        <h3><div>1.Pick out the built-in data types in Python?</div>
            <br>
            <div> <input type="checkbox" name="option">Number <input type="checkbox" name="option2">List
            <input type="checkbox" name="option3">String <input type="checkbox" name="option4">All of the above</div>
            <br>
            <br>
            <div>2.In python every element has a data type.</div>
            <br>
            <div> <input type="checkbox" name="true">True <input type="checkbox" name="false">False</div>
            <br>
            <br>
            <div>3.Arithemetic operations can be applied on_______?</div>
            <br>
            <div> <input type="checkbox" name="opt1">Numeric <input type="checkbox" name="opt2">Not strings
            <input type="checkbox" name="opt3">All of the above <input type="checkbox" name="opt3">None of Above</div>
            <br>
            <br>
            <div>4.Group of bits is called bytes</div>
            <br>
            <div> <input type="checkbox" name="true">True <input type="checkbox" name="false">False</div>
            <br>
            <br>
            <div>5.Data type of 24 is?</div>
            <br>
            <div> <input type="checkbox" name="opt1">String <input type="checkbox" name="opt1"> floating-point
            <input type="checkbox" name="opt1">Integer <input type="checkbox" name="opt1">None of the above</div>
            <br>
            <br>
            <button class="prev"><a class="prev" href="file:///C:/Users/PRADEEP%20KUMAR/project.html"> Previous</a></button>
            <button class="menu"><a class="menu" href="file:///C:/Users/PRADEEP%20KUMAR/title%20page.html">Main Menu</a></button>
            <button class="submit">Submit</button>
            <button class="Logout">Log Out</button>
        </h3>
    </body>
</html>
#css
h1{
    font-size: 60px;
    text-align: center;
    color: aliceblue;
    text-decoration: underline;
}
body{
   
    background-color: black;
}
h3{
    color: aliceblue;
    padding-left: 170px;
    font-size: larger;
}
.prev{
    border-radius: 10px;
    padding: 10px;
    margin-top: 0.5cm;
    background-color: aliceblue;
    color: black;
    font-size: larger;
    text-align: center;
}
.prev:hover{
    background-color: aqua;
}
.menu{
    border-radius: 10px;
    padding: 10px;
    margin-top: 0.5cm;
    background-color: aliceblue;
    color:black;
    font-size: larger;
    text-align: center;
}
.menu:hover{
    background-color: aqua;
}
.submit{
    border-radius: 10px;
    padding: 10px;
    margin-left: 0.5cm;
    margin-top: 0.5cm;
    background-color: aliceblue;
    color:black;
    font-size: larger;
}
.submit:hover{
    background-color: chartreuse;
}
.Logout{
    border-radius: 10px;
    padding: 10px;
    margin-left: 25cm;
    background-color: aliceblue;
    color:black;
    font-size: larger;  
}
.Logout:hover{
    background-color: red;
}
.prev{
    text-decoration: none;
}
.menu{
    text-decoration: none;
}
