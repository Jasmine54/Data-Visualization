| [Home Page](https://jasmine54.github.io/Data-Visualization/) | [Assignment-1](Assignment-1.md) | [Assignment-2](Assignment-2.md) | [Assignment-3&4](Assignment-3&264.md) | [Final Project I](final-project-part-1.md) | [Final Project II](final-project-part-2.md) | [Final Project III](final-project-part-3.md) |

# Assignment 2: High Street Coffee Caffeine Content


## Orginal Data Visualization
![image](https://github.com/Jasmine54/Data-Visualization/assets/120682452/abeb637b-e1c5-490c-b20f-06ddbc89617e)

*Source: https://www.which.co.uk/news/article/caffeine-levels-in-high-street-coffees-vary-significantly-which-finds-ay7cA4G1zh1S*


**Why did I choose this Data Viz?**

As a coffee enthusiast, the subject of caffeine content in coffee resonates with my personal interests.  I find that understanding the quantity of caffeine I consume is essential, not just for the enjoyment of the beverage but also for maintaining a balanced lifestyle.  Many others share this sentiment due to personal, dietary, or health reasons.

Access to information about caffeine content empowers us all to make informed decisions.  It's not just about knowing the numbers;  it's about appreciating how these figures translate into daily life and personal well-being.  The data visualization serves as a crucial tool in this respect, offering clear comparisons between major coffee brands.  This insight is particularly beneficial for those of us who wish to manage our caffeine intake judiciously while still savoring our cherished coffee rituals.

## Data Visualization Critique
**What Stands out：**

- The significant variation in caffeine content across different chains for the same type of coffee. For instance, a single-shot espresso ranges from 33mg at Starbucks to 180mg at Pret.
- Starbucks has the lowest caffeine content across all three coffee types when compared to the other chains.
 
**What works well:**

- The use of illustrations can seize the readers' interest, vividly convey the subject matter, and imbue the visualization with a sense of everyday familiarity and relevance.
- Considering the variations in drink size for the same type of coffee across different brands, and gathering and presenting the relevant data, provides the necessary context for comparing caffeine content.
- The layout is clean and the data is presented in a clear tabular format.

**What didn’t work well:**

- The caffeine content figures fail to provide an intuitive and straightforward comparison for the reader, making it challenging to assess the minimal differences in caffeine content across different coffee brands at a glance. 
- Even with the provided drink sizes, there is a risk that readers might overlook these cues; also, the abundance of numbers can make the information appear cluttered and overwhelming. 
- The bold annotations on the bottom are intended for emphasis, instead, scatter the viewer's attention. 
- The black font on a blue background does not stand out sufficiently, which could hamper readability.


**General Comments**

- Relevance and Context: While the visualization captures the interest of the audience with popular coffee chains and drink choices, it falls short of providing essential contextual information about why these caffeine levels might be significant. For example, it doesn't compare these levels to recommended daily limits or explain the potential health impacts of varying caffeine consumption.
- Clarity and Comprehension: The large font and clear categorization aid in accessibility, yet the visualization does not facilitate an intuitive understanding of the data. The figures require the reader to actively process numerical comparisons, which is not ideal for quick comprehension. A more intuitive representation of numbers would enhance immediate understanding.
- Visual Engagement: The current design, while simple and clear, lacks visual elements that capture and retain the viewer’s attention. A more compelling and aesthetically pleasing design could enhance viewer engagement and make the visualization more appealing and likely to be shared.

**Three Things I will change**

- Introduce a visual element such as bars or graphs to represent caffeine content quantitatively, which would make the differences more immediately apparent.
- Standardizing the caffeine amounts to a uniform drink size for each type would make comparisons across columns more straightforward.
- Use a color scheme (rather than blue and black) with higher contrast to improve accessibility. Apply different colors for each brand to simplify brand differentiation at a glance.

## Sketch Out My Solution ##

### Idea 1: Show the caffeine content per cup with a bar graph
#### 1.1	Use a subdued color palette to distinguish between the brands to avoid an overwhelming visual impact caused by the excessive use of bright colors.

<div class='tableauPlaceholder' id='viz1707262630079' style='position: relative'><noscript><a href='#'><img alt='High Street Coffee Caffeine Content by Brand and ProductThe U.S. Food and Drug Administration considers 400 milligrams  a safe amount of caffeine for healthy adults to consume daily. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;Coffee_17071130327220&#47;1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Coffee_17071130327220&#47;1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;Coffee_17071130327220&#47;1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707262630079');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


#### 1.2	Match the brands with their respective colors, for example, blackish green for Starbucks, dark red for Costa, and blue for Caffe Nero

<div class='tableauPlaceholder' id='viz1707262821849' style='position: relative'><noscript><a href='#'><img alt='High Street Coffee Caffeine Content by Brand and ProductThe U.S. Food and Drug Administration considers 400 milligrams  a safe amount of caffeine for healthy adults to consume daily. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Dr&#47;Draft1_2_17072628054770&#47;Draft2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Draft1_2_17072628054770&#47;Draft2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Dr&#47;Draft1_2_17072628054770&#47;Draft2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707262821849');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


### Idea 2: To make the numbers more meaningful to the audience, consider illustrating how many cups of different types of coffee they can consume within a healthy limit

<div class='tableauPlaceholder' id='viz1707263017741' style='position: relative'><noscript><a href='#'><img alt='How Many Cups of Coffee Can You Drink Everyday?The U.S. Food and Drug Administration considers 400 milligrams  a safe amount of caffeine for healthy adults to consume daily. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Dr&#47;Draft2_17072629200530&#47;Cups&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Draft2_17072629200530&#47;Cups' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Dr&#47;Draft2_17072629200530&#47;Cups&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>   

<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707263017741');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>



## Test My Solution

### Interviewer Information

A: 40 years old, sales manager

B: 25 years old, student & coffee lover


### Feedback for Idea 1

| Aspects/Interviewer     |   A   |  B  |
| :---:                   | :---- | :---|
| Information Delivery | The updated visualization offers a clear and direct comparison between caffeine levels across brands, which surpasses the original table format in delivering insights. The bar charts effectively highlight the significant discrepancies in caffeine content among similar coffee types offered by different chains, which is crucial for data-driven decision-making. | The revealed variation in caffeine content between brands is enlightening and prompts reconsideration of habitual choices. |
| Design Feedback   |The subdued color palette is beneficial in avoiding visual overload. Yet, the colors in version 1.1 could benefit from greater distinction to enhance brand differentiation. The strategic use of brand-associated colors, such as Starbucks' iconic green, aids in immediate brand recognition. Nonetheless, it's important to balance this with adequate contrast to ensure readability against the chart's background. | The colors in 1.1 appear too subdued, and a boost, in contrast, would not only cater to aesthetic preferences but also improve legibility. Besides, The uniform scale on the y-axis across different products might dilute the visual impact of the differences and comparisons.|
| Recommendations| Considering the granular serving size of single-shot espresso, a per-milliliter comparison could offer more precise insights. This adjustment would enable a more nuanced understanding when contrasting it with larger beverage sizes. | Considering a reevaluation of the chart's structure, such as switching the axes for the product and chain, could result in an enhanced layout and a new perspective.|


### Feedback for Idea 2

| Aspects/Interviewer     |   A   |  B  |
| :---:                   | :---- | :---|
| Information Delivery | This appears to be a practical guide that translates caffeine content into the actual number of coffee cups one could safely consume, based on the FDA's daily caffeine recommendation. It's a consumer-friendly approach that simplifies complex data into actionable information. |	At first, the high count of cups suggested a negative connotation—more cups equaling a detrimental caffeine level—which contradicted the actual meaning of lower caffeine concentration. A bit of explanation clarified this misconception, but an intuitive design should communicate this immediately without the need for additional context. |
| Design Feedback   | There's a slight confusion due to the mix of cup icons with numerical values. While the icons are visually appealing, they might distract from the actual data, especially if the icon sizes don't scale with the numbers they represent. There's a slight confusion due to the mix of cup icons with numerical values. While the icons are visually appealing, they might distract from the actual data, especially if the icon sizes don't scale with the numbers they represent. | It uses coffee cup icons in a fun way that speaks to my daily coffee rituals. It's a guide to my daily caffeine consumption allowance in terms of actual cups of coffee, which is much more tangible than just milligrams of caffeine.|
| Recommendations| While the visualization is engaging, I'd recommend ensuring the icons' sizes correlate with the numbers for visual consistency. | Maybe use icons that more closely resemble the actual drinks for an immediate visual connection. Including a quick note explaining what "generalized caffeine" means would also be helpful. |


## Final Solution

### High Street Coffe Caffeine Content Per Cup
<div class='tableauPlaceholder' id='viz1707270932835' style='position: relative'><noscript><a href='#'><img alt='High Street Brands Coffee Caffeine Content Per CupThe U.S. Food and Drug Administration considers 400 milligrams  a safe amount of caffeine for healthy adults to consume daily. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Id&#47;Idea1_17072686653680&#47;PerCup&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Idea1_17072686653680&#47;PerCup' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Id&#47;Idea1_17072686653680&#47;PerCup&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1707270932835');                   
 var vizElement = divElement.getElementsByTagName('object')[0];                    
 vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                
 var scriptElement = document.createElement('script');                 
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);             
</script>

**Changes I made:**

1.	I use coffee bean icons as a visual metaphor to indicate caffeine levels, bringing an element of creativity and accessibility to the data. This choice, while unconventional for the formal business environment, suits consumer-oriented platforms perfectly, enhancing engagement and making the content more appealing to a wider audience.
2.	I have restructured the chart to display products on the y-axis and brands/chains on the x-axis. This singular focus per axis simplifies direct comparisons. Additionally, I employ distinct y-axis scales for each coffee type, sharpening the visibility of differences in caffeine content across brands.
3.	I utilize a gradient brown color palette that progressively represents caffeine concentration. The choice of color not only aligns with the coffee theme but also offers an instinctual guide to caffeine levels, facilitating at-a-glance comprehension without detailed analysis.
4.	I include a reference to the FDA's recommended caffeine intake, providing a crucial health context. This insightful touch converts numerical data into practical, health-related guidance, adding real-world applicability to the figures.

   
### How Many Cups of Coffee Should You Drink Every Day?

I attempted to achieve it using Tableau, but it appears that the software does not support this particular function. As a result, I resorted to illustrating my idea manually.

![e540a33b8f8e08a3495e4e43527bc36](https://github.com/Jasmine54/Data-Visualization/assets/120682452/c0aa422a-b05f-4ab2-bfba-47cfee182f65)

**Changes I made:**

1.	Instead of using bar graphs with cups of different heights, I use coffee cup icons to represent the number of cups one can safely consume from each brand and try to immediately convey quantity through familiar imagery.
2.	Each brand is represented by a different color, which aligns with the previous feedback about using brand-associated colors for quick recognition.
3.	The coffee types are now listed vertically with the brand's cup count horizontally, which is a change from the more traditional bar chart layout seen before.

However, the use of icons could become visually cluttered when dealing with large numbers, and the precision of the data might be lost in translation from exact figures to a count of icons.

### How Much Caffeine Do You Consume Every Day?

To enhance the readers' experience and avoid confusion with the "cups" concept, I tried to develop an interactive tool that clearly shows the exact amount of caffeine consumed daily by choosing the type of product and imputing the drink sizes and quantities freely. This interactive feature is designed to deepen readers' engagement by allowing them to connect directly with the data.

*Learn how to create an interactive calculator by watching this tutorial: https://www.youtube.com/watch?v=ybc_8PI0Nus&list=PLX-uPHRG0cLb697Ie-ZGSObRLLNhxzJGK&index=40*

<div class='tableauPlaceholder' id='viz1707269843418' style='position: relative'><noscript><a href='#'><img alt='How Much Caffeine Do You Consume Every Day?Choose your product, input your drink sizes and quantities to calculate your daily caffeine intake. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Id&#47;Idea3_17072695311610&#47;Calculator&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Idea3_17072695311610&#47;Calculator' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Id&#47;Idea3_17072695311610&#47;Calculator&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1707269843418');                   
 var vizElement = divElement.getElementsByTagName('object')[0];                    
 vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);               
</script>


**Design Notes:**

1. I utilize color-coded bars to represent caffeine content, ranging from low to high. The gradient color scale intuitively indicates the amount of caffeine, making it easy for users to assess their intake at a glance.
2. I introduce a benchmark line within the visualization. This line acts as a reference point, informing readers precisely how their current caffeine consumption compares to the FDA's recommended limits. This visual marker is a straightforward method to guide users in understanding and moderating their intake.



### Combined Dashboard 🌟

From this dashboard, you can easily track the caffeine content in a standard serving size of various drinks from different brands. It also allows you to calculate your caffeine intake if your drink sizes differ from the standard or if you consume multiple cups. Hope this tool can help you make informed choices about your caffeine consumption 🥰

<div class='tableauPlaceholder' id='viz1707271050836' style='position: relative'><noscript><a href='#'><img alt='仪表板 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;Dashboard_17072699831310&#47;1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Dashboard_17072699831310&#47;1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;Dashboard_17072699831310&#47;1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div> 

<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1707271050836');                  
 var vizElement = divElement.getElementsByTagName('object')[0];           
 if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='1604px';vizElement.style.maxWidth='1704px';vizElement.style.width='100%';vizElement.style.minHeight='834px';vizElement.style.maxHeight='934px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} 
 else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='1604px';vizElement.style.maxWidth='1704px';vizElement.style.width='100%';vizElement.style.minHeight='834px';vizElement.style.maxHeight='934px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} 
 else { vizElement.style.width='100%';vizElement.style.height='1027px';}     
 var scriptElement = document.createElement('script');                   
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';     
 vizElement.parentNode.insertBefore(scriptElement, vizElement);             
</script>
