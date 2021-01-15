### Datasets
Two datasets are provided with this assessment:
- candy data (`state-by-state-favorite-halloween-candy.geojson`)
- population data (`population_est2017.csv`)  

### Instructions
1. Name your jupyter notebook with <firstname_candy>. For example, Mary's notebook would be named `mary_candy.ipynb`
2. Read in the candy data and look at the head. Use `geopandas` to read in the file.
3. Create a new column, `total_pounds`, to show the combined weight of 1st, 2nd, and 3rd place candies consumed by each state.
4. Which state consumes the most of its 1st, 2nd, and 3rd place candies combined (greatest combined weight)?
5. Which state consumes the least of its 1st, 2nd, and 3rd place candies combined (lowest combined weight)?
6. What is the average amount of combined candy consumed across all states? What is the median amount?
7. Read in the population data and merge it with the candy data.
8. Calculate a new column, `per_capita` to show the average weight (total pounds) consumed per person in each state.
9. Which state has the greatest consumption of its 1st, 2nd, and 3rd place candies per capita?
10. For this state, what is the consumption per capita for *each* of the top-3 candies?  
11. Which candy shows up most frequently (look at the 1st, 2nd, and 3rd place candies combined) in the dataset? One way you could do this is to create three lists from the DataFrame columns and concatenate them. You could iterate through this list and create a dictionary of counts. You could also use the Counter() method from the collections package.
12. Make a bar plot to show the number of times each candy appears in in the dataset (regardless of place).
13. OPTIONAL BONUS: Which candies only appear once in the dataset? Which states have them in their top 3?
14. OPTIONAL BONUS 2: plot a simple choropleth of candy consumption per capita for states.

#### When you have finished, email your notebook to <your_instructor> and verify that it was received.   

*DO NOT PUT YOUR NOTEBOOK ON GITHUB*



