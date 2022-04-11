# fvisionNetwork14

## Installation
```pip install fvisionNetwork14```

## Description
version: 0.0.4

modules:
        - image_preprocessing
        - fvNet14
        - plot_accuracy
        - plot_loss
        
Dependancy modules:
        - numpy
        - from tensorflow
        - matplotlib

## How to use?
e.g:

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Dataset directory</summary>
  <ol>
    <li>
      <a text = "#class A"> About The Project</a>
    </li>
    <li>
      <a text ="#class B">Getting Started</a>
    </li>
    <li><a text="#class C">Usage</a></li>
    <li><a text="#class D">Roadmap</a></li>
    <li><a text="#class E">Contributing</a></li>
    <li><a text="#class F">License</a></li>
  </ol>
</details>
### image_preprocessing
    image_pre_processing.image_preprocessing(path, image_height = 50, image_width = 50)

### fvNet14
    model_test = fvNet14.fvNet14(image_height = 50, image_width = 50, color_channel = 3, output_layer = 10)
    history = model_test.fit(xtrain,ytrain,epochs=50,validation_data=(xtest,ytest))

## plot_accuracy
    plot_model_acuracy.plot_accuracy(history, height = 10, width = 10)

## plot_loss
    plot_model_loss.plot_loss(history, height = 10, width = 10)
## License

© 2022 Kalyan Mohanty

This repository is licensed under the MIT license. See LICENSE for details.
