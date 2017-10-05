# Solar limb darkening
### Tested with SDO/HMI data during 2012 transit of Venus

I have created a lightcurve of the transit of Venus from the 45s cadence continuum intensity images from NASA’s SDO/HMI instrument. Using this data rather than a real exoplanet transit lightcurve has the advantage of us knowing the correct answer, so we can test the validity of our method of using an artificial neural network to interpolate between the outputs of stellar atmosphere models with any parametric assumption about the form of the limb darkening profile.

The first steps in transforming the SDO/HMI continuum images into a transit lightcurve are explored in [prepare_solar_data.ipynb](./prepare_solar_data.ipynb)
