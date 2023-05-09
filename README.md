# Ex.04 Images as Hyperlinks
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
 ```
 <html>
<body>
<h1>Horticulture</h1>
<a href="https://www.canr.msu.edu/hrt/about-us/horticulture_is#:~:text=Horticulture%20is%20the%20science%20and,Decorative%20indoor%20plants%20and">
<img src="001.JPG"
width="200" height="200"></a>
<br>
<br>
<h1>Irrigation</h1>
<a href="https://en.wikipedia.org/wiki/Irrigation#:~:text=Irrigation%20(also%20referred%20to%20as,many%20cultures%20around%20the%20world.">
<img src="002.JPG"  width="200" height="200"></a>
<br>
<br>
<h1>Apiculture</h1>
<a href="https://www.nal.usda.gov/animal-health-and-welfare/beekeeping#:~:text=Apiculture%20%2D%20the%20maintenance%20of%20honeybees,of%20bees%20to%20other%20beekeepers.">
<img src="003.JPG"
width="200" height="200"></a>
<br>
<br>
<br>
<h1>Organic Fertilizer</h1>
<a href="https://www.sciencedirect.com/topics/agricultural-and-biological-sciences/organic-fertilizer#:~:text=Organic%20fertilizer%20refers%20to%20those,digestate%20and%20other%20bio%2Dwastes.">
<img src="004.JPG"
width="200" height="200"></a>
<br>
<br>
<br>
<h1>Harvester</h1>
<a href="https://www.tractorjunction.com/tractor-combine-harvesters/#:~:text=Harvester%20is%20a%20multipurpose%20farming,helps%20to%20generate%20higher%20income.">
<img src="005.JPG"
width="200" height="200"></a>
</body>
</html>
```


## OUTPUT

![Screenshot (45)](https://user-images.githubusercontent.com/127816678/236992045-1a795669-5fa3-4d7a-b30d-f02ec3042477.png)


## RESULT
 Images as hyperlinks is implemented successfully.
