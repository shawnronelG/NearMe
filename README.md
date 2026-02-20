# Ex03 Places Around Me
## Date: 20.2.2026

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

mapweb.html

<html>
 <head>
        <title>imageapp</title>
</head>
<body>

<h2 align="center">Chennai</h2>
<h2 align="center">SHAWN RONEL(25005544)</h2>


<img src="Screenshot 2026-02-20 082523.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Korattur Lake" title="Korattur Lake" href="lake1.html" coords="720,646,1038,455" shape="rect">
    <area target="" alt="Puzhal Lake" title="Puzhal Lake" href="lake2.html" coords="209,131,613,401,937,32" shape="poly">
    <area target="" alt="Home" title="Home" href="home.html" coords="873,338,28" shape="circle">
    <area target="" alt="Ayyappan Temple Surapet" title="Ayyappan Temple Surapet" href="temple.html" coords="788,320,51" shape="circle">
    <area target="" alt="Retteri Lake" title="Retteri Lake" href="lake3.html" coords="1251,87,1381,439" shape="rect">
</map>

</body>
</html>


lake3.html

<html>
<head><title>mapapp</title></head>
<body bgcolor="lightyellow">
<h3 align="center">RETTERI LAKE</h3>
<p>One of the bigestlake Chennai.</p>
<p>Popular among local fishermen.</p>
</body>
</html>



temple.html


<html>
<head><title>mapapp</title></head>
<body bgcolor="yellow">
<h3 align="center">IYYPAN TEMPLE</h3>
<p>a peaceful place </p>
<p>Popular among locals</p>
</body>
</html>


home.html


<html>
<head><title>mapapp</title></head>
<body bgcolor="black">
<h3 align="center">Home</h3>
<p>THE PLACE WHERE I LIVE</p>
<p>Popular among MY FAMILY</p>
</body>
</html>


lake2.html

<html>
<head><title>mapapp</title></head>
<body bgcolor="ORANGE">
<h3 align="center">PUHAL LAKE</h3>
<p>One of the bigestlake Chennai.</p>
<p>Popular among local fishermen.</p>
</body>
</html>

lake1.html

<html>
<head><title>mapapp</title></head>
<body bgcolor="BLUE">
<h3 align="center">KORATTUR LAKE</h3>
<p>One of the bigest lake Chennai.</p>
<p>Popular among local fishermen.</p>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2026-02-20 084614.png>) ![alt text](<Screenshot 2026-02-20 084709.png>) ![alt text](<Screenshot 2026-02-20 084653.png>) ![alt text](<Screenshot 2026-02-20 084639.png>) ![alt text](<Screenshot 2026-02-20 084629.png>) ![alt text](<Screenshot 2026-02-20 084622.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
