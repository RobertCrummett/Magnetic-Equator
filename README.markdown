## Two Equators

Using the term 'equator' in most circles leads to no confusion. What
is being referenced is the zero parallel, a geographic line that is fixed
by a certain datum. However, in the field of magnetic mineral exploration,
the term equator has taken on another distinct meaning. The term is often
used to refer to the region where Earth's magnetic field points parallel to
the ellipsoid. Geophysicists say the field has zero inclination here.

Despite begin syntactically close, the magnetic and geographic equators are
often quite far apart. Some times as far as a 1000 kilometers! Those who
dare to explore at low latitudes must be confident as to whether they are low
magnetically, or geographically.

In addition to the magnetic and geographic equators, I have also fit a great
circle to the magnetic equator and displayed it in green. The fit minimizes the
energy of differences between the curves - that is what I mean by best in a L2
sense.

The poles are also plotted. Most people who deal with spatial data are aware
of the fact that the magnetic pole does not align with the geographic pole at
any one time. The magnetic pole displayed here was computed from the IGRF model
by NOAA. The best fit pole is simply the pole of the best fit equator. No new
maths were done to compute it.

As a final remark, I fit the great circle to the contour best fitting the
IGRF zero degree parallel on the sphere. I have a nagging suspicion that this
approach is fundamentally incorrect, because it it blind to inclination gradients
in both time and space. Shouldn't the rate at which the equator moves influence
our confidence in its average (minimum energy) position? This riddle is something
I am not quite internally settled about.

## Sources
- [GMT Animation for the Masses](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2024GC011545)
- [NOAA Magnetic Pole locations](https://www.ngdc.noaa.gov/geomag/data/poles/NP.xy)
