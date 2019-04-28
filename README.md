# k-means-image-segmentation
This repo contains the code and a report(please visit the github page) about the k-means image segmentation assignment we did for our Machine Learning class.

### How to run our code:

Please run from the command line -

```$ python hw3.py <image_path>```
For example:

```$ python hw3.py image_to_do_segmentation.jpeg```

The program will segment the photo with K = 1, 2, 5, 10, 20 and generate the corresponding pictures to the current directory where the code file resides in.
From the experiment we found that as the value of K increases, the time used to segment the picture will increase. Also, since the pictures generated from the program will have the same resolution of the original image, please consider using small images since the larger images you use with this program, the longer you could wait to get the results.

Please go to line 24 to change the value of K.
