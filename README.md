# Calculating the Area of Coronal Hole using OpenCV and Python
## by YUNBLAK

The coronal hole is an area where the Sun's corona is darker and colder than average, and has a lower density of plasma. We will use OpenCV and Python to process images of the sun to calculate the area of the coronal hole of the sun.

![SOLARS001](https://user-images.githubusercontent.com/87653966/126169229-365020b6-5c50-4f79-be46-501e65143489.jpg)

We highlight the coronal hole part from the original solar image through image processing. That is, after making the image of the sun black and white, all other elements except the coronal hole are black, and the coronal hole part is white. We calculate the pixel value of the white part. That is the relative width value of the coronal hole.
