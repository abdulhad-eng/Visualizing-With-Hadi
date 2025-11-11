| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Title

# Redesigning India’s Coal Production Visualization for Clarity and Comparative Insight

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization

### Original Visualization
![Original Visualization – Indian Coal Production](1DmkisQ2OUIvOMnPg2vg_Screenshot%202021-01-20%20at%209.14.50%20pm.png)

*Source: [Makeover Monday Week 4 Dataset – data.world](https://data.world/makeovermonday/2021w4)*

I selected this visualization because it attempted to show **Coal Production (MT)** and **Number of Mines** for Indian districts in a single bar chart. However, the dual-axis approach made it confusing—two different metrics were plotted together without clear labeling or logical comparison.  

I chose it because it had strong potential: it contained rich data and a real opportunity to tell a meaningful story about **which states produce the most coal** versus **which produce it most efficiently**. The original design buried that insight under clutter, color overload, and scale confusion

## Step two: the critique

After evaluating the “Indian Coal Mine Production” visualization using Stephen Few’s *Data Visualization Effectiveness Profile*, I found that while the dataset itself was valuable, the chart failed to communicate insight effectively. It scored low on usefulness (3/10), completeness (4/10), and perceptibility (3/10), showing that the design made interpretation unnecessarily difficult. The dual-axis layout confused the comparison between production and number of mines, and the lack of context—such as efficiency or production per mine—left the viewer guessing about meaning.

The visualization was somewhat truthful (8/10) since the data appeared valid, but it lacked intuitiveness (4/10) and engagement (4/10). It didn’t invite exploration or tell a story; instead, it presented raw data in a cluttered form. Its aesthetics (5/10) were neutral—neither distracting nor compelling.

The intended audience likely includes policymakers, journalists, and analysts seeking insight into regional production patterns. However, the visualization doesn’t help them answer key questions such as *Which states are most productive?* or *Which are most efficient?*  

In my redesign, I plan to separate total production and efficiency (production per mine) into two clear bar charts, sorted in descending order and color-coded to highlight the top five performers. I’ll also refine titles, labels, and context to help the audience understand the story instantly without effort.

## Step three: Sketch a solution

For my initial redesign sketch, I created a draft Tableau view comparing **total coal production by state** and **production efficiency (production per mine)**. This prototype allowed me to explore how separating production and efficiency could reveal different patterns across regions.

In this stage, my goal was not visual polish but conceptual clarity — I wanted to test if these two metrics could be understood independently and still tell a cohesive story. I used color to highlight top-performing states while keeping the rest neutral to preserve context. The descending order helped surface India’s leading producers and most efficient states at a glance.

Below is the early sketch version of the redesign:

![Preliminary Tableau sketch showing coal production and efficiency comparison](Dashboard%201.png)

## Step four: Test the solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask (modify these for your own interviews): 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._


| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|          |             |             |
|          |             |             |
|          |             |             |

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

