# Trends-in-Travel-Time
Using Travelling Salesman Problem, we find the total time taken to travel through selected malls in Dubai, UAE. We find the journey's time at different local times and evaluate the data collected to find patterns and trends. This has many use cases: it can be further used to predict the time taken for the journey at different times of the day as well as to alert a person intending to make the journey the best and fastest time.

malls.csv contains the latitudes and longitudes of the locations of the malls selected. This was used to create an adjacent matrix for the travelling salesman's algorithm 
Six more datasets were created to find the time taken to travel between all the locations chosen at different times of the day from 12pm to 12am on Saturday 11/12/2021 from the routes. 
The routes with minimum distance were found using the backtracking algorithm for the travelling salesman's problem. It found all the possible paths and then chose the ones with the minimum distance. Based on the route selected as the minimum, the total time for the journey is calculated for various times of the day i.e., for all six of the time matrices. The results were then stored in the form of a dataset. Created another dataset comparing the time taken using all the possible minimum distance routes  

We then use all three datasets for data visualisation and analysis:
A map was created representing the locations chosen in our malls.csv dataset  
We then read the time.csv dataset and plot scatterplots, line graphs and bar plots to compare the total time taken for the journey at different local times.  
We then do a paired t-test on the third dataset to check if there is enough of a difference between the total times of the routes selected by the algorithm. 

