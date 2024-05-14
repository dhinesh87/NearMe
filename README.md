# Ex04 Places Around Me
## Date: 

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
```
map.html
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">DHINESH.M (212223040040)
<font color="red"><b>Krishnagiri</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>DHINESH.M (212223040040)</b></font>
</h3>
<center>
<img src="Screenshot 2024-05-14 231752.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="home.html" title="My Home Town">
<area shape="circle" coords="570,230,45" href="temple.html" title="CHANDRA CHOODASWARAR TEMPLE">
<area shape="circle" coords="640,200,30" href="lake.html" title="Mayil Ravanan Lake">
<area shape="circle" coords="1120,360,25" href="dam.html" title="KPR dam">
<area shape="rect" coords="950,120,1100,140" href="park.html" title="Jim Corbett Park">
</map>
</center>
</body>
</html>

home.html

html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="cyan"><b>Krishnagiri</b></font>
</h1>
<h3 align="center">
<font color="red"><b>Uthangarai - My Home Town<sub>2</sub>Way</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Krishnagiri" size="5">
Uthangarai, my hometown nestled in the picturesque district of Krishnagiri, Tamil Nadu, holds a special place in my heart.Surrounded by rolling hills
and lush greenery, Uthangarai boasts a tranquil ambiance that soothes the soul. Its bustling markets, vibrant temples, and educational institutions form
the heartbeat of the town, fostering a sense of community and camaraderie among its residents. With its fertile lands yielding abundant crops and its rich
cultural heritage showcased through colorful festivals and traditional art forms, Uthangarai is not just a place on the map but a cherished home where
memories are made and traditions are upheld with pride.
</font>
</p>
</body>
</html>


temple.html
html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Krishnagiri</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>CHANDRA CHOODASWARAR TEMPLE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Krishnagiri" size="5">
The Chandra Choodaswarar Temple is a sacred Hindu shrine located in Hosur, a town in the Indian state of Tamil Nadu. Dedicated to Lord Shiva, this temple holds significant historical and religious importance, drawing devotees from far and wide.The temple's name, "Chandra Choodaswarar," translates to "the Lord who wears the crescent moon on his head," referring to Lord Shiva, who is often depicted with the crescent moon adorning his matted locks. Legend has it that this temple is where Lord Shiva blessed Chandra (the moon god) and relieved him of a curse, hence the association with the crescent moon.
One of the striking features of the Chandra Choodaswarar Temple is its architectural brilliance, showcasing the rich heritage of Dravidian architecture. The temple complex is adorned with intricate carvings, majestic towers (gopurams), and ornate pillars, reflecting the grandeur of ancient South Indian temple artistry.    
Devotees flock to the Chandra Choodaswarar Temple to seek blessings for various aspects of their lives, including prosperity, health, and harmony. The temple also holds religious festivals and ceremonies throughout the year, adding to its vibrant atmosphere. 
Apart from its religious significance, the Chandra Choodaswarar Temple also serves as a cultural hub, preserving age-old traditions and rituals passed down through generations. It stands as a testament to the enduring faith and devotion of the people of Tamil Nadu towards Lord Shiva.
Visiting the Chandra Choodaswarar Temple offers not just a spiritual experience but also a journey through history and artistry. Its serene ambiance and architectural splendor make it a must-visit destination for pilgrims and tourists alike, seeking solace and divine blessings amidst the bustling life of Hosur.   
</font>
</font>
</p>
</body>
</html>

lake.html

html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="purple">
<h1 align="center">
<font color="cyan"><b>Krishnagiri</b></font>
</h1>
<h3 align="center">
<font color="lime"><b>Mayil Ravanan Lake</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Krishnagiri" size="5" color="white"></font>>
Mayil Ravanan Lake, nestled in Krishnagiri district, Tamil Nadu, is a serene reservoir surrounded by lush greenery and rolling hills. 
Its tranquil waters reflect the clear blue skies above, creating a mesmerizing vista for visitors. The lake offers recreational activities 
like boating and fishing, while its cultural significance and association with local folklore add to its charm. A haven for birdwatchers and
 nature enthusiasts, Mayil Ravanan Lake invites visitors to unwind and connect with the beauty of the natural world in a serene setting.
</font>
</p>
</body>
</html>

 dam.html

 html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="cyan"><b>Krishnagiri</b></font>
</h1>
<h3 align="center">
<font color="red"><b>KPR dam<sub>2</sub>Way</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Krishnagiri" size="5" color="white">
The KPR Dam, situated in the Krishnagiri district of Tamil Nadu, India, is a vital water reservoir
serving both irrigation and drinking water needs in the region. Constructed across the Kunderipallam River, 
this dam stands as a testament to engineering prowess while providing a scenic backdrop against the surrounding hills. Its waters not
only facilitate agriculture but also offer opportunities for recreation and relaxation to locals and tourists alike. The KPR Dam plays
a crucial role in water management, ensuring sustainability and prosperity for the communities it 
</font>
</p>
</body>
</html>


park.html

html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="cyan"><b>Krishnagiri</b></font>
</h1>
<h3 align="center">
<font color="red"><b>Jim Corbett Park<sub>2</sub>Way</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Krishnagiri"5" color="white">
It seems there might be some confusion here. Jim Corbett National Park is actually located in the state of Uttarakhand,
not in Krishnagiri. Krishnagiri, a district in Tamil Nadu, doesn't have a park named after Jim Corbett. However, it's
possible that there might be a park or wildlife sanctuary in Krishnagiri, but it would have a different name. If you're 
interested, I can provide information about any parks or wildlife sanctuaries in Krishnagiri, just let me know!
</font>
</p>
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2024-05-14 232206.png>)
![alt text](<Screenshot 2024-05-14 232543.png>)
![alt text](<Screenshot 2024-05-14 232258.png>)
![alt text](<Screenshot 2024-05-14 232347.png>)
![alt text](<Screenshot 2024-05-14 232419.png>)
![alt text](<Screenshot 2024-05-14 232450.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
