# Image de-hazing and fog removal using DCP and CAP 

This is a simple image retrieval project from foggy and hazy images by using the methods of Dark Channel Prior and Colour Attenuation Prior. 

## Directions for Setting up Environment-

To install the source, pre-requisites include-

- Python 3.6 and above
- Dependencies from requirements.txt

First, clone this repository onto your system.
Then, create a virtual environment and install the packages from requirements.txt:
```
cd path/to/folder
virtualenv venv -p python3.6  //or any other name and version
source venv/bin/activate
```

Now, install the python dependencies from requirements.txt:
```
pip install -r requirements.txt
```

## Directions to execute-

Inside the main project directory, run the following command-

`python Dehaze.py images/(image_name) `

The second argument(of including images) is not compulsory, as it runs with the default image(foggy building) inside the images folder. To run with custom images, add/include that image inside the *images* folder, and then run the command as shown above.

Similarly for Color Attenuation Prior-

`python colour_attenuation.py images/(image_name)`

## References-

- [Dark Channel Prior](Dark_Channel_Prior.pdf)
- [Colour Attenuation Prior](Colour_Attenuation_Prior.pdf)
