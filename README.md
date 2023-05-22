### Ex04 Places Around Me

### AIM

To develop a website to display details about the places around my house.

### DESIGN STEPS

### STEP 1

Create a Django admin interface.

### STEP 2

Download your city map from Google.

### STEP 3

Using ```<map>``` tag name the map.

### STEP 4

Create clickable regions in the image using ```<area>``` tag.

### STEP 5

Write HTML programs for all the regions identified.

### STEP 6

Execute the programs and publish them.

### CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Arakkonam</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>A.Aruvi (212222230014)</b></font>
</h3>
<center>
<img src="/static/images/new.png" usemap="#MyCity" >
<map name="MY PLACE">
<area shape="rectangle" coords="1154,213,1204,263" href="/static/html/poo.html"  title="poonamallee">
<area shape="rectangle" coords="749,153,848,192" href="/static/html/thiru.html" title="thiru">
<area shape="rectangle" coords="568,643,744,698" href="/static/html/lake.html" title="lake">
<area shape="rectangle" coords="231,489,333,526" href="/static/html/sec.html" title="saveetha">
<area shape="rectangle" coords="1063,949,1165,986" href="/static/html/kundrathur.html" title="kundrathur">
</map>
</center>
</body>
</html>

poo.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>ARAKKONAM</title>
    </head>
    <body bgcolor="lime">
    <h1 align="center">
    <font color="green"><b>Arakkonam reliance petrol bunk</b></font>
    </h1>
    <h3 align="center">
    <font color="purple"><b>Arakkonam reliance petrol bunk</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
    <font face="Georgia" size="5">
    1)The name "ARAKKONAM ",meaning FAMOUS: "Thiruthani Murugan Temple", Religious Sites.<br>
    2)Arakkonam is a relatively peaceful and quiet residential area.<br> 
    3)There is well-connected to other parts of Chennai, making it easy to communicate with every one </font>
    </p>
    </body>
</html>

thiruthani.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>thiruthani</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="green"><b>Arakkonam</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>Arakkonam</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
1)Thiruthani is famous for Murugan Temple, India.<br>2)It is located in Tiruvallur district,<br>
3)Located on the way to thiruthani bus stand, the neighbourhood is situated at a distance of 28 km from the city's kilometer zero.<br>
4) The nearest railway station is at thiruthani, which is 2 km away.</font>
</p>
</body>
</html>

lake.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>aggor lake </title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="green"><b>Arakkonam</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>aggor lake </b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
   1)aggor lake is a lake located in Thiruthani, Tamil Nadu, India<br>
   2) It is one of from where water is drawn  the other one being the Krishna samudram Lake.<br>
   3)A part of water supply of very beautiful .<br>
   4)This was the best lake . </font>
</p>
</body>
</html>

sec.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Saveetha University</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="green"><b>Thandalam</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>Saveetha University</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
1)SEC is a leading Engineering College located in Chennai, India.which offers a global approach to education and research, with a focus on global perspectives and expertise.<br>
2)SEC offers a wide range of undergraduate, postgraduate and doctoral programs in Engineering.<br>
3)Some of its Academic Highlights are, Only Engineering College in India to have 30 students per class. 98% results in University exam. 175 University Ranks. Compulsory internship every year.</font>
 </p>
</body>
</html>

kundrathur.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Kundrathur</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="green"><b>Thandalam</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>Kundrathur</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
    1)Kundrathur is a south western suburb of the city of Chennai, India and it comes under Kanchipuram District limits.<br>
    2)It is the birthplace of Sekkizhar, a well-known poet-saint who authored the Periyapuranam.<br>
    3)The locality is known for the Kundrathur Murugan Temple, one of the most popular temples in Chennai. </font>
</p>
</body>
</html> 
```

### OUTPUT

C:\Users\SEC\Pictures\111111.png

C:\Users\SEC\Pictures\1234.png

C:\Users\SEC\Pictures\12345.png

C:\Users\SEC\Pictures\123456.png


### HTML VALIDATOR

C:\Users\SEC\Pictures\Screenshot (195).png

### RESULT

The program for implementing image maps using HTML is executed successfully.
