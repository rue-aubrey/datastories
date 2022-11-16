# Critique by Design Project

<div class="flourish-embed flourish-chart" data-src="visualisation/11835908"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Original  Visualization
The original was used in *[PBoth sides of the bars: How mass incarceration punishes families](https://www.prisonpolicy.org/blog/2022/08/11/parental_incarceration/)*, a briefing from the Prison Policy Initative.

The [visualization itself](https://static.prisonpolicy.org/images/spi_family_separation_sex.webp) was made by Wendy Sawyer in 2022. It's based on state prison data from the 2016 Bureau of Justice Statistics' Survey of Prison Inmates as analyzed by the Prison Policy Initiative.

I chose this visualization because I am interested in organizations that work to end mass incarceration. Looking through published data visualizations from various organizations in the field, those from the Prison Policy Institute stood out as needing some work. There is a whole series of visualizations from this organization I could have worked with, each with its own areas for improvement. 

This particular visualization, however, has a key flaw in its presentation. The selected categories of "Parent of a Minor Child," "Lived with Minor Child at Time of Arrest," and "Single Parent Household at Time of Arrest" not only overlap, but fully encompass the next. 

For example, a "Parent of a Minor Child" will also be counted in "Single Parent Household at Time of Arrest." But this is not indicated in the data. This internal relationship in the data poses unique opportunities for data visualization.

## Critique 
[Click here to see the Good Charts Critique](https://docs.google.com/spreadsheets/d/1NJC62tJaYt402543EbG_gNnxd9ZIaAl2qgJeVa-J-0Q/edit?usp=sharing)

[Click here to see the Data Visualization Effectiveness Profile](https://github.com/ruesellers/datastories/blob/main/Data%20Visualization%20Effectiveness%20Profile.pdf).

My primary concern for this visualization is that subsequent Y variable is a subset of the previous, but there is little indication of this data relationship. I will use the relationship to separate the data into four categories of parental relationship to the child at the time of arrest, which add up to 100% of inmates surveyed who were parents.
1. Sole Caregiver
2. Partial Caregiver
3. Not the Caregiver
4. N/A, Children are not Minors

Equations for this data disaggregation can be found in the Excel file [here](https://github.com/ruesellers/datastories/raw/main/DATAFORDESIGNCRITIQUE.xlsx).

## The Sketch

![First Sketch of Redesign](assets/ppisketch.jpg alt="First Sketch of Redesign)

### Feedback on Sketch
Reviewer A. They're a neuroscientist.

They were able to understand the topic of the visualization and understand the nature of the percentages (numerator and denominator). Their main takeaway was that "of women arrested, more are sole caregivers, and more have kids who are still minors."

Their confusion came from two parts. First, "Partial Caregiver," where there is another caregiver in the household besides the arrested parent, was unclear to them. Second, they were concerned as to why women had such a higher percentage of minor children compared to men. They also want to know more about how many men and women there are in the data total. I do not have access to this data.

*KEY TAKEAWAY:* The topic is engaging enough to move forward, and the stacked bar chart makes things more clear.

## First Draft
For this draft, I focused on transferring the sketch to a Flourish chart. As such, it's a bit of rough. I clarified some of the labels, but at this point in the design process, I didn't know how to clarify "Partial Caregiver." I eventually figured this out in the Revised Draft. 

<div class="flourish-embed flourish-chart" data-src="visualisation/11833558"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Feedback on First Draft
Reviewer B. She's a photographer.

She was able to identify the primary message of the visualization, that women's incarceration is more likely to lead to an absence of caregivers, and that there is a large chunk of arrests that lead to this.

"Children Over 18" threw her off. It seemed to indicate that the children were being arrested. I asked if "No Children Under 18" was clearer, and she agreed.

Even with the clarification, she still suggested that I remove "Children Over 18" as a category to focus on *arrested parents with minor children* rather than all arrested parents.

Like with Reviewer A, she wanted to see the proportionality between men and women represented in the figure. However, this data is not available to me. If it were, I could scale the total length of each bar to indicate relative total popualtion. However, this would obscure the relative proportions. It would be sending a different message.

*KEY TAKEAWAY:* Either clarify or remove the category of "Children Over 18."

## Revised Draft
For this revision, I added data labels, emphasized the legend, changed the title, and made the "Only Caregiver" category more saturated to call attention to it, given it's worst case scenario. I also changed the "Children Over 18" category to "No Children Under 18" to hopefully provide a clearer message.

<div class="flourish-embed flourish-chart" data-src="visualisation/11833797"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Feedback on Revised Draft
Reviewer C. He's a student in this class with me.

This reviewer misunderstood the topic to be more about custody. From what I understand, he thought that the "Caregiver Status of Parents Upon Arrest" was about *assignment* upon arest of parents. He mentioned caregiver status being "awarded" more to women than to men. However, the data is about caregiver status *prior* to arrest, so maybe I should change the wording.

He found "No Children Under 18," confusing, so changing it from "Children Over 18" did not seem to help. 

*KEY TAKEAWAY:* Remove "Children Under 18" to focus solely on Parents with Minor Children. Clarify wording.


## Final  Draft 
This graph removes "Children Over 18"/"No Children Under 18" from consideration and focuses solely on parents with minor children at time of arrest. This data highlights the situations faced by minor children when their parents are arrested, ignoring children who are adults.

<div class="flourish-embed flourish-chart" data-src="visualisation/11834166"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
