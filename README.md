# stamps

The two exercises are solved by executing the Jupyter Notebook (IPython) "Exercises.ipynb".

I used linux (Ubuntu 14.04 LTS) to prepare the code.

## Dependencies

The notebook requires an installation of python and ipython (https://ipython.org/install.html).
Moreover, I rely on the following python modules:

* pandas (http://pandas.pydata.org/)
* matplotlib (https://matplotlib.org/)
* basemap (https://matplotlib.org/basemap/, also part of the ubuntu package manager)
* numpy (http://www.numpy.org/)

Most of these are already included in python distributions like canopy (https://www.enthought.com/products/canopy/) or anaconda https://www.continuum.io/downloads).


## Exercises

The exercises can be solved by executing all cells of the notebook.
Execution of some cells (loading data) can take a while. Execution of the last two cells will open two windows showing the result plots for Ex. 1 and Ex. 2.

Note, I did not use the shapefile to show country borders; it was more convenient to use the matplotlib "basemap" toolkit.

### Ex.1
For the downscaling procedure I assumed that the relative amounts of wheat production within Ethiopia did not change between 2005 and 2014. While this seems to be a crude assumption, it is the best guess given the limited data.
By construction, the downscaled data is consistent with the FAO data.

### Ex.2
The annual wheat production of Ethiopia shows essentially three regimes:
1) Steady increase under Haile Selassie I.
2) Rapid decrease starting in 1973 (oil crisis) followed by a stagnation phase (Derg era).
3) Rapid increase starting in 1991 (Federal Democratic Republic).

Conclusion: The numbers are plausible.
