# Neural-Style-Transfer-Tensorflow
Implementation of **Neural Style Transfer** inspired from code available at official tensorflow website.<br>
Implemented single style transfer.

## The following are the requirements 
<details>
  <summary> Check details here </summary>
  
  1. python3
  2. tensorflow
  3. numpy
  
</details>

## Testing
The program runs for 5 epochs and each epoch has 100 steps. The program saves images after each epoch in images folder under the name transferred_<epoch_no>.jpg .
To perform style transfer run: `python transfer.py <path-to-content-image> <path-to-style-image>`


## Outputs
![](https://github.com/SiddhiVTripathi/Neural-Style-Transfer-Tensorflow/blob/master/results/ShotOnPhone1/transfered_900.jpg)
![](https://github.com/SiddhiVTripathi/Neural-Style-Transfer-Tensorflow/blob/master/results/The%20Dark%20Rose/transfered_500.jpg)
![](https://github.com/SiddhiVTripathi/Neural-Style-Transfer-Tensorflow/blob/master/results/ShotOnPhone2/transfered_1500.jpg)

## Changes
The number of epochs can be modified in the [file](https://github.com/SiddhiVTripathi/Neural-Style-Transfer-Tensorflow/blob/master/transfer.py) at line 150.
