# Fashion-Conditional-GAN
Fashion MNIST : Conditional GAN 

## Data: https://github.com/zalandoresearch/fashion-mnist

![](https://raw.githubusercontent.com/zalandoresearch/fashion-mnist/master/doc/img/fashion-mnist-sprite.png)

`Fashion-MNIST` is a dataset of [Zalando](https://jobs.zalando.com/tech/)'s article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. We intend `Fashion-MNIST` to serve as a direct **drop-in replacement** for the original [MNIST dataset](http://yann.lecun.com/exdb/mnist/) for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

### Labels
Each training and test example is assigned to one of the following labels:

| Label | Description |
| --- | --- |
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

# File structure:
```
├── Data
│   ├── Train_Data.gz
│   └── Train_Labels.gz
├── Fashion-GAN.ipynb
└── models
    ├── discriminator.json
    ├── discriminator_CGAN.json
    ├── discriminator_CGAN_model.h5
    ├── discriminator_model.h5
    ├── generator.json
    ├── generator_CGAN.json
    ├── generator_CGAN_model.h5
    └── generator_model.h5
```

# Models

### There are 2 models:
### 1. Vanilla Dense layer based GAN
### 2. Conditional GAN using Dense layers (Using the labels associated with each images)

Each of the models are trained for 30000 epochs.
