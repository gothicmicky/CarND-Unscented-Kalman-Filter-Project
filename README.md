# Unscented Kalman Filter Project 
Self-Driving Car Engineer Nanodegree Program

In this project, an Unscented Kalman Filter (UKF) was utilized to estimate the state of a moving object of interest with noisy lidar and radar measurements. RMSE values were used to evaluate the model performance.

---
## EKF flowchart for this project
![alt text][ukf_flowchart]

[ukf_flowchart]: ./media/UKF_flowchart.png 

## Dependencies
* cmake >= 3.5
 * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools]((https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)
  
## Build Instructions
1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./UnscentedKF` 

## Code Style
The coding style follows [Google's C++ style guide](https://google.github.io/styleguide/cppguide.html).

## Generating Additional Data
This is optional!

If you'd like to generate your own radar and lidar data, see the
[utilities repo](https://github.com/udacity/CarND-Mercedes-SF-Utilities) for Matlab scripts that can generate additional data.

## Results

### Simulator Output
![alt text][ukf_output]

[ukf_output]: ./media/UKF_simulator_output.png

### Final RMSE:
```
Total number of estimations: 499
RMSE: 
0.0674596
0.0891818
0.330094
0.23666
``` 
