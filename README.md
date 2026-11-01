# The Seer Project

Predicting the future price of Nigerian Bonny Light crude oil, five trading days ahead.

## About the dataset

The dataset is synthetic: 5,200 daily rows from January 2006 to December 2025, with 13 numeric columns. These are price and trend features, Brent and dollar moves, US inventory surprises, Nigerian output, and the price five days ahead as the target. It follows the broad shape of real oil market history, including the 2008 spike, the 2014-16 collapse, the 2020 crash and the 2022 surge, but these are not real Bonny Light prices. It is for building and testing the modelling pipeline, so any results should be confirmed on real data. Run `generate_dataset.py` to recreate it.

