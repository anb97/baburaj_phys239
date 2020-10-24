Question 1:
Using the relations given in the slides, we have calculated the value of N and sigma_v0 are 3 different optical depths
N (Column density) = D (dist. through cloud) * n (particle density)
tau_v (optical depth) = sigma_v (cross-section)*N -> sigma_v = tau_v/N

Question 2:
Calculate intensity at freq v_0 by first defining an array for distance through the cloud from 0 to D in steps of 0.1pc. 
Defining a null array of similar size. And then looping through the array using the RT eqn to get I_v at different distances 
according to the previously determined array.

Question 3:
Generate a Gaussian profile for sigma_v for 3 different values of sigma_v0 as defined in Q1. A 10 angstrom wavelength range has been 
chosen to more accurately depict an actual spectral line. 
The Gaussian profile is offset from zero by 5% of the peak value, i.e sigma_v0 (while keeping peak value = sigma_v0). 
This is done to mimic real world scenarios where the cross section could be very small near the edges of the Gaussian profile but 
would not go to zero.

Question 4:
In each case, for lower optical depth, I_v(D) is close to I_v(0)
(a) According to given criteria, I_v(0)=0, S_v=0.9 (an arbitrary value) and sigma_v0=2e-21 cm^2 so that tau_v(D)<1
I_v(D) goes towards S_v as optical depth increases near v_0.

(b) According to given criteria, I_v(0)=1.3, S_v=0.9 (arbitrary values) and sigma_v0=2e-21 cm^2 so that tau_v(D)<1
I_v(D) goes towards S_v as optical depth increases near v_0.

(c) According to given criteria, I_v(0)=0.5, S_v=0.9 (arbitrary values) and sigma_v0=2e-21 cm^2 so that tau_v(D)<1
I_v(D) goes towards S_v as optical depth increases near v_0.

(d) According to given criteria, I_v(0)=0.9, S_v=1.3 (arbitrary values) and sigma_v0=1e-18 cm^2 so that tau_v(D)>>1. 
I_v(D) overlaps with S_v line.

(e) According to given criteria, I_v(0)=0.3, S_v=0.9 (arbitaray values) and sigma_v0=3e-20 cm^2 so that tau_v(D)<1, but tau_v0(D)>1
I_v touches S_v in regions where tau_v is significantly greater than 1

(f) According to given criteria, I_v(0)=1.3, S_v=0.5 (arbitaray values) and sigma_v0=3e-20 cm^2 so that tau_v(D)<1, but tau_v0(D)>1
I_v touches S_v in regions where tau_v is significantly greater than 1