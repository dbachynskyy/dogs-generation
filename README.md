In this project I implemented a small GAN network which I trained on Stanford Dogs Dataset(https://www.kaggle.com/datasets/jessicali9530/stanford-dogs-dataset?resource=download).
Achieved Losses:
![2b42d7b1-a0b8-40fc-a702-313b0f1beaf4](https://github.com/user-attachments/assets/352ac401-6aa2-4739-bba1-4d82bc3c7735)
Achieved Pictures:
![7767ae01-2a53-481b-aa36-7d72932a59e0](https://github.com/user-attachments/assets/ccd8c8a1-c2a7-4adf-9185-767c5f899303)
Thoughts:
The above result does not produce very good dog images, but this is related to small scale of this network(batch_size = 128) + low number of epoch(3). On the other hand, we can clearly see the cnn kernels and how in some pictures they are trying to build out dog's face.
The network seems to have picked up some patters like darker face features, as well as nose and ears shapes in some cases, but to achieve better results it will need to be increased in scale and train on more epochs.
