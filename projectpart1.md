# Part I: Project Outine

## Summary
For this project, I want to interrogate the events underpinning the increased sale of guns across the past few decades, emphasizing their intimate relationship with political violence and mass shootings.

I'm writing this on the day I woke up to news of the [Club Q nightclub shooting](https://www.cnn.com/2022/11/20/us/colorado-springs-shooting-gay-nightclub), where 30 people were shot and 5 killed. This day brings back memories of the Pulse Nightclub shooting in 2016, when over 100 people were shot and 49 killed. Another instance of targeted political violence.
 
Today is Trans Day of Rememberance, where members of the LGBT community remember trans people lost to hatred and violence. Seeing LGBT people at the center of escalating attacks is scary, and I wanted to give some understanding to how this violence plays into the increased targting of marginalized groups and arming of political factions.

## Outline
1. **Introduction** of a personal story with my father buying several guns for the first time right after the election of Obama in 2008. 
  * ![Sketch of Personal Story](https://github.com/ruesellers/datastories/blob/main/assets/obamaelection.png?raw=true)
3. **Basic Question**: How central are guns to America's politics? 
   * Example of gun laws and elections affecting gun sales, who do we think is buying?
   * [The gun industry is growing, so is violence](https://www.forbes.com/sites/elizabethmacbride/2018/11/25/americas-gun-business-is-28b-the-gun-violence-business-is-bigger/?sh=187be5ca3ae8)
4. **New perspective**: when else do gun sales increase?
   * [*Study*: Evidence of violence escalating gun sales]((ht)tps://www.ncbi.nlm.nih.gov/pmc/articles/PMC7369030/))
   * Violence leads to gun sales leads to violence
7. **Thesis Case 1**: State-level perspective after mass shooting
   * ![Sketch of Violent Events Zoomed in on One State](https://github.com/ruesellers/datastories/blob/main/assets/stateguns.png?raw=true)
9. **Thesis Case 2**: State-level perspective after mass shooting
10. **Thesis Case 3**: January 6th or 9/11, national-level perspective
11. **Why does this matter** November 20th Trans Day of Rememberance Colorado Shooting, Club Q
  a. the threat of armed right-wing extremists to marginalized communities
     * Arming of the nation
     * ![Nation-wide Perspective](https://github.com/ruesellers/datastories/blob/main/assets/gunnation.png?raw=true)c

## The Data
The [dataset](https://github.com/BuzzFeedNews/nics-firearm-background-checks/tree/master/data) is provided by BuzzFeedNews via their Github repository. They sourced their data from the FBI's National Instant Criminal Background Check System. The data are the number of firearm background checks by month, state, and type from November 1998 to October 2022, parsed from official PDF documents by Jeremy Singer-Vine.

I will use the background check data to estimate the number of *sales* per month by state. According to [a New York Times analysis](http://www.nytimes.com/interactive/2015/12/10/us/gun-sales-terrorism-obama-restrictions.html), gun sales and background checks cannot be understood as one-to-one because of differing state laws around guns.

Instead, the New York Times used this calculation to estimate sales: "Each long gun and handgun check was counted as 1.1 sales. Each multiple-gun check was counted as two sales. Permit checks and other types of checks were omitted." For consistency, I will be using the same calculation:

Gun Sales = (Long Gun Check + Handgun Check) × 1.1  +  (Multiple-Gun Check) × 2

I hope to analyze these data along the monthly timescale to understand the relationship between mass shootings, major political events, legislation, and gun sales – all understood from state-level upwards.

## Additional Data Options
1. Hate Crime Data and Hate Rhetoric
2. State populations for **Gun Sales per Capita**

## Method and Medium
I will tell my story through Shorthand. It will begin with a more person-centered story and move on to data-specific cases, highlighting specific events and locations and what the data shows happened around that event.
