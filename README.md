# FastNet-machine-learning-weather-prediction-models-through-loss-function-design
https://arxiv.org/pdf/2509.17601

FastNet is the Graphical Neural network global prediction model that is designed for monitoring and predicting weather pattern such as temperature, precipitation, sea-level pressure, jet stream, etc. This model can be used to investigates the impact of alternative loss function designs on improving the physical realism of its forecasts.  

There are three key modifications to the standard mean squared error (MSE) loss: 
(1) a modified spherical harmonic (MSH) loss that penalises spectral amplitude errors to reduce blurring and enhance small-scale structure retention; 
(2) inclusion of horizontal gradient terms in the loss to suppress non-physical artefacts;
(3) an alternative wind representation that decouples speed and direction to better capture extreme wind events.
