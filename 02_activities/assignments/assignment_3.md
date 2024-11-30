# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
        ```
        Your answer...
         Telecom Customers Churn Dashboard by Iaroslava:
         Accesibility: 
         This has clean layout and organized sections make the information visually appealing and easy to navigate for most users. However, as highlighted in the accessible design guidelines, it fails to account for users with visual impairments, such as colorblindness. The reliance on color-coded charts without alternative markers excludes a subset of users. Furthermore, the absence of alt-text or detailed descriptions limits its usability for those relying on screen readers.
         
         Reproducibility: 
         This visualization demonstrates some reproducibility strengths by including data sources, which is a foundational practice for transparent and trustworthy visualizations. However, it lacks documentation of the methods and tools used to create the charts, making it difficult for others to reproduce its outputs. Additionally, while being interactive supports exploration, it does not provide reproducible steps for generating similar visuals.

         Equity: 
         The visualization makes some effort to be equitable by presenting data relevant to a broad audience, such as churn metrics and segmentation. However, it does not explicitly address demographic or socioeconomic disparities that could provide deeper insights into customer churn. Furthermore, the dashboard assumes a baseline level of familiarity with churn analytics, potentially alienating less experienced users. 
 ```
         Mobile-Optimized Superstore Sales Dashboard by Agata Ketterick
         Accesibility: 
         This visualization has some significant drawbacks when it comes to accessibility. The dense layout and small font sizes compromise readability, especially on mobile devices where screen real estate is limited. The lack of high-contrast color schemes exacerbates this issue, as users with sensory sensitivities or visual impairments may find it difficult to distinguish between elements. Also, the dashboard does not include descriptive text for screen readers, limiting its reach to visually impaired users
         
         Reproducibility: 
         This visualizatiopn provides no information on the underlying dataset or the methodologies employed to produce the charts. This omission undermines the ability of users to replicate or verify the dashboard’s findings. In addition, the absence of documented processes and version control measures complicates efforts to update or improve the visualization over time.

         Equity: 
         This visualization has a dense layout and lacks contextual explanations which favors users with advanced data literacy, leaving novice users at a disadvantage. Additionally, it overlooks the cultural and regional nuances that might influence sales patterns, which are crucial for creating inclusive visualizations.  

        ```
    - How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?  
        ```
        Your answer...
        Telecom Customers Churn Dashboard
        Accessibility Improvements:
        Color Enhancements: Use color palettes or add textures and patterns alongside colors to ensure colorblind users can differentiate chart elements
        Alt-Text for Charts: Add descriptive alt-text for all visualizations to make the dashboard usable by screen readers. The alt-text should include key trends and metrics, providing a comprehensive understanding for visually impaired users

        Reproducibility Improvements:
        Documented Methodology: Include details on how charts were created, such as preprocessing methods, algorithms, or formulas. A detailed methodology ensures that others can replicate the dashboard’s outputs
        Datasheets for Datasets: Attach a datasheet documenting the data source, collection methods, and intended uses. This would provide context and ensure ethical data handling

        Equity Improvements:
        Explanatory Context: Include annotations or a narrative introduction to explain what churn metrics mean and how they are calculated. This helps bridge knowledge gaps for users with varying expertise
        Incorporate Demographic Metrics: Add data breakdowns based on demographic factors, such as socioeconomic status or geographic region, to capture how churn impacts different groups

 ```
       
        Mobile-Optimized Superstore Sales Dashboard
        Accessibility Improvements:
        Simplify Layout: Redesign the dashboard to focus on key metrics, eliminating unnecessary visuals. This reduction will help reduce cognitive load.
        Add Alternative Descriptions: Provide alt-text for charts and a detailed summary of the dashboard’s purpose and findings. This will make the dashboard accessible for visually impaired users relying on screen readers

        Reproducibility Improvements:
        Include Data Sources: Clearly identify the data sources used for the dashboard, including links or citations, to allow users to verify and trace the data
        Document Analytical Methods: Provide a step-by-step guide or overview of the analysis performed to create the visualizations, including any calculations or transformations

        Equity Improvements:
        Add Educational Annotations: Include explanations of key metrics and their implications, such as the impact of sales on specific categories or customer segments, to make the dashboard more inclusive for non-experts

        ```

- Word count should not exceed (as a maximum) 300 words for each visualization. 

### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses learning outcomes 2 and 3:  
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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * This markdown file (assignment_3.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
