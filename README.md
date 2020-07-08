## Road_Scenes_Spatial_Priors_Generator
This repo is mainly for generating spatial priors
which are commonly prevalent in road scene datasets like Cityscapes, IDD, and others.

Due to the inherent structure present in the images in the above mentioned datasets, we
can generate a heatmap corresponding to each pixel based on the labels.

### Cityscapes SP:
| person |      car      |    road    |
|:------:|:-------------:|:----------:|
|  ![drawing](./cityscapes_SP/person.png)      |    ![drawing](./cityscapes_SP/car.png)           |     ![drawing](./cityscapes_SP/road.png)       |
|   sky  | traffic light | motorcycle |
|    ![drawing](./cityscapes_SP/sky.png)    |       ![drawing](./cityscapes_SP/traffic%20light.png)        |     ![drawing](./cityscapes_SP/motorcycle.png)       |
