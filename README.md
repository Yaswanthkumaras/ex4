# Ex04 Places Around Me
## Date: 26.04.2025

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
## map.html
```
<html>
    <head>
        <title>My City</title>
        </head>
        <body>
            <h1 align="'center">
                <font color="red"><b>Kangeyam</br></font>
            </h1>
            <h3 align="center">
                <font color="blue"><br>Yaswanth Kumar A S (212224230310)</br></font>
            </h3>
            <center>
                <img src="map.png" usemap="#mycity" height="610" width="1450">
                <map name="mycity">
                <area shape="rect" coords="700,250,900,900" href="home.html" title="My Home Town">
                <area shape="rect" coords="588,348,798,437" href="hotel.html" title="Gayathri Hotel">

                <area shape="rect" coords="304,31,472,132" href="bank.html" title="Fedral Bank">
                </map>
                </center>
        </body>       
</html> 

```
## hotel.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Gayathri Hotel</title>
    <style>
        body {
            background-color: lightblue;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            margin-top: 50px;
        }
        p {
            max-width: 800px;
            margin: 20px auto;
            font-size: 18px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <h1>gayathri Hotel</h1>
    <p>
        The hotel is situated near the bus stand on Tiruppur Road in Kangeyam, making it easily accessible for travelers. ​

        While specific details about the rooms and amenities at the Kangeyam location are limited, Gayathri Hotels are generally known for providing comfortable stays with essential facilities. Their branch in Tirupur, for instance, offers features like free Wi-Fi, 24x7 room service, air-conditioned rooms, and banquet halls suitable for various events.

    </p>
</body>
</html>

```
## bank.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Federal Bank</title>
    <style>
        body {
            background-color: lightblue;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            margin-top: 50px;
        }
        p {
            max-width: 800px;
            margin: 20px auto;
            font-size: 18px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <h1>Federal Bank</h1>
    <p>
        Federal Bank is one of the major private sector commercial banks in India, headquartered in Aluva, Kerala. Here's a quick overview:

Founded: 1931 (as Travancore Federal Bank)

Renamed: Became "Federal Bank Limited" in 1949

Type: Private sector bank

Headquarters: Aluva, Kochi, Kerala, India

Services:

Personal banking (savings accounts, loans, cards)

Corporate banking

NRI banking services (very strong NRI base, especially from the Middle East)

Internet and mobile banking

Investment services (mutual funds, insurance)


    </p>
</body>
</html>

```
## home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Kangeyam</title>
    <style>
        body {
            background-color: lightblue;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            margin-top: 50px;
        }
        p {
            max-width: 800px;
            margin: 20px auto;
            font-size: 18px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <h1>Kangeyam</h1>
    <p>
        Kangayam is a historical town and municipality in Tamil Nadu, India, known for its role as the capital of Kongu Nadu in ancient times. 
        It's also a significant center for agricultural processing, particularly rice and coconut oil. 
        The town is named after the Kangayam breed of draught cattle, known for their strength and ability to adapt to challenging conditions.
    </p>
</body>
</html>

```


## OUTPUT
![4](https://github.com/user-attachments/assets/05c74d89-d349-4ff9-84b2-651724559bef)

![3](https://github.com/user-attachments/assets/d8fc9607-a100-4026-b12f-a9d177cd3df0)

![2](https://github.com/user-attachments/assets/940e14a1-8cd9-465c-a946-a27effb2a767)
![1](https://github.com/user-attachments/assets/71a186b9-fced-4468-8fef-37d0900e5e37)


## RESULT
The program for implementing image maps using HTML is executed successfully.
