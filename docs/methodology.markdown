---
layout: page
title: Methodology
permalink: /methodology/
full-width: true
classes: wide
order: 1
---


To estimate the economic impact of public research institutes, we have used [probabilistic concordance tables]({{ site.baseurl }}{% link concordance.markdown %}) to map the IPC classification of patent admissions to NACE categories.


The data has been obtained from the public APIs of the:
- [Integrated System of Information on Science and Higher Education (POLON)](https://polon.nauka.gov.pl/siec-polon)  
- ['Urząd Patentowy Reczpospolitej Polskiej' webiste](https://uprp.gov.pl/).

The collected data mapped with NACE mappings allows to see which industries are being impacted by the research conducted at these institutes.

Our analysis is based on this mapping, which provides a detailed and accurate picture of the economic impact of the patenting activity of these institutes.

{% include patents_kind_years_groupped.html %}


The following table presents distribution of all patent submissions in the collected database


{% include patents_inst_stats_all.html %}


While our analysis includes all patenting activity, not all of the patents that we have analyzed are currently active. 
This means that our results provide a comprehensive view of the impact of these institutes on the economy, even if some of the patents have expired or are no longer in use.

For our analyses, we have limited the patent submisions to that of public universities and scientific institutions in 2010-2019. 
We have filtered admissions with no decision assigned, and those that were not granted the patenting right. 
However, we have decided to include the patents that have expired (ie. due to lack of payment) as those could be potentially essential in assessing the economical impact.


{% include patents_decisions.html %}


Our data and visualizations allow us to identify the industries that are being impacted the most by the research conducted at public research institutes. 


{% include top_sectors_activity.html %}


Overall no distinct trend in distribution of patents impact on NACE sectors has been observed over the years.

{% include prct_impact_years.html %}