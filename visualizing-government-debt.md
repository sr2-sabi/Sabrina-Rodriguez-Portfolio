| [Home Page](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/) | [Projects On Tableau](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/dataviz-examples) | [Visualizing Government Debt](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/visualizing-government-debt) | [Critique By Design](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/critique-by-design) | [Drafting Final Project Idea](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/final-project-part-one) | [Refining Final Project](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/final-project-part-two) | [Final Project](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/final-project-part-three) |

### Visualizing Government Debt (1995–2023)

**Context**

**Before Redesign**

<div class='tableauPlaceholder' id='viz1760144444464' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='GDP to Debt Ratio Globally (1995–2023) Source: https://www.oecd.org/en/data/indicators/general-government-debt.html Accessed on September 6, 2025' 
           src='https://public.tableau.com/static/images/GD/GDPtoDebtRatioGlobally1995-2023/GDPtoDebtRatioGlobally1995-2023/1_rss.png' 
           style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
    <param name='embed_code_version' value='3' /> 
    <param name='site_root' value='' />
    <param name='name' value='GDPtoDebtRatioGlobally1995-2023/GDPtoDebtRatioGlobally1995-2023' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/GD/GDPtoDebtRatioGlobally1995-2023/GDPtoDebtRatioGlobally1995-2023/1.png' />
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
  var divElement = document.getElementById('viz1760144444464');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

**My Redesign**

<div class='tableauPlaceholder' id='viz1760144559211' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Top 3 Countries by Debt-to-GDP Ratio Compared to Global Trends (1995–2019) Source: https://www.oecd.org/en/data/indicators/general-government-debt.html Accessed on September 6, 2025' 
           src='https://public.tableau.com/static/images/To/Top3CountriesbyDebt-to-GDPRatioComparedtoGlobalTrends19952019/Top3CountriesbyDebt-to-GDPRatioComparedtoGlobalTrends19952019/1_rss.png' 
           style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
    <param name='embed_code_version' value='3' /> 
    <param name='site_root' value='' />
    <param name='name' value='Top3CountriesbyDebt-to-GDPRatioComparedtoGlobalTrends19952019/Top3CountriesbyDebt-to-GDPRatioComparedtoGlobalTrends19952019' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/To/Top3CountriesbyDebt-to-GDPRatioComparedtoGlobalTrends19952019/Top3CountriesbyDebt-to-GDPRatioComparedtoGlobalTrends19952019/1.png' />
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
  var divElement = document.getElementById('viz1760144559211');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Project Goal
This redesign focuses on showing which countries carry the heaviest debt while keeping the global picture visible. The goal was to highlight key players while still allowing all other countries to provide context.

## Design Approach
The first version used a heatmap to show change across countries and years. The format worked well for identifying short-term shocks such as the 2008–09 financial crisis and the 2020 pandemic. However, it made it harder to follow persistence and trajectory.

I changed to a multi-line time series. Every country remains visible in light gray, while the three with the highest average debt-to-GDP ratios from 1995 to 2023 are colored. This static selection avoids the flipping that happened when the top-three countries changed each year. Each highlighted line runs from start to finish with end labels and a dashed global average as a benchmark.

## Design Decisions and Trade-offs
- **Color hierarchy:** muted gray for context and bold color for focus. This helps viewers distinguish the outliers instantly.  
- **Benchmarking:** The dashed line provides a fixed comparison that shows how extreme the top countries are compared to the global mean.  
- **Simplicity:** removing animation and dynamic ranking made the chart easier to read and understand.  
- **Trade-off:** single-year spikes are less visible than in the heatmap, but the final view better highlights long-term debt patterns.

## Insights
The final visualization gives a clear answer to the question: *Who holds the most debt, and how consistent has that been over time?*  
The top three countries stay above the global average across decades, suggesting that their debt levels are part of a structural condition rather than a temporary shock. The gray backdrop still shows variation among other nations and reveals convergence trends over time.

## Reflection
This project showed how design choices shape interpretation. The heatmap told a story about volatility. The line chart tells a story about endurance and long-term imbalance. In policy and economic visualization, color, ranking methods, and reference lines can change how viewers understand stability and risk.
