# Calculating the area of the coronal hole with filters using OpenCV and Python
## by YUNBLAK

### Image Processing

The coronal hole is an area where the Sun's corona is darker and colder than average and has a lower density of the plasma. We will use OpenCV and Python to process images of the sun to calculate the area of the coronal hole of the sun.

![SOLARS001](https://user-images.githubusercontent.com/87653966/126169229-365020b6-5c50-4f79-be46-501e65143489.jpg)

We highlight the coronal hole part from the original solar image through image processing. That is, after making the image of the sun black and white, all other elements except the coronal hole are black, and the coronal hole part is white. We calculate the pixel value of the white part. That is the relative width value of the coronal hole.

### Ratio of image colors with OpenCV

If the image had been read correctly, a three-dimensional form of ndarray would have been created. The meaning of the number being returned is (height, width, channel). where channel means RGB 3 channel.

Learning images with the k-mean algorithm of scikit-learn. The k-mean algorithm is the most common model of machine learning to cluster data by creating k data means. When we invoke the actual function, it returns how many percentages are occupied in the cluster count area. We use that percentage to calculate the coronal hole area.
