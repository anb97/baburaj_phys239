The simulation was run for Z=2 with a time resolution of 1e-14s and 10,000,000 timesteps. 

I will be showing the plots for the interaction with initial y of electron = 50000a_0, initial velocity = 1e7 cm/s in the x direction.
This gives an impact factor of 49283.72a_0.

We have plotted the power spectrum corresponding to x, y as well as the net acceleration. 

Power spectrum =  (absolute value of FT)^2

Of these only the x and y acceleration plots give a peak. As the x acceleration power spectrum has a lower amplitude than the y 
acceleration power spectrum by a factor of ~5, this implies that most of the power for the emitted radiation comes due to the y acceleration.
Hence, we will be noting the peaks in the y power spectrum as the peak frequency value in further analysis.

Another caveat is that as the peak frequency is at pretty low frequency values, its often not clearly visible on the power spectrum plot.
However, we have determined using the np.argmax function that there is indeed a peak at non-zero frequency.

From part 5, we make the following observations:

Peak frequency decreases as impact factor 'b' increases. It qualitiatively looks like a logarithmic relation. This is because as b increases, the electron
deviates less, hence the energy difference between the initial and final energy of the electron is lower. Thus, the frequency of the 
emitted radation is lower.

Peak frequency also decreases as initial velocity 'v' increases. This also qualitatively looks like a logarithmic relation. This happens 
because as v increases, the electron deviates less, hence the energy difference between the initial and final energy of the 
electron is lower. Thus, the frequency of the emitted radation is lower.
