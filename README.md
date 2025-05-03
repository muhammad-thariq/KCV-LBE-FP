# Star Rail Character Data Analysis - README

## Overview

This Jupyter Notebook analyzes character data from the game "Star Rail". The dataset contains information about various in-game characters including their attributes, stats, and characteristics.

## Dataset Description

The dataset (`starraildata.csv`) contains 60 character entries with the following columns:

* `character_id`: Unique identifier for each character
* `character_name`: Name of the character
* `rarity`: Rarity level (4 or 5 stars)
* `world`: World origin (W0, W1, W2, W3, or Unknown)
* `element`: Element type (Ice, Wind, Fire, etc.)
* `path`: Character path/class (The Preservation, The Hunt, etc.)
* `base_HP`: Base health points
* `base_ATK`: Base attack points
* `base_DEF`: Base defense points
* `base_SPD`: Base speed
* `max_Energy`: Maximum energy capacity

## Analysis Highlights

The notebook performs the following analysis:

* **Data Loading & Initial Exploration:**
    * Imports necessary libraries (`numpy`, `pandas`, `matplotlib`, `seaborn`)
    * Loads and displays the dataset
    * Provides basic info about the dataframe structure
    * Shows descriptive statistics for numerical columns
* **Data Cleaning:**
    * Standardizes column names by stripping whitespace
* **Key Statistics:**
    * Average base stats across all characters:
        * HP: ~1121
        * ATK: ~607
        * DEF: ~464
        * SPD: ~102
        * Max Energy: ~122

## How to Use

1.  Ensure you have Python and Jupyter Notebook installed.
2.  Install required packages: `pip install numpy pandas matplotlib seaborn`
3.  Place the `starraildata.csv` file in the same directory as the notebook.
4.  Run the notebook cells sequentially.

## Potential Further Analysis

The notebook provides a foundation for deeper analysis such as:

* Character attribute distributions by rarity, world, or element
* Correlations between different stats
* Visualization of character attributes
* Comparative analysis between character types

## Dependencies

* Python 3.x
* Jupyter Notebook
* pandas
* numpy
* matplotlib
* seaborn

## Note

The notebook currently suppresses warnings (`warnings.filterwarnings('ignore')`) for cleaner output during analysis.
