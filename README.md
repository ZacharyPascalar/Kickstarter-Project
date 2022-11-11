# Overview of the Project

The purpose of this analysis is to give an overview of how I performed this analysis and the challenges I encountered.


## Challenges

One of the first challenges I encountered was converting the dates into something readable. When I had initially researched date conversion in Excel, 
everything was based around the serial numbers being only five or eight digits long, but these were ten. It turns out that they were in Unix format, 
and I had to find a formula for conversion. From there, I used the Year() function to convert the dates. At one point, I believe I did something wrong 
because the year kept stating it was 1905; I'm quite sure Kickstarter did not begin then, so I had to mess around with it to get it to work.

# Results


##### What are two conclusions you can draw about the [Theater Outcomes by Launch Date](https://github.com/ZacharyPascalar/Kickstarter-Project/blob/main/Resources/Theater%20Outcomes%20Based%20on%20Launch%20Date.png)?
One conclusion is that it is best to launch a campaign in late Spring to early Summer, or from May to July. The most campaigns seem to succeed during those times.
Conversely, the worst times appear to be September through January. Speculatively, that would be because it's the holiday season, so people are spending their money
on other things than Kickstarter projects. December in particular is very uncertain, with the number of successes almost matching the number of failures.

##### What can you conclude about the [Outcomes based on Goals](https://github.com/ZacharyPascalar/Kickstarter-Project/blob/main/Resources/Outcomes%20Based%20on%20Goal.png)?
Generally speaking, if a campaign has a small monetary goal (i.e. <$5000), it is more likely to succeed. Conversely, campaigns with a large monetary goal (i.e. >$45000) are least likely to succeed.
Though campaigns asking between $35000 and $45000 are more likely to succeed than not, there were overall very few of those campaigns relative to the smaller projects.
    
##### What are some limitations of this dataset?
The number of campaigns with larger monetary goals are overrepresented in the "Outcomes Based on Goal" graph. Though everything matches up percentage wise, 
there were many, many more campaigns being tracked that had smaller goals. One additional success or failure for those higher goaled campaigns would have
drastically altered the outcomes.

##### What are some other possible tables and/or graphs that we could create?
I think a double bar graph for Outcomes Based on Goal with the y-axis being the count of successful/failed campaigns instead of the percentages of them
would be a good idea. An axial break would be necessary for the sake of visual clarity, but it would assist in providing perspective on how likely a campaign 
really is to succeed or fail.
    






























