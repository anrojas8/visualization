# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Your answer...

      My experience is in manufacturing. I explored the public Tableu website to identify examples of both effective(good) and ineffective data visualization related to manufacturing performance metrics.

      "GOOD" DATA VISUALIZATION

      https://public.tableau.com/app/profile/ghost.pepper.labs/viz/OEEDemo_0/OEEDashboard

      1. Clear purpose + audience. 
      OEE dashboards are tipically operational decision tools(maintenance/prodcution leaders), so a strong OEE dashboard usually prioritize:quick status, drivers(availability, performance/quality), and presents decision-relevanr abstractions rather than raw manufacturing data.
      A dashboard should communicate essential information for monitoring and decision-making at a glance.

      2. Clear legends and labels
        Clearly labels OEE components.
        Avoids legend overlap.
        Uses readable tick marks.
        Maintains consistent formatting.
        
      3. Appropiate use of color
        The dashboard uses color strategically. Consist color coding across A/P/Q, limited palette, status colors used meaningfull(not decoratively).

      4. Clean layout structure
        The OEE dashboard demostrates clear sectional grouping(KPI summary vs breakdown vs trend), consistent spacing, no overlapping legends, no clipped labels, visual hierarchy(primary KPI prominent, breakdown secondary)

      5. Avoids chartjunk
      This dashboard avoids unnecessary background images, avoids 3D effects, avoids decorative icons, keeps attention on metrics.

      6. Multi-view but not overhelming
      Multiple coordinated views.
      Each subplot a clear role.
      The views complement each other than compete.

      "BAD" DATA VISUALIZATION

      https://public.tableau.com/app/profile/rasell.redolosa.lingad/viz/DowntimeReviewData/ProductionAnalysis

      1. Layout density problems
      The dashboard feels packed rather than structured.
      Spacing between charts appears tight.
      Axis labels may feel compressed.
      Some charts compete for space.

      2. Over-reliance on color for meaning
      Color is a weak quantitive encoding channel. It increases cognitive load and reduces comparison clarity. This dashboard is color-heavy.

      3. Legend and labeling discipline
      Potential weakness in this dashboard:
      Legends may not clearly distinguish categories.
      Color coding may not be intuitive.
      Some labels may require interpretation rather than immediate understanding.

      4. Limited emphasis on drivers of OEE
      Downtime dashboard should clearly answer:
      What is the largest downtime cause?
      How does downtime trend over time?
      Which production line is underperforming?
      This dasboard presents many slices of downtime without Pareto ordering, no clear ranking structure, no reference line or target. The dasboard lacks decision support clarity.

      5. Weak visual hierarchy
      This dashboard increases extraneous cognitive load because multiple panels compite for attention, no dominant focal point clearly signals the primary KPI, several charts appear visually equal in importance, dense information is presented without clear visual hierarchy.
      

      ```
    - How could this data visualization have been improved?  
      ```
      Your answer...

      "GOOD" DASHBOARD

      1. Annotate major downtime drivers
      Instead of just showing downtime categories, add callouts to largest driver, highlight change events, annotate anomalies.

      2. Stronger target reference encoding
      Adding horizontal reference lines
      Encoding "above/below target" using subtle background bands.
      Actual vs target.

      "BAD" DASHBOARD

      1. Simplify and restructure layout
      Making OEE or total downtime the clear top KPI.
      Arranging supporting charts below.
      Reducing total number of charts.
      Using a 2-column structured grid.

      2. Replace weak chart types
      Sorted bar charts.
      Aligned small multiples.
      Clean time-series lines.

      3. Reduce cognitive load
      Limiting palette.
      Removing gridline clutter.
      Removing non-essential borders.
      Standardizing fonts.

      4. Remove visual noise
      Reduce overly satured backgrounds
      Reduce thick borders.
      Decorative shapes.
      Excess KPI tiles.

           
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
* Submission Due Date: `23:59 - 02/16/2026`
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
