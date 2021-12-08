## Choosing the Right Sport Climbing Route for You

What does it take to become a better sport climber? If you could teleport to any climbing area in the United States, where should you go?

### Map View

<iframe seamless frameborder="0" src="https://public.tableau.com/views/map_routes/Dashboard1?:language=en-US&embed=yes&:display_count=yes&:showVizHome=no" width = '850' height = '550' scrolling='yes' ></iframe>    

Take a look at this map of the more than 54,000 sport climbing routes entered in MountainProject, with the color of each point corresponding to the difficulty rating assigned to it. The distribution of the routes is not exactly surprising, with the vast majority of them seeming to be located around the Appalachians and the Rockies, depending on which coast you happen to live on.

Unfortunately, while this view of the data is interesting, it doesn't give our hypothetical climber much of an idea of which route to pick. With this many routes, there are likely infinite combinations of hold type, rock shape, and climbing style.  

What differentiates a 5.8 from a 5.11?
Technical skills? Raw strength? Endurance? Grip strength and form? How much of it is overcoming common fears like making dynamic moves, hanging upside down, or just a general unsafe feeling?

### The Data

Using data scraped from the MountainProject database in August 2020 hosted by openbeta.io, we've analyzed the climber-entered descriptions for each route to determine what skills a climber needs to possess to successfully climb at a higher level.

In the rock climbing community, difficulty ratings for climbing routes range from 5.0 to 5.15, with +/- or a/b/c/d modifiers to further expand the scale. For simplicity, we’ve divided these into the following four groups:

5.10a and below: Beginner
5.10a/b through 5.10d: Intermediate
5.11a-d: Advanced
5.12a and above: Elite

To learn more about what the original ratings mean, you can visit [this page](https://www.rei.com/learn/expert-advice/climbing-bouldering-rating.html).

Route descriptions entered into MountainProject are packed with rock climbing slang that, while providing great opportunities for analysis, can be difficult for a newcomer to understand. Some words will be explained along the way, and we’ve included a brief glossary at the end for the rest.


### Categorizing the Routes

<iframe seamless frameborder="0" src="https://public.tableau.com/views/climbinganalysis2/Dashboard2?:language=en-US&embed=yes&:display_count=yes&:showVizHome=no" width = '550' height = '550' scrolling='yes' ></iframe> 

We began our analysis by dividing all the routes into four different cateoriges of difficulty: Beginner, Intermediate, Advanced, and Elite. As you can see in the pie chart above, each category countains a roughly equal number of routes.

### Keywords of Interest that We Identified

<iframe seamless frameborder="0" src="https://public.tableau.com/shared/QKP4DRBBW?:language=en-US&embed=yes&:display_count=yes&:showVizHome=no" width = '850' height = '550' scrolling='yes' ></iframe> 

We continued our analysis by incorporating data from the reviews. We did this by filtering out filler words, such as prepositions, articles, etc. Then, we identified 88 different keywords from the reviews. The word cloud above shows how many times each word appears in the dataset. The size of each word represents how common a given word is the overall dataset, while the color of the word represents how common it is in the selected category.


### Keywords Common Between Categories


<iframe seamless frameborder="0" src="https://public.tableau.com/views/climbinganalysis2/Dashboard3?:language=en-US&embed=yes&:display_count=yes&:showVizHome=no" width = '850' height = '650' scrolling='yes' ></iframe>    

In the above view, if you sort the words by the "Beginner" difficulty category, you will see the words sorted by their frequency in easier routes. You can see how certain keywords pertain to different difficulties.
For example, the word "slab" is more common with beginner routes, and becomes less common as the difficulty increases. This is due to the fact
that "slab" references a route that is fairly straightforward and vertical, which helps to make a route easier. 

On the other hand, a route with more "roof" elements is increasingly more common in harder routes,
because a roof is more horizontal, which requires a climber to be more parallel to the ground when they climb this section. Climbing a roof requires a great deal of effort, which is why it
seems to be associated with more challenging routes.


#### Crimp, Jug, Knob & Pinch, Pocket, Sloper

As you can see in the above view, there are different types of holds that are present in the difficulty categories.
A **hold** is a rock climbing term for the places on the rock surface that are shaped in a way for a climber to attach themselves to the route
and propel themselves higher. 

A **crimp** is a type of hold that consists of a small edge that can support the tips of a climber's fingers.
**Jugs** are large, deep, concave holds that are relatively easy to grab with one or both hands.
A **knob or pinch** hold can be "pinched" between a climber's fingers and thumb, and requires intense strength to grasp.
**Pockets** are holes within a wall that a climber can use to insert their hand or fingers.
**Slopers** are large, round holds that can be difficult to grip and do not have sharply defined edges.

### Ternary Plots

<iframe seamless frameborder="0" src="https://public.tableau.com/views/ternary_plots_rockclimbing/Dashboard2?:language=en-US&embed=yes&:display_count=yes&:showVizHome=no" width = '850' height = '550' scrolling='yes' ></iframe>  


### Stacked bar charts

<iframe seamless frameborder="0" src="https://public.tableau.com/views/holdtype_stackedbar/HoldType?:language=en-US&embed=yes&:display_count=yes&:showVizHome=no" width = '1100' height = '600' scrolling='yes' ></iframe> 

<iframe seamless frameborder="0" src="https://public.tableau.com/views/rockshape_stackedbar/RockShape?:language=en-US&embed=yes&:display_count=yes&:showVizHome=no" width = '800' height = '600' scrolling='yes' ></iframe> 


### Final Interactive Map

<iframe seamless frameborder="0" src="https://public.tableau.com/views/map_routes/Dashboard2?:language=en-US&embed=yes&:display_count=yes&:showVizHome=no" width = '850' height = '550' scrolling='yes' ></iframe>    