# Data Viz Re-Design 2: NISMART

## NISMART Missing Children Statistics

![NISMART Statistics](MissingChildOriginal.JPG)

I selected this data to redesign because I think it is a great example of a table that makes sense in the context it was presented in, 
in that it provides specific values and percentages. However, it also leaves much room for experimentation when it comes to presenting 
the data in a way that helps the viewer to visualize how each category of missing child relates to the others.

## My Process
I began by completing a critique of the original visualization according to Stephen Few's Data Visualization Effectiveness Profile.
Through this process I began to realize how much potential there was to turn this data into something much more visually stimulating. I also took note of how much more cluttered the table was than it needed to be, which I had not noticed before. The audience could be trusted to figure out most of the cluttering information, especially in its original context, being a part of a research paper which provided further information and context on the subject. 

Next, I created the wireframe which required me to think creatively in the different ways this information could be represented. I first
went through an iteration of a layered bar graph which looked nice, but didn't allow for an accurate presentation of the percentages. Each set of percentages were a part of a separate 100%, rather than both being a part of the same whole. For this reason, I opted to create a second wireframe using a scatter plot, which allows for two separate sets of percentages on each axis and is able to show the size of each category by simply changing the size of the points. 

![Wireframe 1](Wireframe1.jpg)

![Wireframe 2](Wireframe2.jpg)

Collecting user feedback at this stage turned out to be incredibly valuable as it allowed me to gain an understanding of how the information in the visual came across (or didn't come across) to others, who weren't steeped in the information. Through these conversations it came to my attention that some of the labels used in the original table (ie. "Counted as Caretaker Missing") was confusing to the readers. For this reason, I changed the title of my y-axis to "Percent Missing to Caretaker" to more accurately describe what was included in that category.

## The Final Product
This final version of my visualization presents this data on Missing Children, their categorization, and the percent that is missing to the caretaker in relation to the percent of cases that are reported to an official. The further along the y-axis, the more of the cases involved the caretaker being aware that the child was missing, and the further along the x-axis, the more of the cases were reported. The size of each circle represents the number of cases documented.

![Final Redesign](redesign2.JPG)

<div class='tableauPlaceholder' id='viz1573655818241' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mi&#47;MissingChildrenRedesignv2&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MissingChildrenRedesignv2&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mi&#47;MissingChildrenRedesignv2&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div> <script type='text/javascript'> var divElement = document.getElementById('viz1573655818241'); var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px'; var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';      vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>


[Go Back to Home Page](/README.md)
