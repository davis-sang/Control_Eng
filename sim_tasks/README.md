## Control Systems simulation design using matlab

The tasks were simulated using [matlab](https://www.mathworks.com/products/matlab.html) 
and the provided tasks can be implemented alternatively using 
[simulink](https://www.mathworks.com/products/simulink.html).

* The `sfdb1.m` implements a state feedback controller from a given transfer function. The provided desired closed loop poles being 
  
  `s = -5` and `s = -4 ±j2 √5` 
  and the transfer function being: `tf = 5 / (s+1)(s+2)(s+2)`
* The `sfdb2.m` file provides a description of a state feedback controller with the overshoot and settling time provided. 
  
  `tf = 5/(s+1)(s+2)(s+2)` and `5%` overshoot with `0.5` settling time.
  
* Lastly, `stobs.m` is a demonstration a full state observer design the desired eigenvalues of the observer gain matrix are 
  
  `s = −5` and `s = −2 ±j4√3`.
