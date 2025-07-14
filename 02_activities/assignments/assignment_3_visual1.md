# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    
    Visualization 1

    > What software did you use to create your data visualization?
    I used the Seaborn and Matplotlib libraries of Python.

    > Who is your intended audience? 
    The intended audience includes public health officials, policymakers, and potentially the general public concerned with water quality and recreational beach safety.

    > What information or message are you trying to convey with your visualization? 
    The visualization aims to highlight temporal trends in E. coli contamination at different beaches from 2006 to 2025. Dots represent daily average levels per beach, while asterisks show the monthly average, giving a picture of long-term trends and variability. The red dashed line indicates a safe threshold (200 UFC/100 mL), helping viewers easily identify exceedances.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Clarity and readability: Labels, descriptions, and titles in adecuated fonts.
    Color distinction: Assigned different hues to each beach to differentiate between locations.
    Temporal legibility: Used a date formatter to display x-axis labels by month/year and rotated labels to avoid overlap.
    Visual hierarchy: Dots for daily values and asterisks for monthly averages.
    Reference line: Added a dashed red line at the safe limit to anchor interpretation.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Reproducibility was ensured by using a script-based approach in Python, which can be run multiple times with the same results, as long as the dataset and packages remain consistent. Comments where added explaining each action made.

    > How did you ensure that your data visualization is accessible?  
    >Accessibility was addressed by using high-contrast colors for clarity, including text labels, such as the y-axis reference line for safety limits and choosing readable fonts (Verdana, Arial).

    > Who are the individuals and communities who might be impacted by your visualization?  
    Local communities and beachgoers, health departments and environmental monitoring agencies, and researchers and academics studying water quality or environmental change.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I focused on the daily and monthly averages of E. coli levels by beach and excluded the specific site of the collection, in order to avoid a higher cognitive load.

    > What ‘underwater labour’ contributed to your final data visualization product?
    The “underwater labour” included data cleaning and preprocessing (aggregating raw E. coli measurements by day and month, handling missing data, standardizing date formats, etc), testing different styles, color palettes, and layouts, and annotating the code to ensure reproducibility and clarity.

    Visualization 2

    > What software did you use to create your data visualization?
    I used Microsofot Excel to create a pivot table and a pivot chart.

    > Who is your intended audience? 
    The intended audience includes environmental scientists, data analysts, and public health officials who are involved in the planning, monitoring, and assessment of water quality sampling.

    > What information or message are you trying to convey with your visualization? 
    The primary message of the visualization is to show the distribution and frequency of water quality samples collected over time for each sampling site. This can help identify trends in sampling efforts (e.g., if certain sites are monitored more frequently than others) and highlight potential gaps in data collection.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Clarity and simplicity: Labels, descriptions, and titles in adecuated fonts.
    Interactivity: the chart is dynamic so filter options are available for users to select specific months or sampling sites.
    Color scheme: Used distinct, contrasting colors for each sampling site.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Saving the spreadsheet with both raw and processed data, and using formulas (like TEXT() for extracting month-year). However, reproducibility is limited compared to code-based tools (e.g., Python), since manual steps are harder to track and version control is minimal. This may reduce transparency for others trying to reproduce the process exactly.

    > How did you ensure that your data visualization is accessible?  
    Accessibility was addressed by using high-contrast colors for clarity, including text labels and choosing readable fonts (Verdana, Arial).

    > Who are the individuals and communities who might be impacted by your visualization?  
    Local communities and beachgoers, health departments and environmental monitoring agencies, and researchers and academics studying water quality or environmental change.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I focused on the number of samples per month and per site because this was the key metric I wanted to visualize. I excluded other data points, such as E. coli levels, since the focus of the visualization is on sampling frequency rather than data results.

    > What ‘underwater labour’ contributed to your final data visualization product?
    The “underwater labour” included data cleaning and preparation (0rganizing raw data, creating new columns), setting up the pivot table ( selecting the right fields, grouping data by month, and summing the number of samples for each site), choosing chart options (deciding on the type of chart (bar chart) and customizing it for clarity, adjusting axis scales, colors, and size), and fine-tuning the chart's visual design by adjusting font sizes, adding titles, and ensuring readability.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 13/07/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
