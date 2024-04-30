# Ex.08 Design of a Standard Calculator
## Date:30.04.2024

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
calc.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script type="text/javascript">
    function dis(x){
        document.getElementById("inbox").value+=x;
    }
    function clr(){
        document.getElementById("inbox").value='';
    }
    function del(){
        var num=document.getElementById("inbox").value;
        var ans=num.substring(0,num.length-1);
        document.getElementById("inbox").value=ans;
    }
    function fun(){
        var res=document.getElementById("inbox").value;
        if(res){
        var ans=eval(res);
        document.getElementById("inbox").value=ans;
        }
    }
    </script>

</head>
<style>
body{
background-color:black;
}
.container{
 position:relative;
margin-top:30px;
margin-left:45px;
width:270px;
height:380px;

}
button{
width:60px;
height:50px;
padding:20px 40px 20px 20px;
border-right: none;
font-size:20px;
text-align: center;
}
input{

width:253px;
height:100px;
font-size:30px;}
#b10{
padding-right:107px;
}
.box{
    position:absolute;
    top:27%;
margin-left:35%;
   height:430px;
   width:340px;
    background-color:darkgrey;
    margin-right: 100px;
    
top: 30%;
left: 60px;
border-radius: 10px;
overflow: hidden;
padding-right: 5px;
}
h2{
    text-align: center;
    color: aqua;
    font-family:serif;
    margin-top: 90px;
    margin-left:0.5%;
    font-size: x-large;
}
.red{
    background-color: red;
    color: green;
}
.red1{
    color: green;

}
.red3{
    color: green;
}
.red4{
    color: green;
}
.red5{
    color: green;
}
.yellow{
    color: green;
}
.yellow2{
    color: green;
    
}
.red6{
    color: green;
}
.blue{
    color: blue;
    background-color: lightskyblue;
}
</style>
</head>
<body>
<div class="box">
<div class="container">
<input type="text"  class="blue" id="inbox"name="input"><br>
<button onclick="clr()"> AC</button>
<button class="red"  onclick="del()">DE</button>
<button class="red4" onclick="dis('%')">%</button>
<button class="red5" onclick="dis('/')">/</button><br>
<button name="1" onclick="dis('1')">1</button>
<button onclick="dis('2')">2</button>
<button onclick="dis('3')">3</button>
<button class="red3" onclick="dis('+')">+</button ><br>
<button onclick="dis('4')">4</button>
<button  onclick="dis('5')">5</button>
<button onclick="dis('6')">6</button>
<button class="red2"  onclick="dis('-')">-</button><br>
<button onclick="dis('7')">7</button>
<button onclick="dis('8')">8</button>
<button onclick="dis('9')">9</button>
<button class="yellow" onclick="dis('*')" >x</button><br>
<button class="yellow1" onclick="dis('.')">.</button>
<button onclick="dis('0')">0</button>
<button id="b10" class="red6" onclick="fun()">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;=</button><br>
</div>
</div>
<h2>
    Subash calculator<br><br>
    Register Number:212223230218
</h2>
</body>
</html>
```
## OUTPUT:

![Screenshot 2024-04-30 114503](https://github.com/subashr1702/Calc/assets/168012691/9a9b4c52-03bd-48b9-9cfa-c076d4ef80d7)


![Screenshot 2024-04-30 114512](https://github.com/subashr1702/Calc/assets/168012691/84fd0fec-2ac3-47a4-ae05-0ded42f3c338)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
