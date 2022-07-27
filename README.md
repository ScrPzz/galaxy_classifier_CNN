# [CNN] Galaxy form factor classifier

Convolutional neural network trained on the Galaxy Zoo dataset (https://data.galaxyzoo.org/) capable of classifying galaxies based on their form factor.
Due of the asymmetry of the dataset only a 3 classes classificator is viable. Elliptical, Lenticular and Spiral:

| Spiral    | Elliptical    | Lenticular    |
|-------|-------|-------|
| ![image](https://user-images.githubusercontent.com/55019419/181256783-1eeb159e-4e3f-4954-8105-d3134c931153.png)| ![image](https://user-images.githubusercontent.com/55019419/181257013-008b9f1e-2d1e-4896-875d-9600458f10af.png) | ![image](https://user-images.githubusercontent.com/55019419/181257270-673b250b-e548-4817-9dac-28251c908570.png)|


## CNN infos

The Net is made of 4 Conv-Conv-MaxPool blocks:

![image](https://user-images.githubusercontent.com/55019419/181258585-91fbd35d-7802-43ee-be47-2aa6687f0ff6.png)


## Training 

The Net reaches 84% accuracy on the test set.

![image](https://user-images.githubusercontent.com/55019419/181259088-0ebce27e-9e28-4b0d-b655-1919d65640ef.png)



