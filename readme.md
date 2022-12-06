
### Transformations
```
ICV_image_shear(image, angle) # shear an image
ICV_rotate_image(image, angle) # rotate an image
```

## Convolution
```
ICV_convolve(img, kernel) # convolve an image given the kernel
```

## Video Segmentation

```
ICV_histogram(image) # calculate histogram of the image
ICV_colored_histogram_plot(image, hist) # plot the colored histogram

ICV_histogram_intersection_helper(h1, h2) # helper function to find the histogram intersection
ICV_histogram_intersection(image1, image2) # get the histogram of two images
```

## Texture Classification 

```
ICV_binatodeci(binary) # convert image to binary
ICV_histogram_plot(image, LBP_image, hist) # plot the image histogram
ICV_LBPimage(image_window) # calculate the LBP of the given image 
ICV_LBP_image_descriptor(img, window_size) # returns the global descriptor and the LBP image
ICV_classify_image(image, face_descriptor, non_face_descriptor) # classify the given image face from non-face

```

## Object Counting
```
ICV_frame_differencing(frames, threshold) # difference between reference frame(frame 0) and the current frame
ICV_frame_differencing_2(frames, threshold) # difference between the previous frame and the current frame
ICV_generate_reference_frame(frames) # generate the reference frame using frame difference and weighted temporal averaging
ICV_count_moving_objects(frames) # count moving objects in an image using histogram
```


## Requirements:
```
numpy >= 1.13.0
matplotlib >= 1.5
cv2 >= 4.0


```

## References:
1. https://python.plainenglish.io/generating-text-on-image-with-python-eefe4430fe77
2. https://stackoverflow.com/questions/73993491/doing-naive-affine-transforms-shear-numpy-image-using-numpy
3. https://shrishailsgajbhar.github.io/post/Image-Processing-Image-Rotation-Without-Library-Functions
