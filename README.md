# image-compression-using-PCA-in-python

> We will first split the image into the three channels (Blue, Green, and Red) first and then and perform PCA separately on each dataset representing each channel and will then merge them to reconstruct the compressed image. Hence, if our colored image is of shape (m, n, 3), where (m X n) is the total number of pixels of the image on the three channels (b, g, r).

> We can also perform the same thing without splitting into blue, green, and red channels and reshaping the data into (m, n X 3) pixels, but we have found that the explained variance ratio given by the same number of PCA component is better if we use the splitting method as mentioned in the earlier paragraph.

# Conclusion

> I have explained how we can use PCA to reduce the dimension of a color image by splitting it into 3 channels and then reconstruct it back for visualization.
