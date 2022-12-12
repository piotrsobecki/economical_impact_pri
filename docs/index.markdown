---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Impact analysis of public research institutes on Polish economy. 
---
## Visualization of the patenting activity and its impact on the economy.
To estimate the impact, we have used concordance tables to map the IPC classification of over 30000 patent admissions to NACE categories. This allows to highlight the industries that are being impacted the most by the research conducted at these institutes.


By understanding the industries that are being impacted by this research, researchers can see the real-world implications of their work and policymakers can better understand the economic benefits of public investment in research. This information can help to inform decision-making and promote more effective research and development efforts. Additionally, our data and visualizations provide a detailed profile of each institution, allowing for a better understanding of their patenting activity and its impact on the economy. 

You can  learn more about the methodology behind our analysis on [the 'About' subpage]({{ site.baseurl }}{% link about.markdown %}).


## Map of influence

The map of influence shows the impact that each research institute has on various NACE sectors. The size of the bubbles on the map corresponds to the relative level of activity of the institute in each sector. This allows you to see at a glance which institutes are having the greatest impact on specific industries.  

{% include inst_influence_map.html %}




## Projection of patenting activity

The chart presents a two-dimensional projection of the data that results from applying Principal Component Analysis (PCA) to vectorized profiles of the institutes. We have grouped the institutes into 15 clusters based on their cosine similarity. This allows you to see the relationships between different institutes and how they compare to one another. The chart is a useful tool for gaining a high-level understanding of the patenting activity of the institutes and its impact on the economy.

{% include institute_nace_impact_clusters.html %}