# Ex03 Places Around Me
## Date: 05/12/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>map</title>
</head>
<body>
    <h1 align="center">Cuddalore</h1>
    <h3 align="center">Dineshkarthikeyan.V(25012548)</h3>
    <img src="map.png" usemap="#image-map">
    <map name="#image-map">
        <area target="" alt="silver Beach" title="silver Beach" href="silver.html" coords="1508,625,85" shape="circle">
        <area target="" alt="hotal Devi" title="hotal Devi" href="Devi.html" coords="933,675,1102,740" shape="rect">
        <area target="" alt="temple" title="temple" href="temple.html" coords="1275,375,1468,431" shape="rect">
        <area target="" alt="reliance" title="reliance" href="reliance.html" coords="876,371,1063,441" shape="rect">
        <area target="" alt="ck" title="ck" href="ck.html" coords="1048,769,1127,794,1197,782,1201,744,1079,742" shape="poly">
    </map>
</body>
</html> 


temple.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>temple</title>
</head>
<body bgcolor="blue">
    <h1 align="center">Cuddalore</h1>
    <h3 align="center">Dineshkarthikeyan.V(25012548)</h3><hr>

    <p>  The temple is located on the outskirts of Chidambaram in Cuddalore district, Tamil Nadu. </p><p>
It was built by the 13th-century chieftain/king Kopperunjingan (who ruled between 1229 and 1278).</p>
    
</body>
</html>


Devi.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ck</title>
</head>
<body bgcolor="gray">
    <h1 align="center">Cuddalore</h1>
    <h3 align="center">Dineshkarthikeyan.V(25012548)</h3><hr>

    <p>Hotel Devi is a well-known hotel / restaurant in Cuddalore, located on Chidambaram Main Road / NH 45A (near Tirupadiripuliyur / Sellankuppam area).</p><p>
It appears listed under “budget / mid-range” hotels and eating places — sometimes also appearing as “OYO 40120 Hotel Devi” (i.e. listed under hotel-booking/room-rental + restaurant) when the accommodation plus food option is needed.</p>
    
</body>
</html>

silver.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ck</title>
</head>
<body bgcolor="yellow">
    <h1 align="center">Cuddalore</h1>
    <h3 align="center">Dineshkarthikeyan.V(25012548)</h3><hr>

    <p>It’s relatively peaceful and less crowded than more commercialized tourist-beaches. Great for relaxing, sunrise/sunset walks, or spending quiet time by the sea.</p><p>
The long stretch of soft sand and shoreline is good for walking, beach strolls.</p>
    
</body>
</html>


reliance.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>reliance</title>
</head>
<body bgcolor="red">
    <h1 align="center">Cuddalore</h1>
    <h3 align="center">Dineshkarthikeyan.V(25012548)</h3><hr>

    <p>There is a store called Reliance SMART Superstore at Shop No 1, Chavadi Road, Vinayaga Nagar, Kondur, Cuddalore 607001.</p><p>For electronics and household gadgets, there is a store called Reliance Digital at No 24 A/30, Ground & 1st Floor, Bharathi Road, Pudupalayam, Cuddalore 607001.</p>
    
</body>
</html>


ck.html



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ck</title>
</head>
<body bgcolor="sky blue">
    <h1 align="center">Cuddalore</h1>
    <h3 align="center">Dineshkarthikeyan.V(25012548)</h3><hr>

    <p>CK College of Engineering & Technology (CKCET) was established in 2002, originally under the name Sri Jayaram Engineering College.</p><p>
In 2010, its management was taken over by CavinKare (a private business group), and the college was renamed CKCET.</p>
    
</body>
</html>



```

## OUTPUT

![alt text](<Screenshot (33).png>)<br> ![alt text](<Screenshot (28).png>)<br> ![alt text](<Screenshot (29).png>)<br> ![alt text](<Screenshot (30).png>) <br>![alt text](<Screenshot (31).png>)<br> ![alt text](<Screenshot (32).png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
