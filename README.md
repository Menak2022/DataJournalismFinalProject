# DataJournalismFinalProject
# Final Project Data Journalism: Limited Starbucks Locations on California College Campuses 
### By: Williamena Kwapo
## Data Analysis Process: 
According to the 2018 dataset of Starbucks locations in the United States, California makes up 20.3% of all Starbucks locations, making it the state with the highest number of Starbucks in the US. 

!['INlWb-map-of-starbucks-around-the-usa.png’ , ’US Map of Starbucks’](/INlWb-map-of-starbucks-around-the-usa.png)'

Though California is saturated with Starbucks, colleges and universities campuses severely lack Starbucks locations. With this dataset, I decided to look at California Universities with 20,000 students or more to find out the closest Starbucks location to each campus. Using google maps, I located Starbucks that are in a 1 mile radius of 19 schools, finding that UC Berkeley has the longest distance to the nearest Starbucks location. The 19 schools analyzed are the following: 
1. University of Southern California
2. University of California-Los Angeles
3. University of California-Berkeley
4. California State University-Fullerton
5. California State University-Northridge
6. California State University-Long Beach
7. University of California-San Diego
8. University of California-Davis
9. San Diego State University
10. University of California-Irvine
11. San Jose State University
12. California State University-Sacramento
13. California State Polytechnic University-Pomona
14. San Francisco State University
15. California State University-Los Angeles
16. University of California-Riverside
17. University of California-Santa Barbara
18. California State University-Fresno
19. California Polytechnic State University-San Luis Obispo
## Scope of Analysis
1. Where in CA is the most Starbucks located?
2. How many Starbucks are located within 1.5 mile of CA college with 20k students or more?
3. Which college has the most starbucks location within 1.5 mile of campus?
4. Which institution has the closest starbucks location in walking distance? 
5. Which college has the furthest walking distance?
## Analysis
1.  Where in CA is the most Starbucks located?
#### The most Starbucks is located in the city of Los Angelos. 
Using my 2018 dataset, I created a pivot table. I put "row" as state and "values" as names in "COUNTA". I then sorted row by "COUNTA of names" in decending order to get the city with the highest number of Starbucks location.

!['Citywithmoststarbucks.png’ , ’California City with most Starbucks’](/citywithmoststarbucks.png)’

!['9ez4e-starbucks-locations-in-california-as-of-2018.png’ , ’California Map of Starbucks’](/9ez4e-starbucks-locations-in-california-as-of-2018.png)’ 

2. How many Starbucks are located within 1.5 mile of CA college with 20k students or more?
### There are a totoal of 43 Starbucks located within 1.5 miles of the 19 CA college with 20k students or more
I extracted data on the total enrollment of each CA schools. There were 19 schools with 20k students or more. I created a new dataset with those 19 schools and using google maps, located the starbucks within 1.5 mile of each school. Usuing a pivot table, I made "institution" row and "Starbucks within 1.5 mile radius institution" as value in 'SUM'

!['1.5milesaway.png , ’California City with most Starbucks’](/1.5milesaway.png)’

3. Which college has the most starbucks location within 1.5 mile of campus?
### University of Southern California has the most Starbucks location within 1.5 mile of campus with a total of 8 locations
By putting the pivot table from question #2 in ascending order by "Sum of Stabucks in 1.5 mile radius institution", you can see that USC has a total of 8 starbucks within 1,5 miles of campus

4. Which institution has the closest starbucks location in walking distance? 
### On average, students walk is San Diego State University
Using the pivot table in question 2 and 3, I made "rows" as institution, and vlaues as "nearest SB Name" and summarized that by "COUNTA". I also kept "walking distance from insitution" in values and summarized that by 'SUM". That way, I was able to see that San Diego State University has 1 starbucks that is a 0mins walk away. 

!['campuswithcloseststarbucks.png’ , ’California City with most Starbucks’](/campuswithcloseststarbucks.png)’

5. Which college has the furthest walking distance?
### University of California - Berkeley has the furtherest distance from a starbucks with the nearest starbucks 12 mins walk away at 0.6 miles
Using the pivot table in question 2 and 3, I made "rows" as institution, and vlaues as "nearest SB Name" and summarized that by "COUNTA". I also kept "walking distance from insitution" in values and summarized that by 'SUM". That way, I was able to see that University of California - Berkeley has the nearest starbucks at 12 mins walk away. 

!['campuswithcloseststarbucks.png’ , ’California City with most Starbucks’](/campuswithcloseststarbucks.png)’

## Story Sourcing - Who I Would Contact
I would want to know if the far distance to the nearest Starbucks at UC Berkeley is impacting students, falculty, or staff in any way
> Noah McMillan
> noah.mcmillan@berkeley.edu

> Pamela Estrada
> pamelastrda@berkeley.edu

> Myah Overstreet
> myah_overstreet@berkeley.edu
