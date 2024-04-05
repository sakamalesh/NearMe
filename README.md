# Ex04 Places Around Me
## Date: 5/4/24

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

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

## CODE
'''
<html>
    
    <head>
        <title>My city</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Sripermbudur</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>kamalesh s</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#Mycity" height="610" width="1450">
            <map name="Mycity">
                <area shape="circle" coords="300,300,900,900" href="hotspot.html" title="hotspot">
                <area shape="circle" coords="500,500,800,800" href="home.html" title="My home">
                <area shape="circle" coords="250,250,600,600" href="temple.html" title="Temple">
                <area shape="circle" coords="400,400,500,500" href="hotspot.html" title="hotspot">
                <area shape="circle" coords="600,600,700,700" href="lake.html" title="lake">
            </map>
        </center>
    </body>
    
</html>

'''

## OUTPUT

![alt text](<Screenshot 2024-04-05 172929.png>)
![alt text](<Screenshot 2024-04-05 171722.png>)
![alt text](<Screenshot 2024-04-05 172849.png>)
![alt text](<Screenshot 2024-04-05 172005.png>)
![alt text](<Screenshot 2024-04-05 171821.png>)
![alt text](<Screenshot 2024-04-05 172849.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
