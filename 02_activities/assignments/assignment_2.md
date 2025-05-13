# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      All referenced slides for both questions are from slide deck 4: choosing the right visualization.

      Good visualization:

      As the good visualization example, I chose the following NBA Shots visualization by Zak Gels: https://public.tableau.com/app/profile/zakgeis/viz/NBAShots_15945788351370/NBAShots. This visualization, intended for exploring and comparing, allows people to explore and compare shooting patterns across players, teams and seasons in the NBA (slides 53-56). It is visually appealing and clear, showing both aestheitic value and perceptual clarity. It is also substantive, focusing on insight with a neutral tone, making it easy to understand what the data means (slide 50). This is further supported by the legends below the visualization. 

      Further, the visualization uses dots as marks to represent shot attempts, position (to encode the location of the shot attempt), colour (to encode shooting success as a heat map) and size (to encode shooting frequency) as channels. The use of appropriate marks and channels like this makes the visualization easy to understand (slides 19-22). In addition, the use of an intuitive basketball court layout reduces the cognitive load to follow the visualization (slide 31). The visualization also follows the guidelines from slide 32, overview then zoom then details. We can start with a general overview of team-level data, zoom into specific years, filter by individuals players and access details on demand by interacting with the visualization (tooltips showing shot type, success percentage, league comparison etc.)

      Bad visualization:

      As the bad visualization example, I chose the following Most Popular NBA Teams by County by Matt Watson - TicketNetwork: https://public.tableau.com/app/profile/matt.watson2889/viz/NBAFanMap_15644286889460/NBATeamsCountyMap. Thhis visualization intends to compare which NBA team is most popular in each county across the United States. However, as the second part of the creator's name suggests, the underlying goal is to sell game tickets. This is further demonstrated by a "Click here to buy tickets" hyperlink appearing when we hover over any county. 

      The use of channels is highly ineffective. Specifically, the visualization uses color to encode teams without sufficient contrast or explanation (slides 19-22). For example, shades of red and blue account for a multitude of teams, and there is no clear legend. Clicking to get further information also indicates a level of strength in a county but this is not reflected by the color channel. Further, the visualization requires a high cognitive load to grasp what's going on. Counties are small and numerous, which makes it hard to interpret fan patterns, and this forces us to hold lots of information in our working memory, violating the cognition over memory best practice (slide 64.) Last, the visualization provides no citation or sources for the data it is visualizing, which violated the principle that citing sources boosts transparency and credibility (slide 66).
      ```

    - How could this data visualization have been improved?  
      ```
      Good visualization:

      The good visualization can be improved by using a colourblind-friendly palette or introducing pattern or shape encodings over colour for shot succes. This would improve accessibility by improving inclusive design and enhance clarity for all users (slide 54). There are also elements of cognitive load that can be improved. At its current state, the visualization has a exploratory rather than an explanatory composition, where the audience navigates it alone instead of being guided through step by step (slide 64). Having an explanatory composition here could entail including guided walkthrough or a story mode feature to show key insights without needing to manually explore.

      Bad visualization:

      There is a lot wrong with this one, but the bad visualization can start to be improved by addressing the colour use and incorporating a legend (slides 19-22). At its current state, colours lack clear contrast and meaning and this can be improved by using a colour scale with strong perceptual differences and providing a legend. The channel issue itself can be fully addressed by completely changing the map style. The US map with counties presented this way misrepresents fan base by area instead of population. Using circle sizes to encode fan count in the included counties would better represent counts. In addition, the audience cannot assess the trustworthiness of the graphic and it cannot be reproduced. The visualization should include a data source citation and elaborate more on the methodology, incorporating a sample size.
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 30/04/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
