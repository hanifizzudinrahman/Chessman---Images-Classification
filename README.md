# Chessman-Dataset---Images-Classification

1. Build and Train

- ImageDataGenerator: rescale, rotation_range, zoom_range, shear_range, fill_mode, validation_split
- Sequential Model: Conv2D, MaxPooling2D, Dropout, Flatten, Dense
- Class = 5
- Optimizer = adam
- Accuracy = 85% - 50%

![image](https://user-images.githubusercontent.com/47806867/135288887-4e09144e-c25f-4731-9bab-0a4610fdffc7.png)
![image](https://user-images.githubusercontent.com/47806867/135288931-2e665c23-339f-4c64-b2d6-9f245e05f808.png)


2. Transfer Learning

- ImageDataGenerator
- Sequential Model: ResNet15V2("imagenet"), Flatten, Dense
- Optimizer = adam
- Accuracy = 95% - 78%

![image](https://user-images.githubusercontent.com/47806867/135289055-7fb11538-f715-4350-ad54-a8a3691153a2.png)
