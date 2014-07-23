3DImaging
=====
Convert 2D Images to Red-Cyan 3D Images
----------------------------


###Dependencies

* MATLAB with ImageViewer

###Using 'thrDImageChng.m'

* Copy your image to folder that contains **thrDImageChng.m**
* Open file **thrDImageChng.m**
* Change variable str to <filename>. Include it with extension
    Ex. str = '<filename>'
* **Optional** Change value of `m`. If you increase it's value, the Depth will be increased upto some extent. Output will be distorted if it goes very high.
* Run file
* You will see a image in current folder with name **3D_<filename>**
###Using 'TwoCams/Code.m'

##Taking two Images for code
* Put your camera on solid surface click Image. This will be image1.
* Now shift camera to right for a small distance i.e. distance between your eyes.
* Click this Image. This will be image2


##Create 3D Image
* Copy both images in same directory as Code.m
* Open Code.m. Replace image1 file name with im1.jpg and image2 file name with im2.jpg
* Run file
* New 3D Image will have name ImageResults.jpg


Good Luck and keep experimenting :D