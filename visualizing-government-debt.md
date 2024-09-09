| [home page](https://saylibhavsar.github.io/Data-Visualization-Projects/) | [visualizing debt](visualizing-government-debt.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three.md) |

# Visualizing Government Debt
<br>
## Part 1 - Working with web-based visualization tools and data (OECD)
<img src="Images/government-debt.png" alt="Government Debt OECD" width="900" align="center"/>
> Graph by <a href="https://www.oecd.org/en/data/indicators/general-government-debt.html">OECD</a>, Source <a href="https://data-explorer.oecd.org/vis?lc=en&ac=false&tm=DF_GOV_PF_YU&pg=0&snb=1&vw=tb&df[ds]=dsDisseminateFinalDMZ&df[id]=DSD_GOV%40DF_GOV_PF_YU&df[ag]=OECD.GOV.GIP&df[vs]=&pd=2007%2C&dq=A.AUT.....&to[TIME_PERIOD]=false">OECD Data Explorer</a>

* This graph shows the General government debt as a % of GDP (2022) from the OECD official website.
* The chart compares the debt of the different countries and sorts them in descending order, making it easy to see which countries have the most debt.
* The chart highlights the OECD average, making it easy to understand which countries are above or below the average.

<br>

## Part 2 - Working With Tableau (Heat Map)

Here is the heat map of the General Government Debt as a % of GDP from 1995 to 2021 from OECD:

<div class='tableauPlaceholder' id='viz1725892839384' style='position: relative'><noscript><a href='#'><img alt='General Government Debt as % of GDP (1995-2021) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;Government_Debt_Part2&#47;GovernmentDebtHeatMap&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Government_Debt_Part2&#47;GovernmentDebtHeatMap' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;Government_Debt_Part2&#47;GovernmentDebtHeatMap&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1725892839384');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<br>

## Part 3 - A Decade After the 2008 Global Financial Crisis

This graph presents the general government debt as a percentage of GDP for various world regions (South America, Oceania, North America, Middle East, Europe, and Asia), comparing debt levels between 2008 (the year of the global financial crisis) and 2018 (a decade after the crisis). 

**What the Graph Shows:**
* The graph highlights how different regions have either recovered or worsened in terms of their government debt levels as a share of their GDP after the financial crisis.
* By comparing 2008 to 2018, we can see which regions have taken on more debt and which have shown signs of recovery or improvement in managing their debt.

<div class='tableauPlaceholder' id='viz1725892913150' style='position: relative'><noscript><a href='#'><img alt='Government Debt Levels: A Decade After the 2008 Global Financial Crisis. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;Government_Debt_Part3&#47;GovernementDebt-FinancialCrisis&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Government_Debt_Part3&#47;GovernementDebt-FinancialCrisis' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;Government_Debt_Part3&#47;GovernementDebt-FinancialCrisis&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1725892913150');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
<br>
**In terms of the design:**
* The years 2008 and 2018 are displayed for each region to compare the two time periods.
* Each bar is labeled with the exact percentage, making it easy for viewers to see the debt levels without having to estimate from the axis.
* The use of two distinct colors – gray for 2008 and orange for 2018 – effectively differentiates between the two time periods. This color scheme makes it easy to compare the debt levels at a glance, without confusion. The orange color signifies the more recent data (2018) as that is the focus of the graph, and the gray color marks the debt levels at the time of the 2008 global financial crisis.
* The graph focuses on regions rather than individual countries, which provides a broader view of the global debt situation. By grouping countries into continents or large regions, the visualization makes it easier to see patterns and regional economic health.

**Key Insights:**
* Asia stands out as having the highest government debt both in 2008 and 2018, with a sharp increase from 181.3% to 238.7% of GDP, suggesting that the region has struggled the most with managing debt levels post-crisis.
* North America also experienced a significant rise in debt, increasing from 75.5% in 2008 to 100.1% in 2018. This indicates ongoing challenges in controlling debt levels.
* South America saw the most dramatic rise, going from a very low level of 12.4% in 2008 to 60.6% in 2018, which could indicate fiscal policies leading to increased borrowing over the decade.
* Oceania and Europe saw moderate increases, but their debt levels remained somewhat stable compared to regions like Asia.
* The Middle East showed an improvement in debt management, with a decrease from 57.6% in 2008 to 32.4% in 2018, indicating stronger recovery and fiscal discipline in that region.

## Comparison of different methods of visualization

* The first visualization is a bar chart that focuses on a more recent snapshot (2022), showing government debt as a percentage of GDP across individual countries. This visualization highlights current debt levels at the national level, enabling a direct comparison of individual OECD countries. The use of highlighted countries and the OECD average makes it easier to benchmark specific nations, while the simple layout ensures clarity. However, it lacks the historical context offered by the other visualizations, focusing solely on a static year.

* The second visualization is a heat map that shows the general government debt as a percentage of GDP from 1995 to 2021 across various countries. This method represents time-series data, allowing viewers to quickly spot trends and outliers through color gradients. Countries with higher debt levels, like Japan and Italy, are marked by warmer colors, making it easy to compare debt levels over time. However, while it excels in showing long-term changes, it can be overwhelming when many years are compared simultaneously, and it’s harder to discern specific figures at a glance.

* My third visualization, a bar chart, compares debt levels across world regions for 2008 and 2018. It uses two distinct colors to highlight changes over the decade, making it simple to compare specific years. The bar chart is effective for showcasing the specific use case (distinct comparisons between years and regions) but lacks the granularity of the heat map, which covers a much broader time frame and individual countries. The clarity and simplicity of this visualization, however, make it a better choice for a focused analysis of the global financial crisis's impact a decade later.
For this assignment, I chose the bar chart because it directly compares the government debt in 2008 and 2018, which is crucial for understanding regional recovery after the global financial crisis. It provides a clear, focused visualization without overwhelming the viewer with too much information. 

**Sources:**
[OECD Data Explorer]((https://data.oecd.org/gga/general-government-debt.htm))
