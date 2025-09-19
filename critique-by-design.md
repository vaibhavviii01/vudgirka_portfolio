| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique and redesign (MakeoverMonday)

_Link to Original Data Visualization_ : https://resume.io/blog/which-country-gets-the-most-paid-vacation-days

## Step one: Choosing the visualization

Visualization Used: “Which Country Gets the Most Paid Vacation Days” by Resume.io
Source: Resume.io Blog
URL: https://resume.io/blog/which-country-gets-the-most-paid-vacation-days

Why I Selected This Visualization?

I chose this visualisation because paid vacation days are an internationally relevant topic, with clear implications for work-life balance, labour rights, and cultural variations between countries. The original chart clearly highlighted international variations in statutory paid leave and public holidays, but it was presented in a cluttered and difficult-to-read format. For example, it did not clearly distinguish between the two contributing components (paid leave days and public holidays), nor did it highlight notable exceptions such as the United States (0 days) or Iran (53 days).

– In my redesign, I used stacked horizontal bar charts to illustrate how total vacation days are divided between statutory paid leave and public holidays.

– Use stacked bars with labels to distinguish between two categories and display totals.

– Top 10 and Bottom 10 Panels: Showcases both the greatest and worst situations without overwhelming the spectator.

– Annotations and Subtitles: Highlight crucial ideas (Iran has 53 days of statutory leave, while the United States has none).

– Consistent Colours: Dark blue for statutory leave (formal and stable), teal for public holidays (lighter, joyous).

– These choices enhance comparison, provide context, and create a narrative flow from best to worst scenarios.

## Step two: Critique the Data Visualization

The Resume.io maps on paid vacation days caught my attention right away with their vibrant colours and quirky design, but I found them more difficult to understand than I had anticipated. When you see how stark the differences are, such as Iran's 53 days vs the United States' zero statutory leave, the maps do a fantastic job of drawing attention and igniting discussion. However, the crowded labels and faint colour ranges made it difficult to compare countries directly as I attempted to make sense of the data. I also found that the definition of "paid leave" and the source of the data were not well explained, which left me with several unresolved doubts. Although I can understand why these images are effective for a broad audience, they are entertaining, shareable, and create discussion, if I were rebuilding them, I would probably use bar charts or include numbers to help simplify the story. I felt like it served as a helpful reminder that, when actual comprehension is the goal, clarity and context are just as crucial as aesthetics and engagement.

## Step three: Sketch out a solution
Following my critique of the Resume.io maps, I began to consider how I may redesign the visualisation to make it more understandable and practical for comparison while maintaining its appeal to a broad audience. Although the initial choropleth maps are eye-catching and vibrant, they rapidly become congested and make it difficult to compare nations directly, particularly smaller ones.

- Instead of using maps for my makeover, I would like to employ stacked horizontal bar charts. This will enable me to:

- Keep public holidays and statutory paid leave distinct while still displaying their total.

- Create two panels: the Top 10 countries with the most vacation days and the Bottom 10 countries with the fewest.

- The subtitles to give context (e.g., Iran leading, U.S. with 0 statutory leave), while the titles will frame the primary subject.

_I drew a basic wireframe using pen and paper:_

- Each of the two vertically stacked panels has a title and a subtitle.
  
- Every nation is represented by a horizontal bar with two colours: lighter for public holidays and darker for mandatory leave.
  
- Labels with numbers inside the bar and a bold sum at the end.

This wireframe maintains the original narrative elements while increasing clarity and simplifying comparisons. In order to overlay annotations, alter labels, and test out interaction if necessary, I would probably construct the redesign in Tableau.

## Step four: Test the solution

Procedure for Testing - 

I showed to my peers my updated visualisation, which consists of stacked bar charts that rank the top and bottom 10 nations by the total number of paid vacation days. I let them make their own interpretations of the chart rather than explaining it to them. To facilitate the feedback session, I wrote a brief interview script.

Script / Questions: 

Can you tell me what you think this is?

Can you describe to me what this visualization is showing?

Is there anything you find surprising or confusing?

Who do you think is the intended audience for this?

Is there anything you would change or do differently?

Feedback : 

i. Mid-20s student: "It's obvious that the United States has the fewest and Iran has the most." I appreciate the way the numbers are shown, however it took me a moment to distinguish between public holidays and mandatory leave.

ii. Student, BME program: "The titles and subtitles are useful, but I wonder if the colours could be adjusted slightly to make the two parts stand out more"

iii. Student, with prev business analytics experience: "It's much easier to read than the original maps, my only recommendation would be to have both charts on the same dashboard and to lessen the amount of text (decimal points) inside the bars.” 

Feedback Patterns

- I didn't have to explain the key plot point, which was the extremes between Iran and the United States.
  
- Although there was a repeated recommendation to make the labels simpler, everyone thought the layout was clearer than the original.
  
- Although colour difference was often apparent, one person recommended experimenting with different palettes.
  
Insights: 

In addition to highlighting areas for improvement, such as reducing label clutter and testing colour accessibility, the comments indicated that the redesign had successfully enhanced clarity and storytelling. With these changes, the end result will be even more easy to understand.


## Step five: build the solution

I intended to make it evident which nations provide the most and the fewest paid vacation days by dividing the totals into public holidays and statutory paid leave days in this visualisation. I utilised stacked horizontal bar charts in place of the original's cluttered world map to make comparisons clearer and easier to read. To allow readers to easily observe both extremes, I divided the chart into two panels: one for the top ten countries and one for the bottom ten. The most surprising aspects of the tale are told by the prominent outliers, such as Iran, which has 53 total days of statutory leave, and the United States, which has none. My objective was to strike a balance between narrative and clarity so that the viewers would get the distinctions right away and require minimal further explanation.

Link to my redesign: https://public.tableau.com/views/TSWD_MakeoverMonday_vudgirka/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

<div class='tableauPlaceholder' id='viz1758250438407' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWD_MakeoverMonday_vudgirka&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSWD_MakeoverMonday_vudgirka&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWD_MakeoverMonday_vudgirka&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1758250438407');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} 
  else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} 
  else { vizElement.style.width='100%';vizElement.style.height='727px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


## References
https://resume.io/blog/which-country-gets-the-most-paid-vacation-days

## AI acknowledgements

I used Gen-AI to help me understand the dataset and the article, brainstorming and framing the title and subtitle of the dashboard. 


