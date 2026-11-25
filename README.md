# NYC Taxi Trip Duration Prediction

Predicting how long a New York City taxi trip will take from pickup and drop-off details, using the public [NYC Taxi Trip Duration dataset on Kaggle](https://www.kaggle.com/c/nyc-taxi-trip-duration).

## What's in the notebook

1. **Exploration:** distributions of trip duration, passengers, pickup times and locations.
2. **Preprocessing:** engineering features such as trip distance and pickup hour.
3. **Visualisation:** how duration varies with time and place.
4. **Modelling:** a scikit-learn pipeline comparing Linear Regression, Lasso, Elastic Net and K-Nearest Neighbours regressors.

## Files

- `nyctrippred.ipynb`: the notebook (outputs cleared).
- `nyctrippred.html` and `nyctrippred.pdf`: exports with the outputs and plots, readable without running anything.

## Run it

Download the dataset from Kaggle, put `train.csv` next to the notebook, and run all cells. You'll need pandas, numpy, matplotlib, seaborn and scikit-learn.

## Limitations

This was an early learning project: it compares linear models and KNN only, and leaves out tree-based models such as gradient boosting.

## License

MIT. See [LICENSE](LICENSE).
