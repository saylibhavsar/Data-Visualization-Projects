| [home page](https://saylibhavsar.github.io/Data-Visualization-Projects/) | [visualizing debt](visualizing-government-debt.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three.md) |

# Critique by Design with Tableau (MakeoverMonday)
<br>
## Part 1 - Choosing a data visualization to critique/re-design

<img src="Images/regional-price-parities.jpg" alt="Regional Price Parity" width="600" align="center"/>
> Graph by <a href="https://cdn.howmuch.net/articles/regional-price-parities-by-state-cfce.jpg">howmuch.net</a>, Source <a href="https://www.bea.gov/data/prices-inflation/regional-price-parities-state-and-metro-area">U.S. Bureau of Economic Analysis</a>

* This graph shows the purchasing power of each state in the US to compare how expensive (and cheaper) everyday goods and services are within each state.
* It uses a benchmark of 100 (US Difference From The Average)

## Part 2 - Critique using Stephen Few's Data Visualization Effectiveness Profile

1- What worked and what did not?
<br>
* **Usefulness (8/10)** - Considering that the visualization is meant for economists and people who are interested in learning about purchasing power, this chart does a good job of telling a story of which US states are the most expensive (and cheapest) for everyday goods and services.
* **Completeness (8/10)** - The chart has all the information necessary to communicate the intended level of understanding the comparison between US states’ purchasing power. It also has a baseline (a measure of norm) to compare the actual values with (Avg. US Regional Price Parity = 100). Maybe, a little more clarity on purchase parity and how it works could be good.
* **Perceptibility (4/10)** - In my opinion, this radial chart is very difficult to understand considering that it makes it harder to compare states directly. States like California and Mississippi, which differ significantly, are placed far apart in the layout, making it harder to compare their relative values at a glance. The text is difficult to read because of the circular arrangement and varying angles. Using left-aligned or right-aligned text would make state names easier to read. This will also make the chart more compact and less visually cluttered. Something that works well here is, using one distinct color per group (e.g., blue for low-price parities, red for high-price parities) and a gradient scale for smooth transitions. 
* **Truthfulness (8/10)** - The chart seems to represent the data accurately without any distortion. The use of color and positioning on the circle corresponds to the actual price parity values.
* **Intuitiveness (4/10)** - The radial layout makes it difficult to immediately grasp how the states compare to each other. It doesn’t seem like this format is commonly associated with price comparison data, making it less intuitive for a normal audience. Plus, the scale and direction of values may require users to pause and analyze before understanding them fully.
* **Aesthetics (6/10)** - Aside from the radial layout, the chart is designed well by using appropriate colors like blue for lower price parity (which is better because goods and services are cheaper on average) and pink for higher values. Though, it would be better to use red/orange in this case. The legend looks good and is easy to understand. Overall, the chart looks well-designed with not too many colors and good usage of grey.
* **Engagement (5/10)** - The unusual format and bright colors attract initial attention. Viewers might find themselves intrigued by the circular design. But, once the user starts trying to interpret the chart, they could get frustrated by its lack of readability. This could lead to disengagement, especially if needed to make quick comparisons.
<br>

2- How successful what this particular tool/scale at evaluating the data visualizations? How does this method compare to the Good Charts method? Is there anything missing?

* Overall, the framework is pretty good at systematically evaluating the visualization's effectiveness by focusing on elements like perceptibility, usefulness, and aesthetics. The framework highlighted key issues like perceptibility and intuitiveness, which are crucial for data tools used by professionals. A measure that could be added is Accessibility (doesn’t address accessibility concerns, such as color blindness or if the chart is readable on various platforms).

* Comparison: I think this method works pretty well because it allows me to isolate each metric and think very objectively. For instance, when I was looking at the 'Usefulness', I did not think about anything else. I believe the good charts metric does not do this. But on a positive note, the Good Charts metric is good at organically laying out and understanding what I like vs what I don't. It is also an easier framework to explain and understand.
<br>

3- Brief Recommendations: 
Switch to a Bar Chart or something with a baseline: A horizontal or vertical bar chart would allow for easier comparison of regional price parities by having states along a single axis. The states could be ordered by their index values to make trends clear.
Color: Using a more limited, distinct palette (such as three colors: blue for below average, gray for average, red for above average) would make it clearer at a glance where states fall in relation to the national average.
Grouping: States could be grouped into categories (e.g., 85-89.9, 90-94.9, etc.) and arranged accordingly, making it easier to focus on the relevant section of the chart. 
