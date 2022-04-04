# javascript-full

<!DOCTYPE html>
<html>
    <head>
     <title>javascript syntax</title>
  
    </head>
    <body bgcolor="lightblue">
        <!----
        <br>
        <script>
            document.write("yeah hai this madan")
        </script><br>
        <script>
            window.alert("malware is attacking")
        </script>
        <br>
        <script>
        alert("hai madan vani ios your wife")
        </script>
        <br>
        <p id="demo">welcome</p>
        <script type="text/javascript"> 
        document.getElementById("demo").innerHTML="cleeanning"; 
        </script>
        <h1>FUNCTIONS IN JAVASCRIPT</h1>
      <script>
             function  hello(){
              document.write("madan"); 
             }
            hello();
      </script>
      <input type="button" value="click here" onclick="hello()"/>
     
      <script>
      function  hello(){
       alert("madan"); 
      }
     hello();
</script>
<input type="button" value="click here" onclick="hello()"/>


<script>
    function multiply(number){
     alert(3*2*6);
    }
</script>
   <input type="button" value="click" onclick="multiply()"/>
   <br>
    
<script>
    function madan(number){
        alert(number*number*number);

    }
</script>
<input type="button" value="onclick" onclick="madan(3)"  />


<script>
    function multiply(number){
        return number*number*number; 
    }
</script> 
<script>
    alert(multiply(2))
</script>
-->
<!---
<h1>VARIABLESN IN JAVASCRIPT</h1>

<script>
    var x=20;
    document.write(x);
</script>


    local variable
    
    
    <script>
    function add(){
        var x=2;
       document.write("value of x is "+ x);
      
    } 
    add(); 
</script>    -->

<!---
             
global VARIABLES

<script>
    var x=20;
    function madan(){
        document.write(x)
    }
    madan();
    document.write(x)
</script>
-->


<!-- 
    DATA TYPES ARE 5 TYPES:=
    1.Number Datatype
    2.String Datatype
    3.Boolean Datatype
    4.Regular Datatype
    5.Array

  1.Number Datatype:=

  <script>
    var x=225;
    document.write(x);
  </script>

  1.A.  floating pont(called as number)
    <script>
        var z=23.5;
        document.write(z);
    </script>


2. String Datatype:=
<script>
  var name="madan";
  document.write(name);

</script>

3.Boolean Datatype:=

<script>
    
  var madan=true;
    document.write(madan);
</script>

4.Regular Datatype:= its for adding subtracting multipication division
<script>
    var x=37;
    var y=15;
    var z=252;
    var a=x+y+z;
    document.write(a)
</script>



5.Array:= similar datatype or one or more values stored in data is used by Array datatype

  there are 3 types of arrays:=

  1. By Aray Literal

  2. Array Directly (New Keyboard)

  3. Array Constructor


1. By Aray Literal

<script>
    var friends=["madan" ,"kumar", "parchuri"];
    for(i=0; i<friends.length; i++){
        document.write(friends[i]+"<br>");
    }
</script>

2. Array Directly (New Keyboard):=
<br>
<script>
    var i=0;
    var friendss=new Array();
    friendss[0]="parchurui";
    friendss[1]="madan";
    friendss[2]="kumar";
    friendss[3]="gowd";
    // for printing data we are usings for loop or while loop  currrently we are using while loop
    while(i<friendss.length){
        document.write(friendss[i]+"<br>");
        i++;
    }
</script>

**important in angular*** 
3. Array Constructor:=

<script>
var emply=new Array("parchuri","madan","kumar");
  for(i=0; i<emply.length; i++){
      document.write(emply[i]+"<br>");
  }
</script>
-->

<!---
Objects:= different types of datatype or one or more values stored in data is used by Array datatype

  there are 3 types of Objects(entity):=

  1. By Objects Literal

  2. Objects Directly (New Keyboard)

  3. Objects Constructor

1st Way:=
  <script>
      var fri1={
          srno:100, name:"madan", class:10
      }
      
     document.write(fri1.srno+" "+fri1.name+" "+fri1.class)
  </script>

  2nd Way:=
  <script>
      var emp=new Object();
      emp.id=222;
      emp.name="madan";
      emp.salary=2500;
      document.write(emp.id+" "+emp.name+" "+emp.salary);
  </script>


<script>

    function student(srno,name,address,branch){
      this.srno=srno;
      this.name=name;
      this.address=address;
      this.branch=branch;
    }
    var stu1=new student(10,"madan","ippagunta","mech")
    document.write(stu1.srno+" "+stu1.name+" "+stu1.address+" "+stu1.branch)
</script>
=-->


<!----
how to identify datatypes:=
<script>
  var x=52;
  document.write(typeof(x))
    
</script>

<script>
    var x="20"; // striog data type
    function name(){
     document.write(typeof(x))
    }
    document.write(typeof(x))
    name()
</script>

<script>
    var x=52.2; // number
    document.write(typeof(x))
      
  </script>


<script>
    var x=true;  //boolean data type
    document.write(typeof(x))
      
  </script>

<script>
    var x=52;
    var y=35;  // regular Datatype 
    var z=51;
    var a=x+y+z;
    document.write(typeof(x))
      
  </script>

  this are all datatypes
--->

<!---
 Types of OPERATORS:=

 1. Arithematic Operators ( +, -, *, /, %, ++, -- )

 2. Assignment Operators  ( =, +=, -=, *=, /=, %= )

 3. Comparison/Relational Operators ( ==, !=, <, <=, >, >=)

 4. Bitwise Operators     ( &, |, ^, ~, <<, >>, >>>)

 5. Logical Operators     ( &&, ||, !)

 6. Special operators     ( ?:, ,, delete, in, instanceof, new, typeof, void, yield)
  

   
1. Arithematic Operators:= by using this we can add + or sub - or mult * or division / or percentage %  or (increment operator ==> ++) or (decrement operator ==> --)
<script>
    var x=52;
    var y=10;
    document.write(x+y);
    document.write(x-y);
    document.write(x*y);
    document.write(x/y);
    document.write(x%y);
    // increment operators:=  this is for adding 1+1+1 example 52 means (x++) ok after this again (x++) means 53  52,53 adding one numberb to it
    document.write(x++) // post increment  in this adding one + one 52
    document.write(x++)  // 53
    document.write(++x) // pre  increment  automatic value increase fromm52 to 53 directely
</script

    <script>
        var x=52;
       // decrement operators:=  this is for adding 1-1-1 example 52 means (x--) ok after this again (x--) means 51  50,49 subtracting one numberb to it
       document.write(x--) // post decrement  in this subtracting one - one 52
       document.write(x--)// 51
      //***important subtracting***//
       document.write(--x) // pre  decrement  automatic value decrease fromm52 to 51 directely

    
  </script>
-->
<!--
2.Assignment Operators:= ( =, +=, -=, *=, /=, %= )
var x=50
// (x=24);
// += (x=x+20)
// -= (x=x-20)
// *= (x=x*20)
// /= (x=x/20)
// %= (x=x%10)


<script>
    var x=37;
    document.write(x)
</script><br>

 <script>
     var x=37;
     x+=13;

     document.write(x)
 </script><br>
 
 
 <script>
    var x=37;
    x-=30;
    
    document.write(x)
</script><br>

<script>
    var x=37;
    x*=13;
    
    document.write(x)
</script><br>


<script>
    var x=37;
    x/=13;
    
    document.write(x)
</script><br>


<script>
    var x=37;
    x%=13;
    
    document.write(x)
</script><br>
  this aree called as Assignment Operators

-->
 
  <!----
// CONDITION BASED OPERATORS (3,4,5)

3. Comparison/Relational Operators ( ==, !=, <, <=, >, >=)
 <script>
     var x=20;
     var y=20;
     var z=x+y;
     if(x==y){
         document.write(true);
     }
     else{
       document.write(false);
     }
 </script><br>


<script>
    var x=20;
    var y=20;
    var z=x+y;
    if(x!=y){
        document.write(true);
    }
    else{
      document.write(false);
    }
</script><br>

<script>
    var x=20;
    var y=28;
    var z=x+y;
    if(x<y){
        document.write(true);
    }
    else{
      document.write(false);
    }
</script><br>

<script>
    var x=20;
    var y=20;
    var z=x+y;
    if(x>y){
        document.write(true);
    }
    else{
      document.write(false);
    }
</script><br>

<script>
    var x=20;
    var y=20;
    var z=x+y;
    if(x>=y){
        document.write(true);
    }
    else{
      document.write(false);
    }
</script><br>

<script>
    var x=20;
    var y=20;
    var z=x+y;
    if(x<=y){
        document.write(true);
    }
    else{
      document.write(false);
    }
</script>



4. Bitwise Operators     ( &, |, ^, ~, <<, >>, >>>)
<script>
    var x=25;
    var y=4;
    var z=54;
    if(y>x & y>z){
        document.write("hai this madan");
    }
    else if(x>z & y>z){
        documen.write("hello failure");
    }
    else{
        document.write("haiu");
    }
</script><br>

<script>
var x=25;
var y=455 ;
var z=54;
if(y>x | y>z){
    document.write("hai this madan");
}
else if(x>z | y>z){
    documen.write("hello failure");
}
else{
    document.write("haiu");
}
</script><br>

<script>
    var names="madan";
    var name="kumar";
    var namez="parchuri";
    if(name=="kumar" ^ namez=="parchuri"){
        document.write("hai this mada");
    }
   
    </script><br>




5. Logical Operators     ( &&, ||, !):==

<script>
    var names="madan";
    var name="kumar";        // it checks first if condition and gives answer without checking another if conditiom
    var namez="parchuri";
    if(name=="kumar" && namez=="parchuri"){
        document.write("hai this mada");
    }
   
    </script><br>


<script>
    var names="madan";
    var name="kumar";            // it checks first if condition and gives answer without checking another if conditiom
    var namez="parchuri";
    var namez="parchuri";
    if(name=="kumar" || namez=="parchuri"){
        document.write("hai this mada");
    }
   
    </script><br>

<script>
    var names="madan";
    var name="kumar";
    var namez="parchuri";
    if(name=="kumar" && || namez=="parchuri"){
        document.write("hai this mada");
    }
   
    </script><br>



6. Special operators     ( ?:, ,, delete, in, instanceof, new, typeof, void, yield)
  
-->


<!--
// if-else condition or statement in JAVASCRIPT:==
 <script>
     var x=50;
     if(x>60){
         document.write("x value is greatherthan 10");
     }
     else{
         document.write("you have error")
     }
 </script><br>


// if-else-if condition or statement in JAVASCRIPT:== two or more conditions
<script>
    var marks=50;
    if(marks>60){
        document.write("x value is greatherthan 10");
    }
    else if(marks>45){
        document.write("you got 45")
    }
    else if(marks>25){
     document.write("x is value of madan")   
    }
    else{
        document.write("fail")
    }
</script>
-->

<!--
// Loops in JAVASCRIPT:=
  
they are three types:=

1. for loop

2. while loop

3. do-while loop


1.for loop:=for(){} :== is called syntax
  <script> //in () in this pass paranthesis 
  // using parameters i as 
      for(i=0; i<=5; i++){ //i=0 checks that i<=5 and print "hello" after that it count as one and i++ means(i+1); in then same way again it checks and reverts back as "hello" and i++(i+3); in then same way again it checks and reverts back as "hello" and i++(i+3); in then same way again it checks and reverts back as "hello" and i++(i+4); in then same way again it checks and reverts back as "hello" and i++(i+5); in then same way again it checks and reverts back as "hello" and i++(i+6) here it stops because 6 is greater than 5 so printing "hell will stopped hereo";

  document.write("hello <br>")
      }
  </script>

// tables in javascript using for loop<br>
  <script>
      for(i=1; i<=10; i++){
          document.write(2*i+"<br>"); 
      }
  </script>


<script>
    for(i=1; i<=10; i++){
  document.write("2x" +i+"="+ 2*i+"<br>")
    };
   for(i=1;i<=10; i++){
      document.write("20x"+i+"="+20*i+"<br>")
  }
</script>



2. while loop:= for this using we have to create variable
<script>
    var i=20;
    while(i<=50){
        document.write(i+'<br>')
        i=i+2; //or i++;
    }
</script>

3. do-while loop:=
<script>
    var i=20;
    do{
        document.write(i+"<br>");
        i=i+2;// or i++
    }
    while(i<=50);
</script><br>

<script>
    var i=51;  // in this you can show if condition is not satisified then it shows starting variable i=51; as 51in browser
    do{
        document.write(i+"<br>");
        i=i+2;// or i++
    }
    while(i<=50);
</script>

-->


<!--
//Switch conditon or Statement in JAVASCRIPT::=
<script>
    var marks=45;
   switch(true){
       case marks>90 : result="A Grade";
        break;
       case marks>75 : result="B Grade";
       break;
       case marks>60 : result="C Grade";
       break; 
       case marks>60 : result="C Grade";
       break; 
       case marks>50 : result="C Grade";
       break; 
       default : result="fail";
    
   }
   document.write(result);

</script>

-->
<!---
To Display Date and Time object in JAVASCRIPT:=
<script>
var today=new Date();
document.write(today)

</script>

//only Date year month seperately
<script>
var today=new Date();
var day=today.getDate();
var month=today.getMonth()+1;
var year=today.getFullYear();
document.write(day+"/"+month+"/"+year)
</script>;

//to call hours:=
<script>
    var today=new Date();
    var time=today.getHours();
    var mints=today.getMinutes();
    var sec=today.getSeconds();
    document.write(time+":"+mints+":"+sec)
</script>

//how to display present running time without refreshing broswer:=
<h1 id="madan"></h1>
<script>
function getTime(){
    var today=new Date();
    var h=today.getHours();
    var m=today.getMinutes();
    var s=today.getSeconds();
    document.getElementById("madan").innerHTML=h+":"+m+":"+s //by calling innerHTML we canm call correct time by calling it id usung html cocept
    setInterval("getTime()",1000);
        

}
getTime();
</script>
--->
<!----
strings objects in JAVASCRIPT:=
<script>
    var x="madan";  // its called concatnation method
    var y="hai ";
    document.write(y+" "+x)
</script>

<script>
    var x=new String("parchuri madan"); //to display words in letter as mention in number
    document.write(x.charAt(3));
    document.write(x.indexOf("madan")); // to identify position of word as number
    document.write(x.toLowerCase());// to print words in lower case
    document.write(x.toUpperCase()); // to print words in upper case
    document.write(x.slice(2,6));// to show words in between 2,6
</script>
--->
<!----
Maths objects in JAVASCRIPT:=
<script>
    var x=25;
    var y=35;
    document.write(Math.sqrt(x));//to find square root
   document.write(Math.random());// to find random numbers
   document.write(Math.pow(2,6));// to display power
   document.write(Math.abs(x));// to display absolute number
   
   </script>
   //to show round numbers for 4.5 as 5
   <script>
       var x=15.5;
       document.write(Math.floor(x));// floor method
       document.write(Math.ceil(x));// to display 1 to right side of point(.)
       document.write(Math.round(x));// to display round figure as 16 if its above (.5) if its below then (0.4) then it shows 15 only

   </script>
--->

<!----
//Browser object model (BOM):=

there are 6 types:=

1.  window object (alert,confirm,prompt,open,close,size,interval,timeout)

2. history object(back,forward)

3. Navigator Object (appName,appVersion,appCodeName,cookieEnabled,usreAgent,language,platform,product,javaEnabled)

4. Screen Object (width,height,colorDepth & pixelDepth)

5. Location Object (href, hostname, pathname, protocol(http.https), assign)

6. Cookies


1. window object (alert,confirm,prompt,open,close,size,interval,timeout):=
<script>
    window.alert("hello")
</script>
<script>
window.confirm("you are having error and virous")
</script>
<script>

 var    x=window.prompt("who are you?");
 document.write(x);// to display name which is written in box
</script>
<script>
    open("http://www.google.com")// to open google
</script>
<center>
<script>
    function google(){
        open("http://www.google.com");
    }
</script>
    <input type="button" value="gooogle"
      onclick="google()"/>
</center>


    <script>
        close();// to close browser
    </script>

<script>//size:=
    var w=window.innerWidth;// to didplay broswer width and height
    var h=window.innerHeight;
    document.write(w+" "+h)
</script>
//note:= you can use 1000 or mor if you required
<script>
    function myFunction(){
        alert("hello");

    }
    setInterval(myFunction,1000) //1000=1sec
</script>

<script>
    function myfunction(){
        alert("you are time is over");// to show message only its dnt repeat process

    }
    setTimeout(myfunction,1000);
</script>

\\end of window object


2. history object(back,forward):=//to display history of the browser

<script>
 function goback(){
    history.back();
 }   

</script>
<input type="button" value="back"  onclick="goback();" />

<script>
function gofor(){
    history.forward();
}
</script>
<input type="button" value="forward" onclick="gofor()" />


3.Navigator object (appName,appVersion,appCodeName,cookieEnabled,usreAgent,language,platform,product,javaEnabled):=
<script>
    document.write(navigator.appName);
</script>
<script>
    document.write(navigator.appVersion);
</script>
<script>
    document.write(navigator.appCodeName);
</script>
<script>
    document.write(navigator.cookieEnabled);
</script>
<script>
    document.write(navigator.userAgent)
</script>
<script>
    document.write(navigator.language)
</script>
<script>
    document.write(navigator.platform)
</script>
<script>
    document.write(navigator.product)
</script>
<script>
    document.write(navigator.javaEnabled())// javaEnabled is method
</script>


4. Screen object   (width,height,colorDepth & pixelDepth):=
//Width:=
<script>
    document.write(screen.width+"<br>");
    var w=window.innerWidth;
    document.write(w)
</script>

//Height:=
<script>
    document.write(screen.height+"<br>");
    var w=window.innerHeight;
    document.write(w)
</script>

//Color-depth:=
<script>
    document.write(screen.colorDepth);// instead of colorDepth we can also use pixelDepth

</script>



5.Location Object (href, hostname, pathname, protocol(http.https), assign):=

<script>
    document.write(location.href);
</script>

<script>
    document.write(location.hostname);
</script>

<script>
    document.write(location.pathname); 
</script>

<script>
    document.write(location.protocol); // there are two types of protocols:=
                                       //they are:=
                                             //    1. http
                                             //    2. https(secure)
</script>

<script>
    document.write(location.assign("http://www.google.com"));// assign() is a method from one website to another website
</script>


6.Cookies :=

--->

<!----
DOM (Document Object Model):=
                
                 With the help of DOM we can add dynamic xontent to our web page. Update the content, structure & style 
3 Methods

they are:=

1. write();

2. getElementById();

3.getElementByName();

1. write():=
<script>
    document.write("hello");
</script>

2. getElementById():=
<script>
    function getcube(){
        var num=document.getElementById("number").value;
        alert("this is cube"+num*num*num);
    }
</script>
  <form>
      Enter NUm: <input type="text" id="number">\
      <br/>
      <input type="button" value="Find cube" onclick="getcube()" />
  </form> 


3.getElementByName:=

<script>
    function printvalue(){
        var name1=document.form1.username.value;
        alert("welcome"+name1)
      
    }
</script>
  <form name="form1">
      Enter Name: <input type="text" name="username" >\
      <br/>
      <input type="button" value="print" onclick="printvalue()" />
  </form> 

DOM Properties:=

there are 3 types of properties:=

1. Changing Content

2. Changing Value

3. Changing Style


1. Changing Content:=

<p id="p1">Hello madan kumar</p>

<script>
  document.getElementById("p1").innerHTML="hai this madan kumar"
</script>

2. Changing Value:=

<img id="myimage" src="C:\Users\LEGION\OneDrive\Pictures\teddy bear.jpg">

<script>
  document.getElementById("myimage").src="C:\Users\LEGION\OneDrive\Desktop\unnamed.jpg";
</script>


3.Changing style:=

<p id="p2">Hello parchiri madan kumar</p>
<script>
    document.getElementById("p2").style.color="yellow";// changing color.
</script>
-->
        

        
  document.write("hai this madan kumar");


<!----
        <br>
        <script>
            document.write("yeah hai this madan")
        </script><br>
        <script>
            window.alert("malware is attacking")
        </script>
        <br>
        <script>
        alert("hai madan vani ios your wife")
        </script>
        <br>
        <p id="demo">welcome</p>
        <script type="text/javascript"> 
        document.getElementById("demo").innerHTML="cleeanning"; 
        </script>
        <h1>FUNCTIONS IN JAVASCRIPT</h1>
      <script>
             function  hello(){
              document.write("madan"); 
             }
            hello();
      </script>
      <input type="button" value="click here" onclick="hello()"/>
     
      <script>
      function  hello(){
       alert("madan"); 
      }
     hello();
</script>
<input type="button" value="click here" onclick="hello()"/>


<script>
    function multiply(number){
     alert(3*2*6);
    }
</script>
   <input type="button" value="click" onclick="multiply()"/>
   <br>
    
<script>
    function madan(number){
        alert(number*number*number);

    }
</script>
<input type="button" value="onclick" onclick="madan(3)"  />


<script>
    function multiply(number){
        return number*number*number; 
    }
</script> 
<script>
    alert(multiply(2))
</script>
-->
<!---
<h1>VARIABLESN IN JAVASCRIPT</h1>

<script>
    var x=20;
    document.write(x);
</script>


    local variable
    
    
    <script>
    function add(){
        var x=2;
       document.write("value of x is "+ x);
      
    } 
    add(); 
</script>    -->

<!---
             
global VARIABLES

<script>
    var x=20;
    function madan(){
        document.write(x)
    }
    madan();
    document.write(x)
</script>
-->


<!-- 
    DATA TYPES ARE 5 TYPES:=
    1.Number Datatype
    2.String Datatype
    3.Boolean Datatype
    4.Regular Datatype
    5.Array

  1.Number Datatype:=

  <script>
    var x=225;
    document.write(x);
  </script>

  1.A.  floating pont(called as number)
    <script>
        var z=23.5;
        document.write(z);
    </script>


2. String Datatype:=
<script>
  var name="madan";
  document.write(name);

</script>

3.Boolean Datatype:=

<script>
    
  var madan=true;
    document.write(madan);
</script>

4.Regular Datatype:= its for adding subtracting multipication division
<script>
    var x=37;
    var y=15;
    var z=252;
    var a=x+y+z;
    document.write(a)
</script>



5.Array:= similar datatype or one or more values stored in data is used by Array datatype

  there are 3 types of arrays:=

  1. By Aray Literal

  2. Array Directly (New Keyboard)

  3. Array Constructor


1. By Aray Literal

<script>
    var friends=["madan" ,"kumar", "parchuri"];
    for(i=0; i<friends.length; i++){
        document.write(friends[i]+"<br>");
    }
</script>

2. Array Directly (New Keyboard):=
<br>
<script>
    var i=0;
    var friendss=new Array();
    friendss[0]="parchurui";
    friendss[1]="madan";
    friendss[2]="kumar";
    friendss[3]="gowd";
    // for printing data we are usings for loop or while loop  currrently we are using while loop
    while(i<friendss.length){
        document.write(friendss[i]+"<br>");
        i++;
    }
</script>

**important in angular*** 
3. Array Constructor:=

<script>
var emply=new Array("parchuri","madan","kumar");
  for(i=0; i<emply.length; i++){
      document.write(emply[i]+"<br>");
  }
</script>
-->

<!---
Objects:= different types of datatype or one or more values stored in data is used by Array datatype

  there are 3 types of Objects(entity):=

  1. By Objects Literal

  2. Objects Directly (New Keyboard)

  3. Objects Constructor

1st Way:=
  <script>
      var fri1={
          srno:100, name:"madan", class:10
      }
      
     document.write(fri1.srno+" "+fri1.name+" "+fri1.class)
  </script>

  2nd Way:=
  <script>
      var emp=new Object();
      emp.id=222;
      emp.name="madan";
      emp.salary=2500;
      document.write(emp.id+" "+emp.name+" "+emp.salary);
  </script>


<script>

    function student(srno,name,address,branch){
      this.srno=srno;
      this.name=name;
      this.address=address;
      this.branch=branch;
    }
    var stu1=new student(10,"madan","ippagunta","mech")
    document.write(stu1.srno+" "+stu1.name+" "+stu1.address+" "+stu1.branch)
</script>
=-->


<!----
how to identify datatypes:=
<script>
  var x=52;
  document.write(typeof(x))
    
</script>

<script>
    var x="20"; // striog data type
    function name(){
     document.write(typeof(x))
    }
    document.write(typeof(x))
    name()
</script>

<script>
    var x=52.2; // number
    document.write(typeof(x))
      
  </script>


<script>
    var x=true;  //boolean data type
    document.write(typeof(x))
      
  </script>

<script>
    var x=52;
    var y=35;  // regular Datatype 
    var z=51;
    var a=x+y+z;
    document.write(typeof(x))
      
  </script>

  this are all datatypes
--->

<!---
 Types of OPERATORS:=

 1. Arithematic Operators ( +, -, *, /, %, ++, -- )

 2. Assignment Operators  ( =, +=, -=, *=, /=, %= )

 3. Comparison/Relational Operators ( ==, !=, <, <=, >, >=)

 4. Bitwise Operators     ( &, |, ^, ~, <<, >>, >>>)

 5. Logical Operators     ( &&, ||, !)

 6. Special operators     ( ?:, ,, delete, in, instanceof, new, typeof, void, yield)
  

   
1. Arithematic Operators:= by using this we can add + or sub - or mult * or division / or percentage %  or (increment operator ==> ++) or (decrement operator ==> --)
<script>
    var x=52;
    var y=10;
    document.write(x+y);
    document.write(x-y);
    document.write(x*y);
    document.write(x/y);
    document.write(x%y);
    // increment operators:=  this is for adding 1+1+1 example 52 means (x++) ok after this again (x++) means 53  52,53 adding one numberb to it
    document.write(x++) // post increment  in this adding one + one 52
    document.write(x++)  // 53
    document.write(++x) // pre  increment  automatic value increase fromm52 to 53 directely
</script

    <script>
        var x=52;
       // decrement operators:=  this is for adding 1-1-1 example 52 means (x--) ok after this again (x--) means 51  50,49 subtracting one numberb to it
       document.write(x--) // post decrement  in this subtracting one - one 52
       document.write(x--)// 51
      //***important subtracting***//
       document.write(--x) // pre  decrement  automatic value decrease fromm52 to 51 directely

    
  </script>
-->
<!--
2.Assignment Operators:= ( =, +=, -=, *=, /=, %= )
var x=50
// (x=24);
// += (x=x+20)
// -= (x=x-20)
// *= (x=x*20)
// /= (x=x/20)
// %= (x=x%10)


<script>
    var x=37;
    document.write(x)
</script><br>

 <script>
     var x=37;
     x+=13;

     document.write(x)
 </script><br>
 
 
 <script>
    var x=37;
    x-=30;
    
    document.write(x)
</script><br>

<script>
    var x=37;
    x*=13;
    
    document.write(x)
</script><br>


<script>
    var x=37;
    x/=13;
    
    document.write(x)
</script><br>


<script>
    var x=37;
    x%=13;
    
    document.write(x)
</script><br>
  this aree called as Assignment Operators

-->
 
  <!----
// CONDITION BASED OPERATORS (3,4,5)

3. Comparison/Relational Operators ( ==, !=, <, <=, >, >=)
 <script>
     var x=20;
     var y=20;
     var z=x+y;
     if(x==y){
         document.write(true);
     }
     else{
       document.write(false);
     }
 </script><br>


<script>
    var x=20;
    var y=20;
    var z=x+y;
    if(x!=y){
        document.write(true);
    }
    else{
      document.write(false);
    }
</script><br>

<script>
    var x=20;
    var y=28;
    var z=x+y;
    if(x<y){
        document.write(true);
    }
    else{
      document.write(false);
    }
</script><br>

<script>
    var x=20;
    var y=20;
    var z=x+y;
    if(x>y){
        document.write(true);
    }
    else{
      document.write(false);
    }
</script><br>

<script>
    var x=20;
    var y=20;
    var z=x+y;
    if(x>=y){
        document.write(true);
    }
    else{
      document.write(false);
    }
</script><br>

<script>
    var x=20;
    var y=20;
    var z=x+y;
    if(x<=y){
        document.write(true);
    }
    else{
      document.write(false);
    }
</script>



4. Bitwise Operators     ( &, |, ^, ~, <<, >>, >>>)
<script>
    var x=25;
    var y=4;
    var z=54;
    if(y>x & y>z){
        document.write("hai this madan");
    }
    else if(x>z & y>z){
        documen.write("hello failure");
    }
    else{
        document.write("haiu");
    }
</script><br>

<script>
var x=25;
var y=455 ;
var z=54;
if(y>x | y>z){
    document.write("hai this madan");
}
else if(x>z | y>z){
    documen.write("hello failure");
}
else{
    document.write("haiu");
}
</script><br>

<script>
    var names="madan";
    var name="kumar";
    var namez="parchuri";
    if(name=="kumar" ^ namez=="parchuri"){
        document.write("hai this mada");
    }
   
    </script><br>




5. Logical Operators     ( &&, ||, !):==

<script>
    var names="madan";
    var name="kumar";        // it checks first if condition and gives answer without checking another if conditiom
    var namez="parchuri";
    if(name=="kumar" && namez=="parchuri"){
        document.write("hai this mada");
    }
   
    </script><br>


<script>
    var names="madan";
    var name="kumar";            // it checks first if condition and gives answer without checking another if conditiom
    var namez="parchuri";
    var namez="parchuri";
    if(name=="kumar" || namez=="parchuri"){
        document.write("hai this mada");
    }
   
    </script><br>

<script>
    var names="madan";
    var name="kumar";
    var namez="parchuri";
    if(name=="kumar" && || namez=="parchuri"){
        document.write("hai this mada");
    }
   
    </script><br>



6. Special operators     ( ?:, ,, delete, in, instanceof, new, typeof, void, yield)
  
-->


<!--
// if-else condition or statement in JAVASCRIPT:==
 <script>
     var x=50;
     if(x>60){
         document.write("x value is greatherthan 10");
     }
     else{
         document.write("you have error")
     }
 </script><br>


// if-else-if condition or statement in JAVASCRIPT:== two or more conditions
<script>
    var marks=50;
    if(marks>60){
        document.write("x value is greatherthan 10");
    }
    else if(marks>45){
        document.write("you got 45")
    }
    else if(marks>25){
     document.write("x is value of madan")   
    }
    else{
        document.write("fail")
    }
</script>
-->

<!--
// Loops in JAVASCRIPT:=
  
they are three types:=

1. for loop

2. while loop

3. do-while loop


1.for loop:=for(){} :== is called syntax
  <script> //in () in this pass paranthesis 
  // using parameters i as 
      for(i=0; i<=5; i++){ //i=0 checks that i<=5 and print "hello" after that it count as one and i++ means(i+1); in then same way again it checks and reverts back as "hello" and i++(i+3); in then same way again it checks and reverts back as "hello" and i++(i+3); in then same way again it checks and reverts back as "hello" and i++(i+4); in then same way again it checks and reverts back as "hello" and i++(i+5); in then same way again it checks and reverts back as "hello" and i++(i+6) here it stops because 6 is greater than 5 so printing "hell will stopped hereo";

  document.write("hello <br>")
      }
  </script>

// tables in javascript using for loop<br>
  <script>
      for(i=1; i<=10; i++){
          document.write(2*i+"<br>"); 
      }
  </script>


<script>
    for(i=1; i<=10; i++){
  document.write("2x" +i+"="+ 2*i+"<br>")
    };
   for(i=1;i<=10; i++){
      document.write("20x"+i+"="+20*i+"<br>")
  }
</script>



2. while loop:= for this using we have to create variable
<script>
    var i=20;
    while(i<=50){
        document.write(i+'<br>')
        i=i+2; //or i++;
    }
</script>

3. do-while loop:=
<script>
    var i=20;
    do{
        document.write(i+"<br>");
        i=i+2;// or i++
    }
    while(i<=50);
</script><br>

<script>
    var i=51;  // in this you can show if condition is not satisified then it shows starting variable i=51; as 51in browser
    do{
        document.write(i+"<br>");
        i=i+2;// or i++
    }
    while(i<=50);
</script>

-->


<!--
//Switch conditon or Statement in JAVASCRIPT::=
<script>
    var marks=45;
   switch(true){
       case marks>90 : result="A Grade";
        break;
       case marks>75 : result="B Grade";
       break;
       case marks>60 : result="C Grade";
       break; 
       case marks>60 : result="C Grade";
       break; 
       case marks>50 : result="C Grade";
       break; 
       default : result="fail";
    
   }
   document.write(result);

</script>

-->
<!---
To Display Date and Time object in JAVASCRIPT:=
<script>
var today=new Date();
document.write(today)

</script>

//only Date year month seperately
<script>
var today=new Date();
var day=today.getDate();
var month=today.getMonth()+1;
var year=today.getFullYear();
document.write(day+"/"+month+"/"+year)
</script>;

//to call hours:=
<script>
    var today=new Date();
    var time=today.getHours();
    var mints=today.getMinutes();
    var sec=today.getSeconds();
    document.write(time+":"+mints+":"+sec)
</script>

//how to display present running time without refreshing broswer:=
<h1 id="madan"></h1>
<script>
function getTime(){
    var today=new Date();
    var h=today.getHours();
    var m=today.getMinutes();
    var s=today.getSeconds();
    document.getElementById("madan").innerHTML=h+":"+m+":"+s //by calling innerHTML we canm call correct time by calling it id usung html cocept
    setInterval("getTime()",1000);
        

}
getTime();
</script>
--->
<!----
strings objects in JAVASCRIPT:=
<script>
    var x="madan";  // its called concatnation method
    var y="hai ";
    document.write(y+" "+x)
</script>

<script>
    var x=new String("parchuri madan"); //to display words in letter as mention in number
    document.write(x.charAt(3));
    document.write(x.indexOf("madan")); // to identify position of word as number
    document.write(x.toLowerCase());// to print words in lower case
    document.write(x.toUpperCase()); // to print words in upper case
    document.write(x.slice(2,6));// to show words in between 2,6
</script>
--->
<!----
Maths objects in JAVASCRIPT:=
<script>
    var x=25;
    var y=35;
    document.write(Math.sqrt(x));//to find square root
   document.write(Math.random());// to find random numbers
   document.write(Math.pow(2,6));// to display power
   document.write(Math.abs(x));// to display absolute number
   
   </script>
   //to show round numbers for 4.5 as 5
   <script>
       var x=15.5;
       document.write(Math.floor(x));// floor method
       document.write(Math.ceil(x));// to display 1 to right side of point(.)
       document.write(Math.round(x));// to display round figure as 16 if its above (.5) if its below then (0.4) then it shows 15 only

   </script>
--->

<!----
//Browser object model (BOM):=

there are 6 types:=

1.  window object (alert,confirm,prompt,open,close,size,interval,timeout)

2. history object(back,forward)

3. Navigator Object (appName,appVersion,appCodeName,cookieEnabled,usreAgent,language,platform,product,javaEnabled)

4. Screen Object (width,height,colorDepth & pixelDepth)

5. Location Object (href, hostname, pathname, protocol(http.https), assign)

6. Cookies


1. window object (alert,confirm,prompt,open,close,size,interval,timeout):=
<script>
    window.alert("hello")
</script>
<script>
window.confirm("you are having error and virous")
</script>
<script>

 var    x=window.prompt("who are you?");
 document.write(x);// to display name which is written in box
</script>
<script>
    open("http://www.google.com")// to open google
</script>
<center>
<script>
    function google(){
        open("http://www.google.com");
    }
</script>
    <input type="button" value="gooogle"
      onclick="google()"/>
</center>


    <script>
        close();// to close browser
    </script>

<script>//size:=
    var w=window.innerWidth;// to didplay broswer width and height
    var h=window.innerHeight;
    document.write(w+" "+h)
</script>
//note:= you can use 1000 or mor if you required
<script>
    function myFunction(){
        alert("hello");

    }
    setInterval(myFunction,1000) //1000=1sec
</script>

<script>
    function myfunction(){
        alert("you are time is over");// to show message only its dnt repeat process

    }
    setTimeout(myfunction,1000);
</script>

\\end of window object


2. history object(back,forward):=//to display history of the browser

<script>
 function goback(){
    history.back();
 }   

</script>
<input type="button" value="back"  onclick="goback();" />

<script>
function gofor(){
    history.forward();
}
</script>
<input type="button" value="forward" onclick="gofor()" />


3.Navigator object (appName,appVersion,appCodeName,cookieEnabled,usreAgent,language,platform,product,javaEnabled):=
<script>
    document.write(navigator.appName);
</script>
<script>
    document.write(navigator.appVersion);
</script>
<script>
    document.write(navigator.appCodeName);
</script>
<script>
    document.write(navigator.cookieEnabled);
</script>
<script>
    document.write(navigator.userAgent)
</script>
<script>
    document.write(navigator.language)
</script>
<script>
    document.write(navigator.platform)
</script>
<script>
    document.write(navigator.product)
</script>
<script>
    document.write(navigator.javaEnabled())// javaEnabled is method
</script>


4. Screen object   (width,height,colorDepth & pixelDepth):=
//Width:=
<script>
    document.write(screen.width+"<br>");
    var w=window.innerWidth;
    document.write(w)
</script>

//Height:=
<script>
    document.write(screen.height+"<br>");
    var w=window.innerHeight;
    document.write(w)
</script>

//Color-depth:=
<script>
    document.write(screen.colorDepth);// instead of colorDepth we can also use pixelDepth

</script>



5.Location Object (href, hostname, pathname, protocol(http.https), assign):=

<script>
    document.write(location.href);
</script>

<script>
    document.write(location.hostname);
</script>

<script>
    document.write(location.pathname); 
</script>

<script>
    document.write(location.protocol); // there are two types of protocols:=
                                       //they are:=
                                             //    1. http
                                             //    2. https(secure)
</script>

<script>
    document.write(location.assign("http://www.google.com"));// assign() is a method from one website to another website
</script>


6.Cookies :=

--->

<!----
DOM (Document Object Model):=
                
                 With the help of DOM we can add dynamic xontent to our web page. Update the content, structure & style 
3 Methods

they are:=

1. write();

2. getElementById();

3.getElementByName();

1. write():=
<script>
    document.write("hello");
</script>

2. getElementById():=
<script>
    function getcube(){
        var num=document.getElementById("number").value;
        alert("this is cube"+num*num*num);
    }
</script>
  <form>
      Enter NUm: <input type="text" id="number">\
      <br/>
      <input type="button" value="Find cube" onclick="getcube()" />
  </form> 


3.getElementByName:=

<script>
    function printvalue(){
        var name1=document.form1.username.value;
        alert("welcome"+name1)
      
    }
</script>
  <form name="form1">
      Enter Name: <input type="text" name="username" >\
      <br/>
      <input type="button" value="print" onclick="printvalue()" />
  </form> 

DOM Properties:=

there are 3 types of properties:=

1. Changing Content

2. Changing Value

3. Changing Style


1. Changing Content:=

<p id="p1">Hello madan kumar</p>

<script>
  document.getElementById("p1").innerHTML="hai this madan kumar"
</script>

2. Changing Value:=

<img id="myimage" src="C:\Users\LEGION\OneDrive\Pictures\teddy bear.jpg">

<script>
  document.getElementById("myimage").src="C:\Users\LEGION\OneDrive\Desktop\unnamed.jpg";
</script>


3.Changing style:=

<p id="p2">Hello parchiri madan kumar</p>
<script>
    document.getElementById("p2").style.color="yellow";// changing color.
</script>
--></img>




<!--
**cookies in JAVASCRIPT***:=
 
they are 6 parts of a cookie:=

 they are:=

1. Name
            >-- Required  (this 2 are required)
2. Value

3. Expires
                 \/
4. Path
             >---- Optional  (this 4 are set as Optional)
5. Domain
                 /\       
6. Security

-

            how to create cookies:=
  
 document.cookie="username=Madan";
 document.cookie="username=Madan:
 expires=Wed,2 April 2022 9:52:00 UTC";
 
 
             Reading Cookies:=
             
var x- document.cookie;



<script>
  function setCookie(cname,cvalue,exdays){
      var d = new Date();
      d.setTime(d.getTime() + (exdays*24*60*60*1000));
      var expires = "expires=" + d.toGMTString();
      document.cookie = cname + " = "+ cvalue+" ; "+ expires + ";path=/";
  }

  function getCookie(cname){
      var name=cname + "=";
      var decodedCookie = decodeURIComponent(document.cookie);
      var ca = decodedCookie.split(';');
      for(var i = 0; i < ca.length; i++){
          var c = ca[i];
          while (c.charAt(0) == ' '){
              c = c.substring(1);
          }
          if (c.indexOf(name) == 0){
              return c.substring(name.length, ca.length);
          }
         
      }
      return " ";
  } 
  
  function checkCookie(){
        var user=getCookie("username");
        if (user != "" ){
            alert("welcome again"+ user);
        } else{
            user = prompt("Please enter your name:","");
            if (user != "" && user != null){
                setCookie("username",user,30);
            }
        }
    }

    //to call cookie we have to call   onload="checkCookie()"
</script> 


    onload ="checkCookie()">
 
--->


<!---
 Events in JAVASCRIPT:=

 there are 4 types of events:=

  1. onclick       \/

  2. ondblclick >---    these four are one catageory 

  3. onmouseover >---   
  
  4. onmouseout     /\

  
  
  5. onfocus         \/

  6. onblur      >----  these  three are one catageory   

  7. onchange         /\


  8. onload        \/

  9. onsubmit  >----  these three are one catageroy
 
  10. onreset      /\


1. onclick:=  


<h1 id="p1">hai this madan</h1>

<input type="button" onclick="event1()" value="click here"/>
  

<script>
    function event1(){
        document.getElementById("p1").innerHTML="hai this madan kumar parchuri"
    }
</script>

2. ondblclick:=
     
<h1 id="p1">hai this madan</h1>

<input type="button" ondblclick="event1()" value="click here"/>
  

<script>
    function event1(){
        document.getElementById("p1").innerHTML="hai this madan kumar parchuri"
    }
</script>

3. onmouseover:=

<h1 id="p1">hai this madan</h1>

<input type="button" onmouseover="event1()" value="click here"/>
  

<script>
    function event1(){
        document.getElementById("p1").innerHTML="hai this madan kumar parchuri"
    }
</script>

4. onmouseout:=

<h1 id="p1">hai this madan</h1>

<input type="button" onmouseout="event1()" value="click here"/>
  

<script>
    function event1(){
        document.getElementById("p1").innerHTML="hai this madan kumar parchuri"
    }
</script>


5. onfocus:=
   
   <h1 id="p1"></h1>

   <input type="text" onfocus="event1()" />

   <script>
       function event1(){
           document.getElementById("p1").innerHTML="yore almost near to the project"

       }
   </script>


6. onblur:=

 
<h1 id="p1"></h1>

<input type="text" onblur="event1()" />

<script>
    function event1(){
        document.getElementById("p1").innerHTML="yore almost near to the project"

    }
</script>


7. onchange:=

 
<h1 id="p1"></h1>

<input type="text" onchange="event1()" />

<script>
    function event1(){
        document.getElementById("p1").innerHTML="yore almost near to the project"

    }
</script>
        

8. onload:=

  
<h1 id="p1"></h1>

<input type="text" onload="event1()"  />

<script>
    function event1(){
        document.getElementById("p1").innerHTML=Date(); // you can date also after refreshing
        
    }
</script>

9. onsubmit:=


<h1 id="p1"></h1>
<form onsubmit="event1()">
    <input type="text"  name="name"  />
    <input type="submit" value="submit"  />
</form>

<script>
    function event1(){
        document.getElementById("p1").innerHTML="hai this madan"; // you can date also after refreshing
        
    }
</script>

10. onreset:=

<h1 id="p1"></h1>
<form onreset="event1()">
    <input type="text"  name="name"  />
    <input type="submit" value="submit"  />
    <input type="reset" value="reset" />
</form>

<script>
    function event1(){
        document.getElementById("p1").innerHTML="all values are clear"; // you can date also after refreshing
        
    }
</script>

--->
  
<!----
 //important   

*******Form validation***** :=

 1. Password validation

 2. Name Validation 

 3. Email validation

 4. Date Validation

 5. Mobile Number Validation


 
 1. Password validation:=
<center>
 <form  name="myform" method="post" onsubmit="return  validpassword()" action="Untitled-1.js">// action is used fro retriving to another site uif condition is true
<br><br>
password:<input type="password" name="pass1" >
<br><br>
confirm password:<input type="password" name="pass2">
<br><br>
<input type="submit" value="check">
</form>
<script>
    function validpassword(){
     var password=document.myform.pass1.value;
     var cpassword=document.myform.pass2.value;
     
     if(password.length<6){
         alert("password must contain 6 characters");
         return false;
     }
     
     if(password==cpassword){
         return true;
     }else{
         alert("password and confirm password must be same");
         return false;
     }
     
    }
</script>
</center>


 
 2. Name Validation:=
    
 <center>
    <form  name="myform" method="post" onsubmit="return  validname()" action="Untitled-1.js">// action is used fro retriving to another site uif condition is true
        <br><br>
        first name:<input type="text" name="name1" pattern="[a-zA-Z 0-9 ]{2,15}" title="name must have only letters and numbers"
         >
        <br><br>
       
        <input type="submit" value="check">
        </form>
 
        <script>
            function validname(){
                var name=document.myform.name1.value;
                

                if(name=="null" || name==""){
                    alert("please provide your name");
                return false;
                }
            }
        </script>
</center>




 3. Email validation:=
 
<center>
    <form  name="myform" method="post" onsubmit="return  validateemail()" action="Untitled-1.js">// action is used fro retriving to another site uif condition is true
        <br><br>
       Enter Your MaiiId:<input type="email" name="email1" required>
      <br><br>
      <input type="submit" value="Validate">
    </form>
    <script>
        function validateemail(){
            var email2=document.myform.email1.value;
            var  atposition=email2.indexOf("@");// we are indixing method
            var dotposition=email2.lastIndexOf(".");
         
             if(atposition<1 || dotposition<atposition+2 || dotposition+2>=email2.length){
                       
                alert("please enter valid email");
                return false;
             }
  
        }
    </script> 

</center>



 4. Date Validation(current date):=
 
 <center>
    <form  name="myform" method="post" onsubmit="return  validdate()" action="Untitled-1.js">// action is used fro retriving to another site uif condition is true
        <br><br>
       Enter your DOB:<input type="date" name="date1" required>
      <br><br>
      <input type="submit" value="Validate">
    </form>
    <script>
   function validdate(){
       var curdate=new Date();
       var dob2=new Date(document.myform.date1.value);
      
        if(dob2>curdate){
            alert("please provide your DOB");
            return false;
        }
   
    }
    </script>

 </center>
--->

 5. Mobile Number Validation:=


 <!---
  <form  name="myform" method="post" onsubmit="return  validnumber()" action="Untitled-1.js">// action is used fro retriving to another site uif condition is true
        <br><br>
       Enter Your MobileNUmber:<input type="number" name="mobile1" required>
      <br><br>
      <input type="submit" value="submit">
    </form>
    
    <script>
        function validnumber(){
            var  mobile2=document.myform.mobile1.value;

            if(mobile2.length==10){
                return true;
            }else{
                alert("enter 10 digit valid number");
                return false;
            }
        
        }
    </script>
    
                         or  // its for condition

     <form  name="myform" method="post" onsubmit="return  validnumber()" action="Untitled-1.js">// action is used fro retriving to another site if condition is true
        <br><br>
       Enter Your MobileNUmber with in a range of 5 to 15:<input type="number" name="mobile1" required>
      <br><br>
      <input type="submit" value="submit">
    </form>
    <script>
        function validnumber(){
            var  mobile2=document.myform.mobile1.value;

        if(mobile2<5 || mobile2>15){
          alert("Enter value with in a range");
          return false;
        }
        
        }
    </script>

--></br>      
        



<!--
**cookies in JAVASCRIPT***:=
 
they are 6 parts of a cookie:=

 they are:=

1. Name
            >-- Required  (this 2 are required)
2. Value

3. Expires
                 \/
4. Path
             >---- Optional  (this 4 are set as Optional)
5. Domain
                 /\       
6. Security

-

            how to create cookies:=
  
 document.cookie="username=Madan";
 document.cookie="username=Madan:
 expires=Wed,2 April 2022 9:52:00 UTC";
 
 
             Reading Cookies:=
             
var x- document.cookie;



<script>
  function setCookie(cname,cvalue,exdays){
      var d = new Date();
      d.setTime(d.getTime() + (exdays*24*60*60*1000));
      var expires = "expires=" + d.toGMTString();
      document.cookie = cname + " = "+ cvalue+" ; "+ expires + ";path=/";
  }

  function getCookie(cname){
      var name=cname + "=";
      var decodedCookie = decodeURIComponent(document.cookie);
      var ca = decodedCookie.split(';');
      for(var i = 0; i < ca.length; i++){
          var c = ca[i];
          while (c.charAt(0) == ' '){
              c = c.substring(1);
          }
          if (c.indexOf(name) == 0){
              return c.substring(name.length, ca.length);
          }
         
      }
      return " ";
  } 
  
  function checkCookie(){
        var user=getCookie("username");
        if (user != "" ){
            alert("welcome again"+ user);
        } else{
            user = prompt("Please enter your name:","");
            if (user != "" && user != null){
                setCookie("username",user,30);
            }
        }
    }

    //to call cookie we have to call   onload="checkCookie()"
</script> 


    onload ="checkCookie()">
 
--->


<!---
 Events in JAVASCRIPT:=

 there are 4 types of events:=

  1. onclick       \/

  2. ondblclick >---    these four are one catageory 

  3. onmouseover >---   
  
  4. onmouseout     /\

  
  
  5. onfocus         \/

  6. onblur      >----  these  three are one catageory   

  7. onchange         /\


  8. onload        \/

  9. onsubmit  >----  these three are one catageroy
 
  10. onreset      /\


1. onclick:=  


<h1 id="p1">hai this madan</h1>

<input type="button" onclick="event1()" value="click here"/>
  

<script>
    function event1(){
        document.getElementById("p1").innerHTML="hai this madan kumar parchuri"
    }
</script>

2. ondblclick:=
     
<h1 id="p1">hai this madan</h1>

<input type="button" ondblclick="event1()" value="click here"/>
  

<script>
    function event1(){
        document.getElementById("p1").innerHTML="hai this madan kumar parchuri"
    }
</script>

3. onmouseover:=

<h1 id="p1">hai this madan</h1>

<input type="button" onmouseover="event1()" value="click here"/>
  

<script>
    function event1(){
        document.getElementById("p1").innerHTML="hai this madan kumar parchuri"
    }
</script>

4. onmouseout:=

<h1 id="p1">hai this madan</h1>

<input type="button" onmouseout="event1()" value="click here"/>
  

<script>
    function event1(){
        document.getElementById("p1").innerHTML="hai this madan kumar parchuri"
    }
</script>


5. onfocus:=
   
   <h1 id="p1"></h1>

   <input type="text" onfocus="event1()" />

   <script>
       function event1(){
           document.getElementById("p1").innerHTML="yore almost near to the project"

       }
   </script>


6. onblur:=

 
<h1 id="p1"></h1>

<input type="text" onblur="event1()" />

<script>
    function event1(){
        document.getElementById("p1").innerHTML="yore almost near to the project"

    }
</script>


7. onchange:=

 
<h1 id="p1"></h1>

<input type="text" onchange="event1()" />

<script>
    function event1(){
        document.getElementById("p1").innerHTML="yore almost near to the project"

    }
</script>
        

8. onload:=

  
<h1 id="p1"></h1>

<input type="text" onload="event1()"  />

<script>
    function event1(){
        document.getElementById("p1").innerHTML=Date(); // you can date also after refreshing
        
    }
</script>

9. onsubmit:=


<h1 id="p1"></h1>
<form onsubmit="event1()">
    <input type="text"  name="name"  />
    <input type="submit" value="submit"  />
</form>

<script>
    function event1(){
        document.getElementById("p1").innerHTML="hai this madan"; // you can date also after refreshing
        
    }
</script>

10. onreset:=

<h1 id="p1"></h1>
<form onreset="event1()">
    <input type="text"  name="name"  />
    <input type="submit" value="submit"  />
    <input type="reset" value="reset" />
</form>

<script>
    function event1(){
        document.getElementById("p1").innerHTML="all values are clear"; // you can date also after refreshing
        
    }
</script>

--->
  
<!----
 //important   

*******Form validation***** :=

 1. Password validation

 2. Name Validation 

 3. Email validation

 4. Date Validation

 5. Mobile Number Validation


 
 1. Password validation:=
<center>
 <form  name="myform" method="post" onsubmit="return  validpassword()" action="Untitled-1.js">// action is used fro retriving to another site uif condition is true
<br><br>
password:<input type="password" name="pass1" >
<br><br>
confirm password:<input type="password" name="pass2">
<br><br>
<input type="submit" value="check">
</form>
<script>
    function validpassword(){
     var password=document.myform.pass1.value;
     var cpassword=document.myform.pass2.value;
     
     if(password.length<6){
         alert("password must contain 6 characters");
         return false;
     }
     
     if(password==cpassword){
         return true;
     }else{
         alert("password and confirm password must be same");
         return false;
     }
     
    }
</script>
</center>


 
 2. Name Validation:=
    
 <center>
    <form  name="myform" method="post" onsubmit="return  validname()" action="Untitled-1.js">// action is used fro retriving to another site uif condition is true
        <br><br>
        first name:<input type="text" name="name1" pattern="[a-zA-Z 0-9 ]{2,15}" title="name must have only letters and numbers"
         >
        <br><br>
       
        <input type="submit" value="check">
        </form>
 
        <script>
            function validname(){
                var name=document.myform.name1.value;
                

                if(name=="null" || name==""){
                    alert("please provide your name");
                return false;
                }
            }
        </script>
</center>




 3. Email validation:=
 
<center>
    <form  name="myform" method="post" onsubmit="return  validateemail()" action="Untitled-1.js">// action is used fro retriving to another site uif condition is true
        <br><br>
       Enter Your MaiiId:<input type="email" name="email1" required>
      <br><br>
      <input type="submit" value="Validate">
    </form>
    <script>
        function validateemail(){
            var email2=document.myform.email1.value;
            var  atposition=email2.indexOf("@");// we are indixing method
            var dotposition=email2.lastIndexOf(".");
         
             if(atposition<1 || dotposition<atposition+2 || dotposition+2>=email2.length){
                       
                alert("please enter valid email");
                return false;
             }
  
        }
    </script> 

</center>



 4. Date Validation(current date):=
 
 <center>
    <form  name="myform" method="post" onsubmit="return  validdate()" action="Untitled-1.js">// action is used fro retriving to another site uif condition is true
        <br><br>
       Enter your DOB:<input type="date" name="date1" required>
      <br><br>
      <input type="submit" value="Validate">
    </form>
    <script>
   function validdate(){
       var curdate=new Date();
       var dob2=new Date(document.myform.date1.value);
      
        if(dob2>curdate){
            alert("please provide your DOB");
            return false;
        }
   
    }
    </script>

 </center>
--->

5. Mobile Number Validation:=


<!---
 <form  name="myform" method="post" onsubmit="return  validnumber()" action="Untitled-1.js">// action is used fro retriving to another site uif condition is true
       <br><br>
      Enter Your MobileNUmber:<input type="number" name="mobile1" required>
     <br><br>
     <input type="submit" value="submit">
   </form>
   
   <script>
       function validnumber(){
           var  mobile2=document.myform.mobile1.value;

           if(mobile2.length==10){
               return true;
           }else{
               alert("enter 10 digit valid number");
               return false;
           }
       
       }
   </script>
   
                        or  // its for condition

    <form  name="myform" method="post" onsubmit="return  validnumber()" action="Untitled-1.js">// action is used fro retriving to another site if condition is true
       <br><br>
      Enter Your MobileNUmber with in a range of 5 to 15:<input type="number" name="mobile1" required>
     <br><br>
     <input type="submit" value="submit">
   </form>
   <script>
       function validnumber(){
           var  mobile2=document.myform.mobile1.value;

       if(mobile2<5 || mobile2>15){
         alert("Enter value with in a range");
         return false;
       }
       
       }
   </script>

-->


</body>
  
</html>
