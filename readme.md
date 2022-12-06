
### Transformations
```
ICV_image_shear(image, angle)
ICV_rotate_image(image, angle)
```

## Convolution
```
ICV_convolve(img, kernel)
```

## Video Segmentation

```
ICV_histogram(image)
ICV_colored_histogram_plot(image, hist)

ICV_histogram_intersection_helper(h1, h2)
ICV_histogram_intersection(image1, image2)

```

##Texture Classification 

```
ICV_binatodeci(binary)
ICV_histogram_plot(image, LBP_image, hist)
ICV_LBPimage(image_window)
ICV_LBP_image_descriptor(img, window_size)
ICV_classify_image(image, face_descriptor, non_face_descriptor)

```


## Object Counting
```
ICV_frame_differencing(frames, threshold)
ICV_frame_differencing_2(frames, threshold)
ICV_generate_reference_frame(frames)
ICV_count_moving_objects(frames)
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
