# Ex04 Places Around Me
## Date: 20-03-2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using <map> tag name the map.

### STEP 4
Create clickable regions in the image using <area> tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
### map.html
 ```html
 <html>
<head>
  <title>My City</title>
</head>
<body>
  <h1 align="center">
    <font color="red"><b>HOSUR</b></font>
  </h1>
  <h3 align="center">
    <font color="blue"><b>P SIRISHA (212224040321)</b></font>
  </h3>
  <center>
    <img src="./img/map.png" usemap="#MyCity" height="610" width="1450">
    <map name="MyCity">
      <area shape="rect" coords="690,310,790,350" href="home.html" title="My Home Town">
      <area shape="rect" coords="500,50,650,200" href="bengalaru.html" title="Bengaluru">
      <area shape="rect" coords="703,469,773,450" href="kelamangalam.html" title="Kelamangalam">
      <area shape="rect" coords="600,300,660,365" href="anekal.html" title="Anekal">
      <area shape="rect" coords="1021,485,1120,536" href="krishnagiri.html" title="Krishnagiri">
      <area shape="rect" coords="770,200,850,250" href="bagalur.html" title="Bagalur">
    </map>
  </center>
</body>
</html>
```
### home.html
 ```html
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="yellow">
  <h1 align="center">
    <font color="red"><b>HOSUR</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>Hosur - The Industrial Gateway of Tamil Nadu</b></font>
  </h3>

  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">
        Hosur, located in Tamil Nadu, is a rapidly growing industrial town known as the "Little England" of India for its pleasant climate. It serves as a hub for manufacturing industries, particularly in the automotive and electronics sectors, attracting professionals and businesses alike. The town is strategically positioned near Bengaluru, making it a crucial gateway for trade and connectivity. Hosur’s serene natural surroundings, including hillocks and lush greenery, add a touch of tranquility to its industrial prowess. The town is home to a variety of educational institutions, catering to the needs of its growing population. Its vibrant market spaces and thriving local economy reflect a blend of traditional and modern lifestyles. The transport infrastructure, including well-maintained roads and proximity to Bengaluru's airport, enhances its accessibility. Hosur also has a rich agricultural base, particularly famous for its roses and horticultural produce. The town offers a balanced lifestyle, combining work opportunities with peaceful living. With its steady development and strategic location, Hosur continues to be a prominent and promising destination in South India.</font>
      </p>
</body>
</html>
```

### bengaluru.html
 ```html
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="pink">
  <h1 align="center">
    <font color="red"><b>HOSUR</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>Bengaluru - Silicon valley of India</b></font>
  </h3>

  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">
        Bengaluru, the "Silicon Valley of India," is a thriving hub for technology, culture, and greenery, while Hosur, its neighboring town in Tamil Nadu, complements this vibrancy with its industrial prowess and tranquil charm. Bengaluru is renowned for its innovative spirit, housing numerous IT companies and startups, while Hosur shines as an industrial town with significant contributions to manufacturing and automobile industries. The cities share a geographical connection and are well-linked, making commuting between them convenient. While Bengaluru offers landmarks like Cubbon Park and Lalbagh Botanical Garden, Hosur is surrounded by scenic natural spots, such as hillocks and lakes. Bengaluru's lively culture embraces cosmopolitan art, food, and entertainment, while Hosur’s calm atmosphere provides a respite from city life. Both cities have thriving markets, with Bengaluru's bustling malls and bazaars contrasting Hosur's quieter local spaces. The combination of Bengaluru's modernity and Hosur's industrial heritage creates unique opportunities for career growth and living. Connectivity through highways and public transport ensures easy interaction between these two cities. Bengaluru's fast-paced urban lifestyle and Hosur's relaxed industrial vibe make the pairing an interesting balance. Together, they showcase a blend of technology, industry, and lifestyle, reflecting the dynamic face of Southern India.</font>
  </p>
</body>
</html>
```


### kelamangalam.html
```html
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="cyan">
  <h1 align="center">
    <font color="red"><b>HOSUR</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>Kelamangalam - The Tranquil Retreat of Tamil Nadu</b></font>
  </h3>

  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">
        Kelamangalam, a tranquil locality near Hosur, Tamil Nadu, is known for its serene environment and lush greenery. It offers a peaceful lifestyle, attracting those who seek a retreat from the hustle and bustle of city life. Hosur, on the other hand, is an industrial hub with a thriving manufacturing sector, making it a hotspot for career opportunities. The proximity between Kelamangalam and Hosur allows residents to enjoy the best of both worlds—nature's calm and urban amenities. Kelamangalam is developing rapidly, with residential plots and gated communities emerging as popular choices. Hosur complements this growth with its robust infrastructure, including schools, hospitals, and markets. The connectivity between the two areas is seamless, thanks to well-maintained roads and public transport options. Kelamangalam's scenic beauty, combined with Hosur's industrial vibrancy, creates a unique blend of lifestyle and work opportunities. Together, they represent a harmonious balance of development and tranquility in Tamil Nadu. Whether it's for living or investment, Kelamangalam and Hosur offer promising prospects for the future.</font>
      </p>
</body>
</html>
```


### anekal.html
``` html
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="green">
  <h1 align="center">
    <font color="red"><b>HOSUR</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>Anekal - The Serene Neighbor of Hosur</b></font>
  </h3>

  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">
        Anekal, located near Bengaluru, is a serene town that shares a close connection with Hosur, Tamil Nadu. Known for its peaceful environment, Anekal offers a refreshing contrast to Hosur's industrial vibrancy. The proximity between the two towns facilitates easy commuting, making them well-linked through roads and public transport. Anekal is surrounded by lush greenery and scenic landscapes, providing a tranquil retreat for residents and visitors. While Hosur thrives as an industrial hub, Anekal complements it with its residential charm and growing infrastructure. The town is gradually developing, with gated communities and educational institutions emerging to cater to its population. Anekal's calm atmosphere makes it an ideal place for those seeking respite from the hustle of urban life. Its connectivity to Hosur allows residents to enjoy the benefits of both industrial opportunities and serene living. Together, Anekal and Hosur represent a harmonious blend of development and tranquility. Their geographical and cultural proximity highlights the dynamic lifestyle of this region in South India.</font>
      </p>
</body>
</html>
```

### krishnagiri.html
``` html
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="Orange">
  <h1 align="center">
    <font color="red"><b>HOSUR</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>Krishnagiri - The Gateway of Tamil Nadu's Heritage</b></font>
  </h3>

  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">
        Krishnagiri, located near Hosur in Tamil Nadu, is a district renowned for its historical significance and natural beauty. Known as the "Mango Capital of India," it is famous for its abundant mango orchards and agricultural produce. The district serves as a gateway to Tamil Nadu, with Hosur being a key industrial town within its boundaries. Krishnagiri is rich in heritage, with ancient forts and temples that reflect its vibrant history. Its proximity to Hosur allows residents to benefit from industrial opportunities while enjoying the scenic landscapes of Krishnagiri. The district is well-connected through highways, making travel between Krishnagiri and Hosur seamless. Krishnagiri's serene environment contrasts with Hosur's bustling industrial vibe, offering a balanced lifestyle. Educational institutions and healthcare facilities in the region cater to the growing population. The district's development is steadily progressing, with infrastructure and tourism gaining momentum. Together, Krishnagiri and Hosur represent a dynamic blend of history, industry, and natural charm in Tamil Nadu.</font>
      </p>
</body>
</html>
```

### bagalur.html
``` html
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="violet">
  <h1 align="center">
    <font color="red"><b>HOSUR</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>Bagalur - The Educational and Emerging Hub</b></font>
  </h3>

  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">
        Bagalur, located near Hosur in Tamil Nadu, is a developing town known for its educational institutions and serene environment. It is strategically positioned just 10 kilometers from Hosur, making it an accessible and convenient location for residents and businesses. Bagalur is rich in greenery, offering a peaceful retreat from the industrial hustle of Hosur. The town is home to several government and private schools, contributing to its reputation as an educational hub. Its proximity to Hosur allows residents to benefit from the industrial opportunities while enjoying a quieter lifestyle. Bagalur is also known for its brick factories, which are a significant part of its local economy. The connectivity between Bagalur and Hosur is seamless, with well-maintained roads and transport options. The town's development is steadily progressing, with residential areas and infrastructure expanding. Bagalur's charm lies in its balance of rural tranquility and urban accessibility. Together with Hosur, it represents a dynamic blend of growth and serenity in Tamil Nadu.</font>
      </p>
</body>
</html>
```

## OUTPUT
![OUTPUT](/myproject/myapp/static/img/img1.jpg)

![OUTPUT](/myproject/myapp/static/img/img2.png)

![OUTPUT](/myproject/myapp/static/img/img3.png)

![OUTPUT](/myproject/myapp/static/img/img4.png)

![OUTPUT](/myproject/myapp/static/img/img5.png)

![OUTPUT](/myproject/myapp/static/img/img6.png)

![OUTPUT](/myproject/myapp/static/img/img7.png)






## RESULT
The program for implementing image maps using HTML is executed successfully.

