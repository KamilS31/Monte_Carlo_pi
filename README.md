# Monte_Carlo_pi
## Description

A program written as part of the course Computational Intelligence in Data Analysis in MATLAB environment.

My goal was to compare the effect on the accuracy of estimating the number pi using the Monte Carlo method depending on the random number generator used as well as the number of points drawn. I used two different random number streams and two different seeds ie.

```
RandStream("twister", "Seed",2^32-1);
RandStream("twister", "Seed",sum(100*clock));
```

The results are shown for 100, 1000, 10000 drawn points for each generator separately.  
The visualization is shown below.

## Technologies
* Matlab R2022b

## Visualization
![1](https://user-images.githubusercontent.com/127042515/229302705-a1a536f4-1283-4cff-a438-8c88c2eba3de.png)
<p align="center"> Data for seed equel 2^32-1 <p> <br />

![2](https://user-images.githubusercontent.com/127042515/229302742-63b02d54-4dba-4231-8448-ec8aa46a30f6.png)
<p align="center"> Data for seed equel sum(100*clock) <p> <br />

![3](https://user-images.githubusercontent.com/127042515/229302769-08657ba5-f477-46f5-83fc-70b2e09dd277.png)
<p align="center"> Value of pi against number of generated points (N = 10000) <p>
