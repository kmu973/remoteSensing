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

## Semantic Segmentaion UNET

- Image categorization : down sampling, Semantic segmentation : Up sampling
<img src="https://user-images.githubusercontent.com/70645899/228857650-7882af3f-030a-4646-b11d-e3263413bd7c.png" width="600">

- https://towardsdatascience.com/understanding-semantic-segmentation-with-unet-6be4f42d4b47
- https://www.youtube.com/watch?v=azM57JuQpQI
- https://towardsdatascience.com/unet-line-by-line-explanation-9b191c76baf5

## Autoencoder

- https://blog.keras.io/building-autoencoders-in-keras.html

## Transfer Learning

Why we're doing this?
- Lack of dataset
- Less common

- https://neptune.ai/blog/transfer-learning-guide-examples-for-images-and-text-in-keras
<img src="https://user-images.githubusercontent.com/70645899/230416030-28daf8ec-be16-4a34-bade-55e383fda6d0.png" width="600">
<img src="https://user-images.githubusercontent.com/70645899/230416658-5c3b89a6-4817-4adb-8e4b-734e18c13f94.png" width="600">
<img src="https://user-images.githubusercontent.com/70645899/230417721-b2f2987a-c31c-4a22-840f-cb0804dc310a.png" width="600">

- freeze initial conv blocks, dont freeze later blocks.
