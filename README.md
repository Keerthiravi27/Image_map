# Ex04 Places Around Me
# Date:14/04/2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
'''
map.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Kanchipuram</b></font>
        </h1>
        <h3 align=center>
            <font color="blue"><b>Keerthana R (212224040156)</b></font>
        </h3>
        <center>
            <img src="map.png" usermap="MyCity" height="610" width="1450">
            <map name="MyCity">
               

    <area target="" alt="Hotel Ramco Residency" title="Hotel Ramco Residency,Kanchipuram" href="ramco.html" coords="816,153,1091,221" shape="rect">
    <area target="" alt="Kamakshi Temple" title="Kamakshi Temple" href="temple.html" coords="893,220,1198,260" shape="rect">
    <area target="" alt="Kanchi Kudil" title="Kanchi Kudil" href="kudil.html" coords="437,628,749,709" shape="rect">
    <area target="" alt="Damro Furniture" title="Damro Furniture" href="damro.html" coords="891,412,1218,463" shape="rect">
                
            </map>
        </center>
    </body>
</html>

temple.html

<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    <body bgcolor="pink"
<h1 align="center">
    <font color=""black"><b>Kanchipuram</b></font>
</h1>
<h3 align="center">
    <font color="blue"><b>Kamakshi Amman Temple</b></font>
</h3>
<hr size="3 color="red">
<p align="justify">
    <font face="Georgia" size="5">
        The temple's main diety is goddess Parvathi.This temple is famous for tourist spot.
    </font>
</p></body>
</html>

kudil.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgclor="purple">
        <h1 align="center">
            <font color="blue"><b>Kanchipuram</b></font>
        </h1>
        <h3 align="center">
            <font color="yellow"><b>Kanchi Kudil</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                Kanchi Kudil is an ancestoral house. There we can see lots of antique things. They still maintain the traditional culture.
            </font>
        </p>
    </body>
</html>

damro.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="red"><b>Kanchipuram</b></font>
        </h1>
        <h3 align="center">
            <font color="pink"><b>Damro Furniture</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                Damro furniture is one of the famous furniture shops in kanchipuram.
            </font>
        </p>
    </body>
</html>

ramco.html

<html>
    <head>
        <body bgcolor="red">
            <h1 align="center">
                <font color="cyan"><b>Kanchipuram</b></font>
            </h1>
            <h3 align="center">
                <font color="blue"><b>Ramco Residency</b></font>
            </h3>
            <hr size="3" color="green">
            <p align="justify">
                <font face="Georgia" size="5" color="white">
                    Ramco Residency which is located in Kanchipuram is a residency lodge for touristers and outer area people.
                </font>
            </p>
        </body>
    </head>
</html>

'''
# OUTPUT
![alt text](keerthi/mapapp/static/map.png)

![alt text](keerthi/mapapp/static/damro.png)

![alt text](keerthi/mapapp/static/1.damro.png)

![alt text](keerthi/mapapp/static/kudil.png)

![alt text](keerthi/mapapp/static/1.kudil.png)

![alt text](keerthi/mapapp/static/ramco.png)

![alt text](keerthi/mapapp/static/1.ramco.png)

![alt text](keerthi/mapapp/static/temple.png)

![alt text](keerthi/mapapp/static/1.temple.png)

# RESULT
The program for implementing image maps using HTML is executed successfully.
