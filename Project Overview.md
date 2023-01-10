# Movie Lens case study

## Overview
Identified the features affecting the ratings of any particular movie and built a model to predict the movie ratings. The datasets are in .dat format and hence 
needed to converted into .csv using encoding.
Created a separate column for each genre category with a one-hot encoding ( 1 and 0) whether or not the movie belongs to that genre. Also found out the unique genres 

## Dataset description
These files contain 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040 MovieLens users who joined MovieLens in 2000. The datasets are in .dat format 
and need to be preprocessed in order to be worked upon.
- UserIDs range between 1 and 6040 
- The MovieIDs range between 1 and 3952
- Ratings are made on a 5-star scale (whole-star ratings only)
- A timestamp is represented in seconds since the epoch is returned by time(2)
- Each user has at least 20 ratings
- Gender is denoted by an "M" for male and "F" for female
- Some MovieIDs do not correspond to a movie due to accidental duplicate entries and/or test entries
- Movies are mostly entered by hand, so errors and inconsistencies may exist
