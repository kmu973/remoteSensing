## convolutional neural networks

- https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53
- https://www.youtube.com/watch?v=B-M5q51U8SM
```
CNN finds optimal filters
convoled image ≒ filtered image
stride : step size of window
```
<img src="https://user-images.githubusercontent.com/70645899/225632347-39a9b2dc-d9a7-420f-915d-609037c0f3b5.png" width="500">




## image kernel (≒ filter) 
- https://setosa.io/ev/image-kernels/
<img src="https://user-images.githubusercontent.com/70645899/225631436-09044dc1-7ea7-407b-a1fa-ea132e45c457.png" width="500">




## gabor filter
- https://medium.com/@anuj_shah/through-the-eyes-of-gabor-filter-17d1fdb3ac97
```
find edge of images of diffrent multiple orientations
```
<img src="https://user-images.githubusercontent.com/70645899/225629881-b3d8b96d-c05e-467a-af68-1f8dad23ce06.png" width="500">




## pooling (≒ downsampling)
- https://www.youtube.com/watch?v=8oOgPUO-TBY
```
averaging surrounding values : most popular  
max pooling : based on attention mechanism (typically no overlapped, stride = filtersize)
```


## imagenet - vgg16
- https://www.image-net.org/index.php
- https://image-net.org/static_files/files/pascal_ilsvrc.pdf
- https://machinelearningmastery.com/use-pre-trained-vgg-model-classify-objects-photographs/
```
exsiting cnn architecture
```
<img src="https://user-images.githubusercontent.com/70645899/225662434-9f43411c-5bc2-464a-9945-bfe31e011705.png" width="500">



## GPU setup
- https://rsandstroem.github.io/gpuDeepLearningWindows.html

## Data augmentation
```python
ImageDataGenerator
```

## Semantic segmentaion UNET

- Image categorization : down sampling, Semantic segmentation : Up sampling
<img src="https://user-images.githubusercontent.com/70645899/228857650-7882af3f-030a-4646-b11d-e3263413bd7c.png" width="600">

- https://towardsdatascience.com/understanding-semantic-segmentation-with-unet-6be4f42d4b47
- https://www.youtube.com/watch?v=azM57JuQpQI
