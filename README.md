# Chessman-Dataset---Images-Classification

1. Build and Train

- ImageDataGenerator: rescale, rotation_range, zoom_range, shear_range, fill_mode, validation_split
- Sequential Model: Conv2D, MaxPooling2D, Dropout, Flatten, Dense
- Class = 5
- Optimizer = adam
- Accuracy = 85% - 50%

2. Transfer Learning

- ImageDataGenerator
- Sequential Model: ResNet15V2("imagenet"), Flatten, Dense
- Optimizer = adam
- Accuracy = 95% - 78%
