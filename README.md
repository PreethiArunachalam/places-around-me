# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Write your own steps here.
### Step 2:
Create a new Django project.
### Step 3:
Write the needed HTML code.
### Step 4:
Run the Django server and execute the HTML files.

## Code:
```
### map.html:
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Tirunelveli-Oxford Of TamilNadu</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Preethi (212222110035)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/ghs.html" title="Nellaiappar Temple">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/rto.html" title="Thamirabarani">
<area shape="circle" coords="400,350,50" href="/static/html/vk.html" title="Palayamkottai">
<area shape="circle" coords="400,200,75" href="/static/html/bus.html" title="Tirunelveli Medical College">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/park.html" title="Panchalankurichi Fort">
</map>
</center>
</body>
</html>

### place.html:
<!DOCTYPE html>
<html lang="en">
<head>
<title>Palayamkottai</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Tirunelveli-Oxford Of TamilNadu</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Oxford of TamilNadu</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Palayamkottai is called the Oxford of South India as it has many schools and colleges.
Palayamkottai is a residential and educational centre in the Tirunelveli urban agglomeration.
A major hub for Christian missions in southern India.
It has private Christian schools and colleges.
It has other colleges affiliated with Manonmaniam Sundaranar University in Tirunelveli.
</b>
</font>
</p>
</body>
</html>

### fort.html:
<!DOCTYPE html>
<html lang="en">
<head>
<title>Fort</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Tirunelveli-Oxford Of TamilNadu</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Panchalankurichi Fort</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
Panchalankurichi is best known as the birthplace of Veerapandiya Kattabomman,an 18th-century Palayakarrar ('Polygar'),
who opposed the British East India Company governance in the area and its revenue-raising methods.
The existing Memorial Fort was constructed in 1974, by the government of Tamilnadu.
The Memorial hall, has beautiful paintings depicts the heroic deeds of the saga which give a good idea about 
the history of the period.
Sri Devi Jakkammal Temple, the hereditary Goddess of Kattabomman, is located in the fort complex.
</font>
</p>
</body>
</html>

### college.html:
<!DOCTYPE html>
<html lang="en">
<head>
<title>Tirunelveli Medical College</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Tirunelveli-Oxford Of TamilNadu</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Tirunelveli Medical College</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
<b>
Tirunelveli Medical College was established in the year 1965 under the affiliation to the Tamil Nadu 
Dr. MGR Mdical University, Chennai and administered by the Directorate of Medical Education of the Government of Tamil Nadu.
The government Hospital was well equipped with all the basic and latest technology.
The teachers were well known and few of the best doctors from India, the exposure provided was very unique.
The campus was ragging free and was very friendly.
</b>
</font>
</p>
</body>
</html>

### temple.html:
<!DOCTYPE html>
<html lang="en">
<head>
<title>Nellaiappar Temple</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Tirunelveli-Oxford Of TamilNadu</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Nellaiappar Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
The Nellaiappar Temple is considered to be a big temple in the city with five Gopurams.
It spreads over 850 feet long and 756 feet wide in the middle of the city. 
There is a belief that Lord Shiva, and Lord Brahma are disguised as water and lotus respectively.
Veerabhadra stands for courage, and a mother holding her child stands for feminine. 
In addition to this, the columns with cock fight, the elopement of Arjunan.
The shrine of Arumuganainar is chiseled from a single stone which is above Lord Shiva’s sannathi.
Devotees can see all the six faces of Lord Arumugaperuman.

</b>
</font>
</p>
</body>
</html>

### river.html:
<!DOCTYPE html>
<html lang="en">
<head>
<title>Thamirabarani</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Tirunelveli-Oxford Of TamilNadu</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Thamirabrani</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
<b>
Thamirabarani River also known as Tambraparni.
This river originates from the Arrival Hills of Papanasam taluk in the Thanjavur district of Tamil Nadu.
It is the largest reservoir of Snakehead in the world with 17 types of Snakeheads present in this river.
Snakehead fishes are locally called as Viraal in Tamil.
All the species are consumed as food around the regions of Thamirabarani when they enter paddy fields.
</b>
</font>
</p>
</body>
</html>
```
## Output:

![image](https://user-images.githubusercontent.com/120115840/233788857-b1e08a31-e716-44d6-9cdb-5b2ebcaa45c0.png)

![image](https://user-images.githubusercontent.com/120115840/233788885-8e1574f8-fb68-4087-816d-e50c36191b33.png)

![image](https://user-images.githubusercontent.com/120115840/233788909-1052b00b-f898-4cec-a122-3511077d3086.png)

![image](https://user-images.githubusercontent.com/120115840/233788931-0089f3fa-c377-40d9-be0f-5c6de4f321b4.png)

![image](https://user-images.githubusercontent.com/120115840/233788944-49e1741f-8e94-4313-915f-6570bcb310f9.png)

![image](https://user-images.githubusercontent.com/120115840/233788952-8e303e6f-db4d-4a42-8878-79a73938ad50.png)

![image](https://user-images.githubusercontent.com/120115840/233789127-d8396984-f53b-4a2c-acf6-b1424653b50e.png)

![image](https://user-images.githubusercontent.com/120115840/233789157-a0c83c14-b200-45db-beea-3081353734a3.png)

## Result:
Thus a website to display details about the places in map is successfully executed and displayed.
