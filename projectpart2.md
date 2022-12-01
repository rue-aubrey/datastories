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

<div class='tableauPlaceholder' id='viz1669862555776' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gr&#47;Graph1Final&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Graph1Final&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gr&#47;Graph1Final&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    
  var divElement = document.getElementById('viz1669862555776');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                   
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

### **Option 2**
I used Flourish to create radar chart, which I got the idea for when researching the concept of "data densification." Because I need to show mutliple events and their corresponding gun sales, there will be a lot of graphs on the final website. Line graphs are intuitive, but can get overwhelming in large numbers. I hoped a radar chart could present the data more compactly.

<div class="flourish-embed flourish-radar" data-src="visualisation/11998115"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Interview with A, a 22 year old CMU student
I presented Option 2 to A. This version had no radial axis to show quantity of gun sales. I gave him no context about the story I was telling, and he was confused about what the chart meant. The outwardness of the lines (distance from the origin) didn't carry the immediate meaning of *more* that I wanted. After I explained, he got exactly what I meant. To clarify the purpose of the chart, I decided to add annotations to clarify when Obama's election is on the chart. 

He said, "Highlight the dimensions more. I want to be able to get numbers out of the lines." In response to this critique, I added radial axis lines with boldened labels.

When I showed A Option 1, he liked it much more, saying, "The scale is much clearer and more intuitive." This reflected his earlier opinions that about Option 2 being harder to read for specific quantities. 

#### Takeaway
In the end, his recommendation was that I use the line chart. However, when trying to include Option 1 in Shorthand, the Tableau embed looked unprofessional and unclear. The black background didn't keep and the axis was cropped short of the full 12 months. This biased me towards Option 2, which is in Flourish.

## 3. How should I synthesize story and data?

I combined the introduction text and Option 2 graph on Shorthand, shown in the screenshots below. I brought them to B for feedback.

![image](https://user-images.githubusercontent.com/39631332/204965127-0c5c52d7-5efd-404c-a514-e0c0bbdf13c0.png)
![image](https://user-images.githubusercontent.com/39631332/204964963-1ab5f069-5ac0-43fa-be7d-66168aa62c27.png)


### Interview with B, a 24 year old photographer

First, I showed B the Shorthand draft with the embedded Flourish radar chart from Option 2. Within the context of the story, the graph made "immediate sense" to her. Afterwards, I showed her Option 1 from before for comparison. 

#### Feedback and Changes for Shorthand visualization:

| **Feedback**                                                    | **Changes**                                                                             |
|-----------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| "Prior Years" isn't specific enough.                            | I will change the legend to read "2000-2007" and "2008."                                |
| She wanted to be able to look more closely at the data.         | I will refine the popup function                                                        |
| She wanted to be able to see growth in gun sales through years. | I will add a final visualization that animates gun growth nationally from 2000 to 2020. |

#### Comparison to Option 1 line chart from before
She said the line chart was much "simpler," and should be easier for the average person to intuitively understand. However, she qualified that the line chart was less visually interesting. The radar chart from Option 2, by comparison, had a much more "polished" presentation, with a "wow-factor."

In response, I asked which option would look best on a webpage. Specifically, I asked, "Which visualization would be less cluttered and overwhelming when replicated multiple times." She answered Option 2, the radar chart in Flourish. She said, "it communicates the specific message much more clearly."

#### Takeaway
I will continue to refine the radar chart in Tableau, leaving the line chart alone for now.






## Polishing the Visualization

<div class="flourish-embed flourish-radar" data-src="visualisation/11997932"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
