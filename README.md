# Keras Model to TFLite

&emsp;&emsp;This repositories is a demonstration of converting Keras model to TFlite model. Then we can use `BatchEvalTFLite.ipynb` to batch validate the TFLite model.

&emsp;&emsp;此存储库演示了如何将Keras模型转换为TFlite模型。然后我们可以使用 `BatchEvalTFLite.ipynb` 对TFLite模型进行批验证。

## Requirements:

- tensorflow >= 2.0
- python >= 3.6
- numpy
- matplotlib

## HighLight

&emsp;&emsp;We use some SeparableConv2d to reduce the number of parameters

## How to use

### Ste 1. Train and convert the model to TFLite model

Run all the code cells in `SeparableMnist.ipynb`

### Step 2. Batch validate the TFLite model

Run all the code cells in `BatchEvalTFlite.ipynb`, this file contains batch verification and single image verification.

## Reference

1. https://github.com/nex3z/tflite-mnist-android