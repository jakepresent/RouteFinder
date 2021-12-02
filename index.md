## Choosing the Right Climbing Route for You

Hello! For our group's final capstone project for CS 6730, our group has chosen to explore [OpenBeta's open source rock climbing dataset](https://github.com/OpenBeta/climbing-data). It contains climbing routes data from [MountainProject](https://www.mountainproject.com/) that has been extracted from an immense variety of locations all across the USA.

We decided to use the skills we've gained from this class to try to find a way to help someone choose climbing routes that best suit their level of skill, whatever it may be.


### Raw Data
![](raw_data.jpg)

This is a screenshot of the raw data that we were given. As you can see, each line corresponds to one climbing route in the USA. For each route, the data provided consists essentially of some geographic coordinate data, difficulty ranking information, and a textual review of the route.

Our challenge is to find a way to synthesize this data into something that could provide some utility to a climber trying to test his or her skills.

### Map View

<iframe seamless frameborder="0" src="https://public.tableau.com/views/map_routes/Dashboard1?:language=en-US&embed=yes&:display_count=yes&:showVizHome=no" width = '850' height = '550' scrolling='yes' ></iframe>    

Here is a map of all of the routes in the dataset, with the color of each point corresponding to the difficulty rating assigned to it. The distribution of the routes is not exactly surprising, with the vast majority of them seeming to be located around the Appalachians and the Rockies, depending on which coast you happen to live on.

Unfortunately, while this view of the data is interesting, it doesn't give our hypothetical climber much of an idea of which route to pick. All it does is tell us where the easy routes are and where the hard routes are.

To solve this problem, we decided to drill down into the provided ratings and see if any broad patterns start to emerge.

### Keywords of Interest that We Identified

<iframe seamless frameborder="0" src="https://public.tableau.com/views/climbinganalysis2/Dashboard1?:language=en-US&embed=yes&:display_count=yes&:showVizHome=no" width = '550' height = '650' scrolling='yes' ></iframe> 

We began our analysis of the reviews by filtering out filler words, such as prepositions, articles, etc. Then, we identified 88 different keywords from the reviews. The number of times each word appears in the dataset is shown above.

However, this still isn't exactly the most helpful in terms of our ultimate goal. We need to drill down further, so next, we identified distinct categories for the routes themselves.

### Categorizing the Routes

<iframe seamless frameborder="0" src="https://public.tableau.com/views/climbinganalysis2/Dashboard2?:language=en-US&embed=yes&:display_count=yes&:showVizHome=no" width = '550' height = '550' scrolling='yes' ></iframe> 




### Kewords Common Between Categories


<iframe seamless frameborder="0" src="https://public.tableau.com/views/climbinganalysis2/Dashboard3?:language=en-US&embed=yes&:display_count=yes&:showVizHome=no" width = '850' height = '650' scrolling='yes' ></iframe>    