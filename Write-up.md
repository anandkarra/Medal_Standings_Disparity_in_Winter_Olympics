# Medal Standings Disparity in Winter Olympics

### [**Github**](https://github.com/anandkarra/Medal_Standings_Disparity_in_Winter_Olympics)
### [**Tableau Public**](https://public.tableau.com/profile/anand.karra#!/vizhome/Project_Tableau_Workbook-FINAL/Story1)

____

## Summary
Reading and exploring about data visualization online I stumbled across #MakeoverMonday. An online weekly social data project ([#MakeoverMonday](http://www.makeovermonday.co.uk/)). The Winter Olympics dataset piqued my interest as it was just around the time the Winter Olympics in PyeongChang, South Korea were taking place. Looking at the Winter Olympics medal standings data, I found an interesting trend: 
> **A small number of the participating countries win a larger proportion of the medals**.

This Tableau story is about how this trend varied over time, the three medals (Gold, Silver and Bronze), sports and gender.

___

## Design

### Initial Design Decisions

1. #### Number of medals won by each of the participating countries.
The first horizontal bar plot is to visually present the viewer with the skewed nature of the medal standings in question. As the quantity to be represented was the number of medals won for all of the participating countries, I used a bar plot. Moreover, as the number of medals won are spread across a large range (from 329 for Norway to 1 for Uzbekistan), I specifically chose to represent the bar plot as a horizontal bar plot to accurately depict the range of variation to the viewer.

I wanted this visualization to be the first to be presented to the viewer as it lays a clear foundation on which the subsequent visualizations are based upon and also clearly depicts the disparity.

The countries winning high number of medal are grouped into "Top Medal Standing Countries" which includes 14 countries. These countries are represented in one colour and the remaining countries in another.

2. #### Medal standings visualized over a map.
This plots aims to further connect the viewer with the data. Rather than just be a bunch of country names and numbers. This map also allows the viewer to hover over each of the countries and see how many medal that country has won in a Tooltip.

3. #### Variation of medal standings over time
The variation of medal standings over time is shown in this plot. It gives the viewer perspective if the disparity in question here is just a one-time occurance or a trend over time.

As the Winter Olympics occur once every four years, the year marks for the time axis are adjusted accordingly.

4. #### Distribution of individual medals across the countries
This visualization is similar to the first one but it further shows the number of Bronze, Silver and Gold medals won by the countries. It allows the viewer to observe if there are any additional trends in the data which were previously unexplored.

5. #### Variation of medal standings across events among the Top Medal Standing Countries and the remaining countries
This visualization shows the number of medals won by the "Top Medal Standing Countries" and the other countries for the individual events (sports). Just as in the previous visualization, it allows the viewer to observe if there are any additional trends.


### Changes after feedback on version 1
* Added "event" as a filter to the second, third and last visualization to allow the user to further explore the data.
* Added number of medals won in the Tooltip and Label for relevant visualizations as it is the prime focus of this story.
* Added the year of the data point in the third slide to assist the viewer in understanding the variation over time more clearly.
* Changed the colours used for representing the Bronze, Silver and Gold medals in the fourth slide so that it is more intuitive to the user.
* Used the green colour to represent the countries in the "Top Medal Standing Countries" and grey for other countries to improve consistency.

### Changes after feedback on version 2
* Added the average and 2X average reference lines to the relevant visualizations to give the viewer better context to understand the range of variation in the data. Also, shaded the region of the data points less than the average value in the appropriate visualizations.
* Allowed the selection of a country on the map to filter other related plots for more detailed exploration.
* Used the "Pages" pane to implement animation in the third slide representing the variation of the medal standing over time for better understanding.
* Added the reason why the data points for 1940 and 1942 are missing from the visualization (World War 2).
* Separated the countries based on whether they are in the "Top Medal Standing Countries" or not in the last two visualizations.
* Added annotations to highlight the exceptions in the last visualization.

____

## Feedback

### (Feedback collected from Mr. Avinash Pandey)

#### Version: 1
The visualizations look really good and I can get an idea of the story you are trying to convey using them. There are some design and presentation choices and some consistency issues I noticed that could use a bit of improvement. I saw on the last slide the distribution of the number of medals for the various events, the ability to view the medals won by each country for each sport in appropriate visualizations could be a nice addition.

Since the disparity in medal standings is the main focus of these visualizations, the rank of the country (if it is possible) and the number of medals won by the individual countries may be displayed on the bar plot in all relevant plots. Along the same lines, having the year and number of medals won near the circle representing the data point in the third slide would be very helpful. In the fourth slide, the colours for the Bronze, Silver and Gold can be changed to colours like Brown, Grey and Yellow. That would make the plot more intuitive.

Overall, I felt it would be better to use a single colour for the "Top Medal Standing Countries" rather than blue in some places and green in others.

#### Version: 2
The uniformity in the colours used in the visualizations look much better now. The first slide states - "the number of medals won by the top 9 "Top Medal Standing Countries" is twice...". It would be more clear if some kind of reference line could be shown on the visualization itself that marked these values. Not only in the first slide, but also in other slides like the third and fourth one.

In the map in the second slide, it would be helpful if the bar plot in the first slide is also visible here since all the "Top Medal Standind Countries" are not marked on the map. Also, try making the countries on the map to act like filters for the other visualizations on selecting them.

In the third slide, there is no reason specified for why the data points for 1940 and 1944 are not present. Also, if possible some animation in the way these points appear for the various years will be very helpful for understanding the variation.

In the last two sides, the separation of the countries on whether the country is in the "Top Medal Standing Countries" or not will make the plots more easy to understand. In the last plot, there are some exceptions to the general trend of the "Top Medal Standing Countries" winning more medals than the other countries, hightlight them accordingly.

#### Version: FINAL
The story looks a quite polished now. One of the first things I noticed is the shading of the region less than the average, that was a very nice touch. Selection of a country on the map to further filter the other plots is working exactly like I expected it to. Also, the timeline in the slide showing the variation of medal standing over time is very intuitive. The annotations in the last slide also highlight the exceptions well.

Looks pretty good overall. Good job!
____

## Resources

* **Example – A Story That Examines a Trend** - [Tableau Help](https://onlinehelp.tableau.com/current/pro/desktop/en-us/story_example.html)
* **Makeover Monday** - [Makeover Monday | A weekly social data project](http://www.makeovermonday.co.uk/)
* **Week 7: The Winter Olympics** - [Makeover Monday](http://www.makeovermonday.co.uk/week7-2018/)
* **The Winter Olympics** - [Workbook: The Winter Olympics](https://public.tableau.com/views/TheWinterOlympics/TheWinterOlympics?:embed=y&:showVizHome=no)
* **#MakeoverMonday Week 7 | Who Gets an Olympic Medal?** - [Tableau Public](https://public.tableau.com/profile/ann.jackson#!/vizhome/MakeoverMondayWeek7WhoGetsanOlympicMedal/MakeoverMondayWeek7WhoGetsanOlympicMedal)
* **How do Wealth and Population Impact Countries' Medal Counts in Winter Olympics** - [Workbook: GDP and Population Impact on Winter Olympic Performance](https://public.tableau.com/views/GDPandPopulationImpactonWinterOlympicPerformance/WinterOlympics?:embed=y&:display_count=yes&publish=yes&:showVizHome=no#3)
* **The Tableau Interface** - [Tableau Training](https://www.tableau.com/learn/tutorials/on-demand/tableau-interface?product=tableau_desktop+tableau_prep&version=2018_1&topic=getting_started)
* **Reference Lines** - [Tableau Learning](https://www.tableau.com/learn/tutorials/on-demand/reference-lines?product=tableau_desktop&version=10_0&topic=visual_analytics)
* **Formatting** - [Tableau Learning](https://www.tableau.com/learn/tutorials/on-demand/formatting?signin=2e2e5de59d610ac85ba7a6cb2a68de4f)
* **Save Workbooks to Tableau Public** - [Tableau Help](https://onlinehelp.tableau.com/current/pro/desktop/en-us/publish_workbooks_tableaupublic.html)
____
