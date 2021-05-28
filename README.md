# Digital-Signal-Processing-In-Trading
Transform asset price time series into stationary form apply Discrete Fourier Transform to eliminate noise and identify/model repeating patterns to exploit and backtest.

## Inspiration from Research Journals
The project was inspired by the following academic journals:
> [Journal 1](https://www.researchgate.net/publication/303849241_Fourier_Analysis_for_Stock_Price_Forecasting_Assumption_and_Evidence)
> [Journal 2](https://www.mesasoftware.com/papers/FourierTransformForTraders.pdf)
> [Journal 3](https://web.wpi.edu/Pubs/E-project/Available/E-project-022808-142909/unrestricted/FullIQPReport7.pdf)
 
## Project Demo
* [Jupyter Notebook Demo](https://nbviewer.jupyter.org/github/Naharul98/Digital-Signal-Processing-In-Trading/blob/main/Applying-Discrete-Fourier-Transform-In-Trading.ipynb)

## Screenshots
![Example ScreenShot](https://github.com/Naharul98/Digital-Signal-Processing-In-Trading/blob/main/Screenshots/screenshot2.jpg?raw=true)
![Example ScreenShot2](https://github.com/Naharul98/Digital-Signal-Processing-In-Trading/blob/main/Screenshots/screenshot1.jpg?raw=true)

## About the Project

### Discrete Fourier Transform

* This digital signal processing technique is used to de-noise the data. Discrete Fourier Transform Splits time series into a set of waves. These waves can be summed up to construct the original time series again!

* However, objective is to remove noise from original time series.

* Therefore, the concept is that, we only select a few set of waves with most amplitude -> and only use these to reconstruct the time series.
the resulting time series will only have the most prominent characteristics of the original
