---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home

---

This site presents visualization of the PRI patenting activity and its estimated impact on the Polish economy.

By understanding the industries that are being impacted by this research, researchers can see the real-world implications of their work and policymakers can better understand the economic benefits of public investment in research. This information can help to inform decision-making and promote more effective research and development efforts. Additionally, our data and visualizations provide a detailed profile of each institution, allowing for a better understanding of their patenting activity and its impact on the economy. 

## Analysed data

To estimate the impact, we have used [probabilistic concordance tables]({{ site.baseurl }}{% link concordance.markdown %}) to map the IPC classification of patent admissions to NACE categories. 
This allows to highlight the industries that are being impacted the most by the research conducted at these institutes.

Four our analyses, we have limited the patent submisions to that of public universities and scientific institutions in 2010-2019. 
We have filtered admissions with no decision assigned, and those that were not granted the patenting right. 

The following table presents statistics of patent submissions included in analyses and visualization.

{% include patents_inst_stats.html %}

You can learn more about the data and the methodology behind our analysis on [the 'Methodology' subpage]({{ site.baseurl }}{% link methodology.markdown %}).

## Map of influence

The map of influence shows the impact that each research institute has on various NACE sectors. The size of the bubbles on the map corresponds to the relative level of activity of the institute in each sector. This allows you to see at a glance which institutes are having the greatest impact on specific industries.  

{% include inst_influence_map.html %}


## Projection of patenting activity

The chart presents a two-dimensional projection of the data that results from applying Principal Component Analysis (PCA) to vectorized profiles of the institutes. We have automatically grouped the institutes into clusters based on their cosine similarity. This allows you to see the relationships between different institutes and how they compare to one another. The chart is a useful tool for gaining a high-level understanding of the patenting activity of the institutes and its impact on the economy.

{% include institute_nace_impact_clusters.html %}

Most active institutions in each identified cluster. 

{% include cluster_leaders.html %}


## Sector leaders

We present a list of identified sector leaders on [the 'Sector leaders' subpage]({{ site.baseurl }}{% link sector_leaders.markdown %}). This subpage presents the results of our analysis of the industries that have been most impacted by the patenting activity of PRIs. Using concordance tables and the IPC classification, we have identified the top performers in each sector and highlighted their contribution to the economy.
