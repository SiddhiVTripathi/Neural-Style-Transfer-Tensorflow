# Neural-Style-Transfer-Tensorflow
Implementation of **Neural Style Transfer** inspired from code available at official tensorflow website.<br>
Implemented single style transfer.

## The following are the requirements 
<details>
  <summary> Check libraries here </summary>
  
  1. python3
  2. tensorflow
  3. numpy
  
</details>

## Testing
The program runs for 5 epochs and each epoch has 100 steps. The program saves images after each epoch in images folder under the name transferred_<epoch_no>.jpg .
To perform style transfer run: `python transfer.py <path-to-content>.jpg <path-to-style>.jpg`
