# Ex04 Places Around Me
## Date: 22/09/2025

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
<!DOCTYPE html>
<html>
<head>
    <title>My City</title>
</head>
<body>
    <h1 align="center">
        <font color="red"><b>KRISHNAGIRI</b></font>
    </h1>

    <h3 align="center">
        <font color="blue"><b>MANOJ KUMAR N (25015346)</b></font>
    </h3>

    <center>
        <img src="map.png"   alt="My City" usemap="#MyCity">
         <map name="MyCity">
         
            <area target="_blank" alt="GOVERNMENT ARTS COLLEGE" title="GOVERNMENT ARTS COLLEGE" href="Artscollege.html" coords="1124,253,1360,364" shape="rect">
            <area target="_blank" alt="DISTRICT COURT" title="DISTRICT COURT" href="court.html" coords="290,388,566,500" shape="rect">
            <area target="_blank" alt="KRISHNAGIRI FORT" title="KRISHNAGIRI FORT" href="krishnagirifort.html" coords="762,162,970,264" shape="rect">
            <area target="_blank" alt="OLD PET" title="OLD PET" href="oldpet.html" coords="750,321,851,376" shape="rect">
        </map>
    
      
                     
       
    </center>
</body>
</html>
   <!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Government Arts Colleges in Krishnagiri</title>
  <style>
    body{font-family:Arial, sans-serif; background:#f9f9f9; margin:0; padding:0;}
    .container{max-width:900px;margin:30px auto;padding:20px;background:#fff;border-radius:10px;box-shadow:0 4px 12px rgba(0,0,0,0.1);}
    h1{text-align:center;color:#2b6cb0;}
    table{width:100%;border-collapse:collapse;margin-top:20px;}
    th, td{border:1px solid #ccc;padding:12px;text-align:left;}
    th{background:#2b6cb0;color:#fff;}
    tr:nth-child(even){background:#f2f2f2}
  </style>
</head>
<body>
  <div class="container">
    <h1>Government Arts Colleges in Krishnagiri</h1>
    <table>
      <thead>
        <tr>
          <th>College Name</th>
          <th>Established</th>
          <th>Affiliation</th>
          <th>Location</th>
          <th>Courses Offered</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Government Arts College for Men, Krishnagiri</td>
          <td>1964</td>
          <td>Periyar University</td>
          <td>6 km from Krishnagiri town</td>
          <td>UG, PG, M.Phil, Ph.D in Arts, Science, Commerce</td>
        </tr>
        <tr>
          <td>Annai Sathiya Government Arts College for Women, Krishnagiri</td>
          <td>1992</td>
          <td>Periyar University</td>
          <td>Near district sports stadium, Krishnagiri</td>
          <td>UG, PG, Research in Tamil, English, Math, Biochemistry, Computer Science</td>
        </tr>
      </tbody>
    </table>
  </div>
</body>
</html>



<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Krishnagiri Fort</title>
  <style>
    body{font-family:Arial, sans-serif; background:#f9f9f9; margin:0; padding:0;}
    .container{max-width:800px;margin:30px auto;padding:20px;background:#fff;border-radius:10px;box-shadow:0 4px 12px rgba(0,0,0,0.1); text-align:center;}
    h1{color:#2b6cb0;}
    ul{margin-top:20px; display:inline-block; text-align:left;}
    ul li{margin:10px 0;line-height:1.6;}
  </style>
</head>
<body>
  <div >
    <h1>Krishnagiri Fort</h1>
    <ul>
      <li><strong>Location:</strong> Krishnagiri town, Tamil Nadu, about 90 km from Bengaluru.</li>
      <li><strong>Historical Origin:</strong> Built during the Vijayanagara Empire and later reinforced by Tipu Sultan.</li>
      <li><strong>Strategic Position:</strong> Stands on a hill, offering wide views and used as a military stronghold.</li>
      <li><strong>Battles:</strong> Witnessed wars, especially during the Anglo–Mysore conflicts with the British.</li>
      <li><strong>Architecture:</strong> Made of granite stones with gateways and defensive walls.</li>
      <li><strong>Tourist Spot:</strong> Today, it attracts history lovers and trekkers for its scenic beauty.</li>
    </ul>
  </div>
</body>
</html>



<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Krishnagiri District Court</title>
  <style>
    body{font-family:Arial, sans-serif; background:#f9f9f9; margin:0; padding:0;}
    .container{max-width:800px;margin:30px auto;padding:20px;background:#fff;border-radius:10px;box-shadow:0 4px 12px rgba(0,0,0,0.1);}
    h1{text-align:center;color:#2b6cb0;}
    ul{margin-top:20px;}
    ul li{margin:10px 0;line-height:1.6;}
  </style>
</head>
<body>
  <div class="container">
    <h1>Krishnagiri District Court</h1>
    <ul>
      <li><strong>Location:</strong> Krishnagiri, Tamil Nadu, India.</li>
      <li><strong>Type:</strong> District Court handling civil, criminal, and other legal matters.</li>
      <li><strong>Jurisdiction:</strong> Covers all legal cases arising in Krishnagiri district.</li>
      <li><strong>Facilities:</strong> Court halls, administrative offices, legal aid services.</li>
      <li><strong>Official Website:</strong> <a href="https://districts.ecourts.gov.in/krishnagiri" target="_blank">https://districts.ecourts.gov.in/krishnagiri</a></li>
    </ul>
  </div>
</body>
</html>



<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Old Pet, Krishnagiri</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f9f9f9; margin: 0; padding: 0; }
    .container { max-width: 900px; margin: 30px auto; padding: 20px; background: #fff; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.1); }
    h1 { text-align: center; color: #2b6cb0; }
    ul { margin-top: 20px; }
    ul li { margin: 10px 0; line-height: 1.6; }
    .image-gallery { display: flex; justify-content: space-between; margin-top: 20px; }
    .image-gallery img { width: 32%; border-radius: 8px; }
  </style>
</head>
<body>
  <div class="container">
    <h1>Old Pet, Krishnagiri</h1>
    <ul>
      <li><strong>Location:</strong> Old Pet is a locality in Krishnagiri city, Tamil Nadu, India. It is situated under the postal code 635001, with the Krishnagiri Head Post Office serving the area. Nearby localities include Moham Rao Colony, Veerappa Nagar, and Kottai. <a href="https://www.onefivenine.com/india/villages/Krishnagiri/Krishnagiri/Old-Pet">Source</a></li>
      <li><strong>Religious Significance:</strong> The locality is home to several temples, including the Hanuman Temple. These temples are central to the community's religious activities and festivals. <a href="https://www.mappls.com/place-hanuman%2Btemple-old%2Bpet-krishnagiri-tamil%2Bnadu-635001-HB6QIM">Source</a></li>
      <li><strong>Cultural Events:</strong> Old Pet hosts various cultural and religious events, such as the annual bull race festival held on Netaji Road. This event attracts thousands of spectators and features over 300 bulls from neighboring areas. <a href="https://timesofindia.indiatimes.com/city/coimbatore/spectator-gored-to-death-at-bull-race-in-krishnagiri/articleshow/122032978.cms">Source</a></li>
      <li><strong>Educational Institutions:</strong> The area is served by several schools, including Sri Vijay Vidyalaya Matric High School, providing education to the local community. <a href="https://www.justdial.com/Krishnagiri/Sri-Vijay-Vidyalaya-Matric-High-School-Old-Pet-Old-Pet/9999P4343-4343-221209023223-Z4P9_BZDET">Source</a></li>
      <li><strong>Commercial Activities:</strong> Old Pet hosts various businesses, including the Oldpet Fish Market, which is popular among locals for fresh seafood. <a href="https://www.justdial.com/Krishnagiri/Oldpet-Fish-Market-Old-Pet/9999P4343-4343-180316212820-A1T1_BZDET">Source</a></li>
    </ul>
   
    </div>
  </div>
</body>
</html>

```

# OUTPUT
![alt text](<KRISHNAGIRI MAP.png>)
![alt text](<GOVERNMENT ARTS COLLEGE.png>)


![alt text](<KRISHNAGIRI FORT.png>)
![alt text](<DISTRICT COURT.png>)

![alt text](<OLD PET.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
