### DEPRECATED

[Codeforplotting2](https://github.com/HugoBruins/cancatchers/tree/master/python/codeforplotting%202) is used to plot all the data now.

# Information

The code makes 3 different plots as of now, one has all the data graphs of altitude, pressure, temperature, wind / horizontal speed. The other graph is a 2d map with all the latitude and longitude information plotted and the third graph is a 3 dimensional graph that has latitude and longitude, but also altitude information plotted, sadly I cannot get a nice image of the map for the 3d graph. 

The data from these pictures is taken from a caveman distance test with our old transceiver modules. 

## How to get the code working

Make sure you have a nice python editor installed, and install the following libraries for python using pip:

- matplotlib
- pandas
- numpy

Now drop **_code_for_plotting.py_** into a folder, and also drop **_your_cansat_data.txt_** and **_map.png_** in that same folder, and run **_code_for_plotting.py_**. The code works if you get exactly the same graphs as given in the pictures at the bottom of this readme. 

## How can I use my own text file name?

Go to the top of the code and change the **_data_file_name_** variable to your own file name. (don't forget the .txt)

## How can I get my own map image?

- Run the code once with your own data file
- In the console it will print a boundary box ( (4.96607, 4.970542, 51.848461, 51.852519) for the example in the github ) These are the maximum / minumum longitudes and latitudes.
-  Go to [openstreetmap](https://www.openstreetmap.org/export#map=5/53.488/5.757 "openstreetmap") and fill in these values in the box over at the left side. 
-  Now go to the top right corner and press the 'share' button.
-  Here check the box 'modified picture dimensions', and manually drag the corners of the new appearing box over the old one that fits the given boundary
-  Pick a nice scale that gives good image resolution and download the png.
-  Change the name of this png to map.png and drop it into the same folder as the code.


## Graphs:

### The temperature / pressure / wind speed / altitude plot
![data graphs](https://user-images.githubusercontent.com/25268098/121771673-032dac80-cb71-11eb-835e-5add11a95b53.png)

### The 2d map plot
![2d map](https://user-images.githubusercontent.com/25268098/121771681-10e33200-cb71-11eb-9bb5-a613e46859bd.png)

### The 3d map plot
![3d map](https://user-images.githubusercontent.com/25268098/121771595-94505380-cb70-11eb-9d5d-ccbaeb07c86f.png)
