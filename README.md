# Background
Translating novel convolutional neural network (CNN) architecture into code.

Google researchers have developed a novel CNN architecture, called the JumpNet, in 2020. JumpNet incorporates best practices of ResNet v2 and introduces a new skip connection that minimizes the number of parameters and matrix operations, while preserving accuracy and without going deeper in layers.


## Model
The code is written in a procedural design pattern where there is a pattern for constructing and coding a model which can be re-applied across a wode range of cases. For a CNN, the design pattern consists of a stem, learner, and task. The image below illustrates the design pattern.




Complete notebook can be found [here](https://github.com/tjeng/JumpNet/blob/main/JumpNet.ipynb).

## Results
