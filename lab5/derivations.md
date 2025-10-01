Half-wave rectifier
$$V_{ac} = 12.6V_{rms}$$
$$V_p = V_{ac} \cdot sqrt(2) = 17.8V$$
$$V_{dc} = V_p - V_f = 17.8V - 0.7V = 17.1V$$
$$V_r = \frac{V_{dc}}{R}\frac{T}{C} = \frac{17.1V}{1k\Omega}\frac{\frac{1}{60}s}{470\mu F} \approx 0.606 V$$
$$\Delta T = \frac{1}{2\pi60 \text{rads/s}}\sqrt{\frac{2 \cdot 0.606}{17.8}} \approx 692\mu s$$
$$I_p = \frac{V_{dc}}{R_L}\frac{2T}{\Delta T} = \frac{17.1V}{1k\Omega}\frac{2\frac{1}{60}Hz}{692\mu s} \approx 824 mA$$