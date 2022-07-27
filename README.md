# IMDb insights

This is the Data Analysis part of a bigger project from [Academy Phase 1](https://github.com/empathyco/academy-winter-batch-2022).

## Dataset

The data for this project is from [This IMDb Dataset](https://datasets.imdbws.com/), so this dataset needs to be downloaded first in case cade wants to be executed.

## 1. Merging Files

This code was used to merge the pieces of the dataset because in IMDb was uploaded in different _.tsv.gz_ ([here](https://www.imdb.com/interfaces/) it is explained what the pieces consist of). 

The first part of the code was a try to merge all pieces of dataset in one and to see how much time could take. As it is logic, whenever a set of data was added to the dataset it took longer for the code to be executed and finish the merge. Everytime a merge was made, it was saved in a file in case it was needed to stop at that moment and continue later.

The second part of the code was simpler. This part of the project was only in charge of doing some insights for the IMDb genres, so, in order to merge and load the whole dataset, only the needed pieces were merged.

## 2. IMDb Insights


