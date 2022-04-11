# fvisionNetwork14
"fvisionNetwork14" is a CNN model for image classification that can categorize "n" classes. It has been tuned to have less codes than other models with higher code complexity. The model can categorize with improved accuracy with just a few lines of code. The dataset can be immediately fed into the model using an image pre-processing module that has been built into the package. Two graphical modules are given for plotting model accuracy and loss by providing model history as input.

## Installation

```pip install fvisionNetwork14```

## Released version
version: 0.0.9

<!DOCTYPE html>
<h2> Modules:</h2>
  <li>fvNet14</li>
  <li>image_preprocessing</li>
  <li>plot_accuracy</li>
  <li>plot_loss</li>  
</ul>
<h2> Pre-requisites:</h2>
    <li>tensorflow</li>
<h2> Dependancy modules:</h2>
    <li>numpy</li>
    <li>matplotlib</li>


## How to use?

e.g:

<!DOCTYPE html>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Dataset directory</summary>
  <ol>
    <li>
      <a text = "#class A">  class A</a>
    </li>
    <li>
      <a text ="#class B">  class B</a>
    </li>
    <li><a text="#class C">  class C</a></li>
    <li><a text="#class D">  class D</a></li>
    <li><a text="#class E">  class E</a></li>
    <li><a text="#class F">  class F</a></li>
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
