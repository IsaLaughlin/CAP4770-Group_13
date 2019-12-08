# CAP4770-Group_13

## TMDB Box Office Revenue Prediction
The movie industry makes billions of dollars across the world. The success of these movies, however, is not universal. Some crash at the box office, costing the production company or companies paying for the film millions of dollars while others enjoy hugely successful revenues. The goal of our project is to predict what movies will fail or succeed and to identify key factors in box office success.

### Directory Structure
```
TMDB Box Office Revenue Prediction
├── data 
    ├── preptest.csv    # Intermediate preprocessed data file for test set
    ├── preptrain.csv   # Intermediate preprocessed data file for the train set
    ├── test.csv        # Raw test file
    ├── train.csv       # Raw train file
    ├── trueResults.csv # Revenue collected from another source
    ├── testPrepDone.csv #  Final preprocessed test file
    └── trainPrepDone.csv   # Final preprocessed train file
├── plots
    ├── diffcollection.png  # Box and whisker plot of movies belonging to a collection vs not belonging to a collection
    ├── logdiffcollection.png # Same as plot above but with log revenue
    ├── logrevhist.png # Distribution of log revenue
    └── revhist.png # Distribution of revenue
└── src
        ├── basicmodeling.ipynb # Baseline model
        ├── combined.ipynb # Combining preprocessed data from other files
        ├── Data Analysis.ipynb # Creating data visualizations
        ├── dsfinal (1).ipynb
        ├── dsfinalModeling (1).ipynb
        ├── disfinalModeling.ipynb
        ├── dsfinalPre.ipynb
        └── kfold.ipynb # Performing k cross fold validation on best performing models
```