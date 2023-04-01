# Monte_Carlo_pi
## Description

A program written as part of the course Computational Intelligence in Data Analysis in MATLAB environment.

My goal was to compare the effect on the accuracy of estimating the number pi using the Monte Carlo method depending on the random number generator used as well as the number of points drawn. I used two different random number streams and two different seeds ie.
`RandStream("twister", "Seed",2^32-1);`
`RandStream("twister", "Seed",sum(100*clock));`
The results are shown for 100, 1000, 10000 drawn points for each generator separately.
The visualization is shown below.

## Technologies
* Matlab R2022b

## Visualization
