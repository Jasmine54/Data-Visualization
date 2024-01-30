# Assignment 1: General Government Debt Analysis

## Bar Chart
<iframe src="https://data.oecd.org/chart/7krH" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7krH" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2022</a></iframe>

## Heat Map
<div class='tableauPlaceholder' id='viz1706561844009' style='position: relative'><noscript><a href='#'><img alt='General Government Debt-to-GDP Ratio In 1995-2022(SOURCE: OCED DATA) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebt-to-GDPRatio&#47;GeneralGovernmentDebt&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebt-to-GDPRatio&#47;GeneralGovernmentDebt' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebt-to-GDPRatio&#47;GeneralGovernmentDebt&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /></object></div>

<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1706561844009');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    
 vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>  


## Line Chart

* Why I chose a subset of the data: In this analysis, I've narrowed the scope to only include the countries with the fifth-highest average debt-to-GDP ratios globally to avoid an overly cluttered and complex visualization. Concentrating on these particular cases allows for a clear, concise depiction of how significant debt levels can shift over time within varied economic climates and under different fiscal policies. This approach not only provides a focused narrative on the challenges and strategies of heavily indebted countries but also ensures the graph remains readable and informative, avoiding the visual noise that would result from plotting all countries simultaneously.
* Why I chose a line chart: The line chart is particularly adept at offering an intuitive and immediate visual representation of the data. It translates complex numerical information into a form that can be quickly grasped by readers, showing not just static figures but also the movement and changes over time. 
* Other design elements: Regarding the color scheme, distinct colors are assigned to each country to create clear visual distinctions between their respective data lines. I have also placed labels at the end of each line, which helps in instantly identifying the corresponding country without necessitating excessive eye movement across the chart. 

<div class='tableauPlaceholder' id='viz1706575220024' style='position: relative'><noscript><a href='#'><img alt='How Government Debt-To-GDP Ratio Changed Over Time?Focusing on the top 5 countries with the highest average Debt-to-GDP ratio from 1995-2022 to analyze how this ratio has changed over time.(SOURCE: OCED DATA) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebt-to-GDPRatio&#47;LineGraph&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebt-to-GDPRatio&#47;LineGraph' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebt-to-GDPRatio&#47;LineGraph&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div> 

<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1706575220024');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    
 vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>



**From the chart, we can discern several key points:**
1. There are periods of convergence and divergence among the countries' debt trajectories, indicating varying fiscal responses to economic conditions, such as recessions or periods of growth.
2. Some countries exhibit sharp increases in debt-to-GDP ratios at certain intervals (Iceland in 2008, Germany in 2012) likely corresponding to economic downturns or fiscal stimulus measures.
3. Japan has held the distinction of having the highest debt-to-GDP ratio since 1999, which signals its enduring financial stress and the significant pressure on its fiscal health. 
4. All 5 countries' ratios experienced a marked increase in 2020, probably due to the global economic impact of the COVID-19 pandemic, indicating widespread increased government borrowing during this period.


## Summary
- The **bar chart** is a straightforward method to compare numerical data across different categories. In this case, it represents a single point in time (2022) and a specific value (debt-to-GDP ratio) for each country listed on the x-axis. The clear advantage of a bar chart is its simplicity and ease of reading, making it ideal for comparing **discrete** quantities across entities. However, it cannot effectively compare a large number of different values between different entities or track changing dynamics over time, as compared to a line chart or heat map.
- The **heat map** can provide a detailed view of data **over time**. The color intensity reflects the **magnitude of the data**, with darker shades typically indicating higher values. In this context, I used orange to signal a warning regarding a country's sustainability of government finance, while blue represents safety. This format allows for the tracking and comparing of changes over time within each country and across countries. Heat maps are particularly useful when there are many data points to consider, as they can highlight trends and outliers effectively. However, the display of a large amount of information can sometimes make it challenging for readers to quickly understand and grasp the main points of the map.
- The **line chart** excels at showing trends **over time**. Each line represents a different country, with the y-axis showing the debt-to-GDP ratio and the x-axis representing time. Line charts are especially good for visualizing how data changes over a period, making it easier to spot increases, decreases, and volatility in the data, unlike heat maps, where it can be difficult to quickly grasp the main points due to similar colors or a large amount of numerical data.
