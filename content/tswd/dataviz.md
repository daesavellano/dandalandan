---
title: "Data Visualization Examples"
date: 2025-10-21
draft: false
type: "page"
tags: "Template"
---

# Data visualization examples
This page contains example data visualizations from the Telling Stories With Data course, along with appropriate citations, references, and data sources used.

## Learning Tableau and Datawrapper

### Trust in Media

This Tableau dashboard was created as a reintroduction to the tool. It explores American trust in major news organizations across two different years.
- The **top graph** visualizes which news organizations Americans trusted most in **2018**, based on data from [Simmons Research](https://infogram.com/276787a2-ff55-457f-9a29-c0a8267b8b29).
- The **bottom graph** shows the **2024** net trust rating (the percentage point difference between "trust" and "distrust") for various outlets, using data from and based on an existing visualization in [YouGov](https://today.yougov.com/politics/articles/49552-trust-in-media-2024-which-news-outlets-americans-trust).

<div class='tableauPlaceholder' id='viz1761883156363' style='position: relative; max-width: 800px; margin-left: auto; margin-right: auto;'>

  <noscript><a href='#'><img alt='Trust in News (2018 and 2024) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Tr&#47;TrustInMedia_17618797080800&#47;TrustinNews2018and2024&#47;1_rss.png' style='border: none' /></a></noscript>
  <object class='tableauViz'  style='display:none;'><param name='host_url' value='httpsClick:&#47;&#47;public.tableau.com&#47;' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TrustInMedia_17618797080800&#47;TrustinNews2018and2024' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Tr&#47;TrustInMedia_17618797080800&#47;TrustinNews2018and2024&#47;1.png' /> <param name='animate_transition' value='yes' /><param name'display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object>
</div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1761883156363');
    var vizElement = divElement.getElementsByTagName('object')[0];
    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}
     var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

### Popularity of Datawrapper Visualization Types

The following graph was made as an introduction to [Datawrapper](https://datawrapper.dwcdn.net/Tb9rk/2/).

For this in-class exercise, we were given the data with no instructions other than to explore the website. With the limited time, I decided to implement the following design choices.
- I used a **bump chart with curved lines**, as it's a highly effective way to visualize how rankings change over time.
- I framed the data as a **"battle" between tables and area/line charts**, inspired by Datawrapper's common use in journalism (and need for catchy titles!). The color scheme also highlights this narrative: the current "winner" is green, the previous winner is orange, and all other chart types are grey.
- I chose a **horizontal format**, as it aligns with how Western audiences read time-based data (left to right), reinforcing the clear progression.

<iframe title="How The Tables Have Turned" aria-label="Line chart" id="datawrapper-chart-Tb9rk" src="https://datawrapper.dwcdn.net/Tb9rk/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="437" data-external="1"></iframe><script type="text/javascript">window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r,i=0;r=e[i];i++)if(r.contentWindow===a.source){var d=a.data["datawrapper-height"][t]+"px";r.style.height=d}}});</script>