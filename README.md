# Description
This repo was the first attempt at hosting a Github Page for my JavaScript version of the Kalman Filter for mouse tracking.

`matrix.js` is a matrix library written in scratch for this project. The Kalman Filter class is defined in `sketch.js`. I've used the p5.js library for interactions/graphics on the page. Clicking and dragging the mouse in the canvas provides noisy measurements of the mouse pointer's coordinate to the filter. You can adjust the sampling time and noise factor on measurements, as well as magnitude of the covariance matrices Q and R. The webpage also displays all important matrices in the Kalman Filter (P,Q,R,K).

# Links
* [Live Github Page](https://gr-code.github.io/kalman-js/)
* [Python version](https://github.com/GR-Code/kalman-py)
