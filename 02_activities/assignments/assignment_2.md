# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Good example: https://public.tableau.com/app/profile/fabio.fantoni/viz/WorldHappinessReport_20/WorldHappinessReport

      The World Happiness Report visualization created by Fabio Fantoni is an example of well-designed public data visualization because it communicates a complex dataset clearly and efficiently. The visualization allows users to easily explore happiness scores across different countries and regions by clicking on the map, transforming abstract rankings into an accessible and understandable global story.
      
      First, the visualization adopts appropriate visual design choices. Happiness scores are represented through color gradients and geographic positioning, which take advantage of viewers’ natural ability to perceive spatial relationships. This makes regional patterns immediately visible. For example, happiness levels in Northern Europe and North America are clearly higher than in many other regions. The color scheme is clean and well ordered, avoiding unnecessary visual distractions.
      
      Second, key variables such as country, happiness score, and ranking are clearly labeled. When users select a region on the map, only information relevant to that region is displayed, preventing information overload. This design improves efficiency by allowing users to explore the data at their own pace rather than forcing them to process all information at once.
      
      Third, the visualization uses standardized happiness scores instead of raw national statistics. This avoids biases related to factors such as population size or economic scale, enabling fair comparisons between countries. It also provides simple interaction guidance, which helps users without technical backgrounds understand the data.
      
      Finally, the visualization includes data on additional factors that may influence differences in happiness. Users can use the filters in the upper left corner to conduct focused comparisons, rather than receiving excessive information all at once. This encourages users to actively explore the underlying reasons behind global happiness patterns.

      ```
    - How could this data visualization have been improved?  
      ```
      Bad example:https://public.tableau.com/app/profile/austin.condon/viz/USPresidentialElectionResults2016/USPresidentialElectionResults2016

      The US Presidential Election Results 2016 visualization by Austin Condon is a classic example of how technically correct data can be communicated in a misleading way through poor visualization design choices.
      
      1. Electoral Votes for Each Candidate Side by Side Chart (top left)
      This side-by-side bubble chart attempts to represent each state’s electoral votes using circles. However, the sizes and spatial arrangement of the bubbles lack intuitive comparability. Viewers find it difficult to accurately judge differences in vote counts based on area, and the bubbles are not arranged according to any geographic or logical order, which increases the difficulties to read the chart. A simple bar chart would have been far more effective for quantitative comparison. This chart prioritizes visual appeal over readability.
      
      2. State by Candidate and Electoral Vote Tree Map (top center)
      The treemap suffers from the same problem. Although it represents the proportion of electoral votes, the many similarly sized rectangles make it difficult to identify meaningful differences. Color is used only to distinguish political parties and does not convey vote margins, resulting in limited informational value.
      
      3. Electoral Votes for Each Candidate Stacked Chart (top right)
      
      The stacked bar chart displays the total electoral votes for the two candidates, but the excessive use of colors make it difficult to understand what information this graph want to show. The stacks also makes horizontal comparisons between states impossible. Without active user interaction, it conveys little meaningful information.
      
      4. State by Candidate US Map (bottom left)
      
      This is a highly problematic map. It uses land area rather than population or vote counts to encode election results, exaggerating the visual weight of large but sparsely populated states while obscuring the actual distribution of voters. This type of map easily misleads viewers into perceiving the election outcome as overwhelmingly one-sided.
      
      5. Overall
      Placing multiple charts together in a single dashboard further increases burdens to read. Each subplot attempts to communicate the same result, yet the dashboard lacks consistency. As a result, viewers are exposed to a large amount of information but struggle to conclude what actually happened.

      6. How to improve
      To improve this dashboard, first, chart types that look visually interesting but are hard to compare, such as bubble charts and treemaps, should be replaced with simple, sorted bar charts (e.g., by states) that make differences immediately clear. The stacked bar chart adds unnecessary complexity and makes state-level contributions unreadable, so it would be more effective to just show total votes for both candidates. The map mainly shows land area rather than voters, and without population or vote-weighted context it misleads viewers about the true distribution of votes. So the dashboard should focus on one main view, treat other charts as supporting elements, and use brief annotations to guide viewers toward the intended takeaway (e.g., this map shows geography, not voter distribution)

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
* Submission Due Date: `23:59 - 10/26/2025`
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
