# CSCI 3656: Numerical Computation - Final Project
## University of Colorado - Boulder
## Authors: Andy Wood, Brendan McCall & Ethan Kissell

In this paper we explore parameters that are closely related to US housing prices. The data that these parameters are chosen from come from a Kaggle dataset that is regularly updated with data from the real-estate site Redfin. We use Lagrange Interpolation and Cubic Spine Interpolation to describe the dataset graphically. After choosing Lagrange Interpolation using Chebyshev polynomials to describe the dataset we explore which parameters are correlated with median sale price of houses. It is found that number of homes sold per year shows the best correlation with median sale price of houses.

### Dependencies

- Python 3.9
- NumPy (Library)
- Pandas (Library)
- MatPlotLib (Library)
- SciPy (Library)

### Build Instructions

Use an IDE of your choice to open the project. Then download
the whole dataset from Kaggle at [this link](https://www.kaggle.com/datasets/vincentvaseghi/us-cities-housing-market-data/data),
and place it in the same directory as the main .ipynb.
Then, unzip the truncated data set from the .zip file and place
it in the same directory as the main .ipynb. Make sure the name of
the truncated data set is "city_market_tracker.tsv", while the name
of the whole dataset is "city_market_tracker.tsv000". Finally, you
can run all the cells.