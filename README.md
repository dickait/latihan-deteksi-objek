1. Download dataset di https://www.kaggle.com/datasets/rhammell/ships-in-satellite-imagery
2. Extract dan copy ke folder project ini
3. Rename folder tersebut ke kaggle-satellite-imagery

## Ships in Satellite Imagery Dataset
* The specific Dataset includes 4000 images labeled with either a "ship" or "no-ship" classification.
* These 4000 images are in .png format and have dimensions of 80 × 80 pixels. 
* The colour depth of the above 4000 images is 24 bit (8 bits per channel).
* Image chips were derived from PlanetScope full-frame visual scene products, which are orthorectified to a 3 meter pixel size.
* The "ship" class includes 1000 images which are near-centered on the body of a single ship. 
* Ships of different sizes, orientations, and atmospheric collection conditions are included.
* Each individual image filename follows a specific format: {label} __ {scene id} __ {longitude} _ {latitude}.png
  * label: Valued 1 or 0, representing the "ship" class and "no-ship" class, respectively.
  * scene id: The unique identifier of the PlanetScope visual scene the image chip was extracted from. 
  * longitude_latitude: The longitude and latitude coordinates of the image center point, with values separated by a single underscore.
* Dataset Link: https://www.kaggle.com/rhammell/ships-in-satellite-imagery 