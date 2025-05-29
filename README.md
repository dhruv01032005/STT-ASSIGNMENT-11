# STT-ASSIGNMENT-11 - Model Quantization

## TEAM NUMBER - 10
## TEAM MEMBERS - 
1. Dhruv Goel(23110098)
2. Nitin Bansal(23110223)

## Objective -
This assignment aims at quantization of the Neural Network model.

## Methodology -
1. Found out the weights and biases of the neural network model by training on SST2 dataset on MLP(Multi Layer Perceptron) of hidden layer of sizes of 512, 256, 128, 64.
2. Then quantized the model to INT_8 using torch.quantization.quantize_dynamic().
3. And also used half precision(FP16) using .half() function.

## Learning Outcomes -
1. Quantization of model which is very important for huge deep learning models because with drastic change in memory used - the accuracy doesn't change much.
2. It also improves the inference speed of the model.
3. Can be helpful for edge devices like Raspberry Pi, mobile phones, FPGA, etc.

## Work Distribution -
As it was a small assignment and unavailablity of my teammate due to final exam I did the whole assignemnt.

## Observations - 
