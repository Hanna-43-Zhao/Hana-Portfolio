| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Title
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization

[Forbes: World’s Highest-Paid Athletes](https://www.forbes.com/lists/athletes/?sh=162054105b7e)
_Include link to the original data visualization (or screenshot - make sure to correctly cite your sources, etc.).  
I selected this data visualization because the topic is interesting and highly engaging for a broad audience. The earnings of top athletes spark curiosity worldwide and connect to everyday conversations about sports, money, and fame. What's more, The source of the information which is forbes is also highly credible and widely recognized.

At the same time, while the dataset is rich in information and provides a comprehensive breakdown of athlete earnings, the original visualization is limited in how effectively it communicates insights. Table makes it harder for viewers to immediately see patterns across sports, countries, or the balance between on-field and off-field income. I think these shortcomings making it a strong candidate for redesign because there are many opportunities to highlight key stories, simplify comparisons, and make the data more visually impactful.

## Step two: the critique
### Strengths
- Accuracy: The source (Forbes) is reliable, and the dataset is transparen.
- Completeness: All the essential information is there.  
- Clarity of facts: As a lookup tool, it works well for quickly finding an athlete’s exact numbers.  

### Weaknesses
- Low perceptibility : The table forces readers to scan row by row and mentally calculate comparisons. It doesn’t surface patterns or relationships automatically.  
- Weak storytelling: There is no visual guidance toward insights such as which sports dominate, which athletes rely most on commercial income, or how geography affects distribution.  
- Limited engagement: While useful as a database, it fails to spark curiosity or discussion because it looks flat and purely informational.  

### Overall Reflection
Overall, the visualization is useful as a reference but ineffective as a storytelling tool. The design is plain and invisually, misses the opportunity to highlight trends, contrasts, or narratives that the data could reveal. Next step, I aim to highlight key themes and make the story clearer. I will use stacked bar charts with distinct colors to show on-field vs. off-field income, add sport-based colors to reveal which sports dominate, and include national flags to emphasize geographic patterns. To make the visualization more engaging and accessible, I also plan to incorporate athlete headshots for easier recognition.


## Step three: Sketch a solution
![IMG_0405](https://github.com/user-attachments/assets/e9e8a020-504a-4fb7-b287-e7fe10fb1e60)

Below is my initial sketch for the redesign. At this stage, I began translating the critique insights into a visual plan. From the critique, I realized that the original table lacked perceptibility and storytelling, which guided me to focus on highlighting contrasts and patterns more clearly.The sketch highlights how I plan to:  

- Use stacked bar charts to compare on-field vs. off-field income.  
- Add filiters for nationality and sports, so the audience can interact with the data and focus on the groups or comparisons most relevant to them.  
- Include national flags to emphasize geographic distribution.
- Add athletes’ photos to make the visualization more engaging and easier to recognize.

I also drew inspiration from a Statista chart on the world’s highest-paid athletes (https://www.statista.com/chart/14130/the-worlds-highest-paid-athletes/). The chart is visually engaging, but I found two key limitations that shaped my redesign ideas. First, its interactivity is limited。the audience cannot explore data in their ways. Second, it only highlights eight athletes, which makes the story less representative. In my redesign, I aim to improve on these points. I can have interactive filters in my chart, also includa larger dataset (Top 25 athletes) to present a more complete and insightful picture.


## Step four: Test the solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask (modify these for your own interviews): 

- When you first see this, what do you think it’s showing?

- What story or insight do you get from the visualization?

- Is the split between on-field and off-field income clear to you?

- Do the colors, flags, or photos help you understand better, or do they feel distracting?

- If you could change one thing to make it clearer, what would it be?


Results: 

| Question                                                                                 | Interview 1                                                                                                                             | Interview 2                                                                                                                                     |
| ---------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| When you first see this, what do you think it’s showing?                                 | It looks like a ranking of top-paid athletes, but I wasn’t sure at first what "on-field" and "off-field" meant.                         | I could tell it’s about income breakdown, but I'm not sure what is "on-field" and "off-field"                 |
| What story or insight do you get from the visualization?                                 | I quickly noticed there are lots of U.S. athletes are included compared to other countries. That stood out me. I also can recognize a lot of U.S. athletes because they are too famous.           | Shohei Ohtani’s case jumps out—his off-field income is so much higher than others, it makes me wonder why.                                      |
| Is the split between on-field and off-field income clear to you?                         | The stacked bars make it visually clear, but the terminology confused me. Maybe simpler terms like “sport earnings” vs. “endorsements.” | The split is easy to read, but I think the contrast could be even sharper with stronger colors.                                                 |
| Do the colors, flags, or photos help you understand better, or do they feel distracting? | The flags are really helpful, but the athlete photos might be weired especially since there are 25 people here. Flags really help me to recognize athletes' nationality, it will be better if add legend                   | I like the idea of photos because I don’t follow sports closely, faces would help me, but technically it may be too hard to implement in Tableau. |
| If you could change one thing to make it clearer, what would it be?                      | I’d adjust the wording of income categories, or add a note on the bottom of the chart.                                                                  | I’d add filters by sport or country so I can focus on one group at a time instead of scanning the whole chart.                                  |

Synthesis: 

From the two interviews, several patterns stood out.

First, both interviewees were confused by the terms “on-field” and “off-field”. While the intended audience might be sports fans who already know these terms, for a broader audience I should clarify them. Adding a short note at the bottom of the chart would make the distinction more accessible.

In terms of storytelling, one person pointed out how many American athletes dominate the list, while the other was struck by how much of Shohei Ohtani’s earnings come from endorsements. This shows that geography and unique outliers naturally capture attention and add discussion value. It also confirmed that the design choices I made—such as adding flags and highlighting categories—do strengthen the narrative dimension of the visualization.

As for design elements, both found the national flags helpful. Feedback on athlete photos was mixed: one thought they could add personality, while the other worried they might clutter the view, especially since showing 25 photos would be overwhelming. I’ve decided not to include photos in the final design for clarity and feasibility in Tableau.

Finally, at least one interviewee suggested the ability to filter by sport or nationality. This aligns with my original plan but my sketch couldn’t show it.

Based on these feedbacks, for my final redesign, I plan to (1) Add notes to explain “on-field/off-field”, (2) keep the flags but drop the photos, and (3) add interactive filters for sport and nationality to make exploration easier.

## Step five: build the solution
<div class='tableauPlaceholder' id='viz1758249382745' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='The Top 25 Highest-Paid Athletes On-Field vs. Off-Field Income Across Sports and Countries ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Th&#47;TheTop25Highest-PaidAthletes-HZ&#47;Sheet12&#47;1_rss.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz'  style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
    <param name='embed_code_version' value='3' /> 
    <param name='site_root' value='' />
    <param name='name' value='TheTop25Highest-PaidAthletes-HZ&#47;Sheet12' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Th&#47;TheTop25Highest-PaidAthletes-HZ&#47;Sheet12&#47;1.png' /> 
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
  </object>
</div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1758249382745');                    
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

In this final version, I built the visualization directly in Tableau, which made it more feasible and allowed me to make some practical adjustments while still keeping the original design concept. Through this process, I also learned new Tableau techniques such as using dual axis, synchronizing axes, and inserting country flag images. These adjustments not only improved the functionality of the visualization but also enhanced its clarity and storytelling power.
The final chart also revealed several meaningful insights. Cristiano Ronaldo’s dramatic lead highlights how exceptional cases can dominate the rankings, reflecting both his longevity and unmatched brand appeal. Shohei Ohtani’s income structure shows how his off-field endorsements far exceed his on-field salary—his unique position as a Japanese player in Major League Baseball allows him to capture both the Asian and U.S. markets, making him one of the most commercially valuable athletes in the world. The strong presence of American athletes demonstrates the high degree of commercialization in U.S. sports, supported by a passionate fan culture and a robust economy. Finally, the sport-specific differences are striking: football players earn primarily from on-field salaries, while basketball and soccer players rely much more on off-field endorsements, illustrating how global popularity and sponsorship opportunities shape different income structures across sports.

## References
Forbes. “The World’s Highest-Paid Athletes.” Forbes.com. Retrieved from https://www.forbes.com/lists/athletes/?sh=162054105b7e
Statista. “The World’s Highest Paid Athletes 2023.” Statista.com. Retrieved from https://www.statista.com/chart/14130/the-worlds-highest-paid-athletes/


## AI acknowledgements
I occasionally used copilot to address specific Tableau questions and refine my writing, but all analysis, design work, and the final visualization were carried out by myself.

