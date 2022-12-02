# Part II: Drafts and Feedback

## 1. What's the story?

With this data story, I'm trying to show how gun sales change in response to large political events like elections. I want to convey to my audience that Americans buy these guns as a reaction to fear. This fear comes from many places: fear of gun laws, fear of political change, fear of the other, and fear of death. 

One [study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7369030/) from Callcut et al (2020) shows that mass shootings and gun laws have ramped up gun purchases to levels not seen before, particularly in the last 10 years.  One other [study](https://www.tandfonline.com/doi/abs/10.1080/0735648X.2021.1997787?journalCode=rjcj20) suggests that fear over **"loss of status"** is a much greater motivator of gun purchases than "lack of safety."

To tell this story, I want to incorporate stories of my dad, a conservative Evangelical Virginian. This personal anecdote exemplifies the larger sentiment shown in the data. It gives a face to reactionary factions and their increasingly armed response to political change and polarization. What follows are the first two paragraphs of this narrative which introduce the story.

<p style="text-align: center;"><i> It was the Christmas after Obama's historic victory in 2008. I was nine years old. My Virginian father, a staunch conservative and persistent Evangelical, bought his first gun. And his second. And third.</i></p>

<p style="text-align: center;"><i>Obama is going to take away our freedom. We have to be able to protect our house. This is the end of America. These memories I have of my father were full of fear – fear that taught me guns keeps us safe. Fear that just so happens to drive sales.</i></p>

## 2. Which kind of visualization should I use?
There's lots of ways I could do this. I thought about pictogram charts to show the sheer quantity of guns. However, it's hard to shpw time-dependence in the data with pictograms. I ended up with two other approaches.

### **Option 1**:
I used Tableau to make an easy approach, a line chart. Each line represents one year leading up to the 2008 election of Barrack Obama. 2008 is highlighted in a bold red. The spike around November is clear. There was a clear response in the gun purchase data to Obama's win.

Option 1 wasn't embedding well, so you can find it [here.](https://public.tableau.com/views/Graph1Final/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

### **Option 2**
I used Flourish to create radar chart, which I got the idea for when researching the concept of "data densification." Because I need to show mutliple events and their corresponding gun sales, there will be a lot of graphs on the final website. Line graphs are intuitive, but can get overwhelming in large numbers. I hoped a radar chart could present the data more compactly.

<div class="flourish-embed flourish-radar" data-src="visualisation/11998115"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Interview with A, a 22 year old CMU student
I presented Option 2 to A. This version had no radial axis to show quantity of gun sales. I gave him no context about the story I was telling, and he was confused about what the chart meant. The outwardness of the lines (distance from the origin) didn't carry the immediate meaning of *more* that I wanted. After I explained, he got exactly what I meant. To clarify the purpose of the chart, I decided to add annotations to clarify when Obama's election is on the chart. 

He said, "Highlight the dimensions more. I want to be able to get numbers out of the lines." In response to this critique, I added radial axis lines with boldened labels.

When I showed A Option 1, he liked it much more, saying, "The scale is much clearer and more intuitive." This reflected his earlier opinions that about Option 2 being harder to read for specific quantities. 

#### Takeaway
In the end, his recommendation was that I use the line chart. However, when trying to include Option 1 in Shorthand, the Tableau embed looked unprofessional and unclear. The black background didn't stay and the axis was cropped short of the full 12 months. This biased me towards Option 2 which uses Flourish.

## 3. How should I synthesize story and data?

![image](https://user-images.githubusercontent.com/39631332/204965127-0c5c52d7-5efd-404c-a514-e0c0bbdf13c0.png)
![image](https://user-images.githubusercontent.com/39631332/204964963-1ab5f069-5ac0-43fa-be7d-66168aa62c27.png)

I combined the introduction text and Option 2 graph on Shorthand, shown in the screenshots above. I brought them to B for feedback.

### Interview with B, a 24 year old photographer

First, I showed B the Shorthand draft with the embedded Flourish radar chart from Option 2. Within the context of the story, the graph made "immediate sense" to her. Afterwards, I showed her Option 1 from before for comparison. 

We spent time workshopping the title. She suggested that if my story doesn't touch on mass shootings, I should remove it from the subtitle. She also said that the title should focus more on conservative reactionism than "fear and loathing." The title needed to be punchy This is what we ended up with:

<p style="text-align: center;">"Reactionary Armament: Americans and Their Guns </p>

<p style="text-align: center;"><i> As polarization deepens, some Americans seek comfort in arms." </i></p>


#### Feedback and changes for shorthand visualization:

| **Feedback**                                                    | **Conclusion**                                                                             |
|-----------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| "Prior Years" isn't specific enough.                            | I will change the legend to read "2000-2007" and "2008."                                |
| She wanted to be able to look more closely at the data.         | I will refine the popup function                                                        |
| She wanted to be able to see growth in gun sales through years. | I will add a final visualization that animates gun growth nationally from 2000 to 2020. |

#### Comparison to Option 1 line chart from before
She said the line chart was much "simpler," and should be easier for the average person to intuitively understand. However, she qualified that the line chart was less visually interesting. The radar chart from Option 2, by comparison, had a much more "polished" presentation, with a "wow-factor."

In response, I asked which option would look best on a webpage. Specifically, I asked, "Which visualization would be less cluttered and overwhelming when replicated multiple times." She answered Option 2, the radar chart in Flourish. She said, "it communicates the specific message much more clearly." It seems that the refinements on Option 2 since my interview with A worked.

#### Takeaway
I will continue to refine the radar chart in Tableau, leaving the line chart alone for now.

## 4. Expanding the story, a group interview

The story pieces below follow the introduction. They're meant to continue the story, expanding the narrative to the national scale and to more recent years. To get feedback, I presented each to my CMU classmates, all in their 20s.

### National Perspective
In this section, I want to highlight that  that Virginia is not an isolated trend, pointing out that gun sales peaked more in states that voted against Obama.
![image](https://user-images.githubusercontent.com/39631332/205175042-2cd2c6b1-d6c7-4c5e-9687-14b6590d77f3.png)

| **Feedback** | **Conclusion** |
|---|---|
| It's hard to read the legends for each. One person misread 2008 to mean 2009. | Increase font size for legend. |
| The plots raise questions about why gun sales rise in December. | Maybe include a link to a paper that talks about this. |
| One person was not sure why Texas and New York were specifically included. We didn't share the common knowledge that New York leans D and Texas leans R | Maybe include a map comparison above these plots. Use a map of 2008 election results vs. a map of 2008 november gun sales compared to prior year  |
| They wanted to see a comparison of this trend to other elections. | Create a pictogram of gun sale spikes by 21st century election |

### 2020 Highlight
To support the message that Americans buy guns when there is political instability, I wanted to highlight 2020, a massive year for gun sales. Three major events are correlated with the gun sale spikes, COVID-19 Shutdowns, BLM Protests, and the Biden Election. 

<div class="flourish-embed flourish-radar" data-src="visualisation/12028192"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

| **Feedback** | **Conclusion** |
|---|---|
| The "BLM Protest" label is upsidedown, can we flip it around? | Flourish doesn't allow for this, so I will clarify the label in the adjacent paragraphs. |
| "Does buying guns actually work? Do communities feel safer?"  | This is a story point I don't have the data to explore. But I could find a study to reference. |
| "Be careful making causal arguments." | In adjacent paragraphs, I will support my claims with literature review and qualify my argument. |

### Two Decade Snapshot
This animated chart is the last point in my narrative. Using the foundation of the rest of the story, I want to show that polarization and gun sales are getting out of control. It leads into my conclusion that it is not a sustainable pattern.

<div class="flourish-embed flourish-radar" data-src="visualisation/12028476"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

#### Feedback
The members of the group interview really liked this visualization and appreciated the way that the colors changed as we approached 2020. There was some brief confusion about where to read time on the graph, but with a brief explanation they understood. I asked if there was anything else that was unclear, and they said that it made sense. However, they wanted to get a clearer picture of growth in a more familiar medium, **maybe a line graph.***

I presented this visualization to Professor Goranson. I asked if it gives a clear enough perspective on two-decade trends. He suggested a bar chart or **line chart** might be better. However, the information provided by this visualization is interesting, so he suggested I include both. 

My last question to Professor Goranson was whether or not having only one kind of graph would hurt my story. He said that the radar chart takes some time to learn, but once the audience learns it, it's a powerful tool to densify data. He said that ultimately, the radar chart is interesting enough to stand alone.

#### Takeaway
Include a line chart with national sales by year alongside this animated graph in the conlcusion of the data story.



