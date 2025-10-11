<style>
  body { background-color: #c48b9f; } /* soft rose background */
  .markdown-body, .page, .main-content {
    background-color: #ffffff;        /* keep content white */
  }
</style>

|[Home Page](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/) | [Projects On Tableau](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/dataviz-examples) | [Visualizing Government Debt](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/visualizing-government-debt) | [Critique By Design](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/critique-by-design) | [Drafting Final Project Idea](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/final-project-part-one) | [Refining Final Project](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/final-project-part-two) | [Final Project](https://sr2-sabi.github.io/Sabrina-Rodriguez-Portfolio/final-project-part-three) |

### **Interactive Story**

<script src="https://carnegiemellon.shorthandstories.com/the-next-petrochemical-footprint/embed.js"></script>


**Reflection on Changes Since Part II**

Since part two, I narrowed the focus. I began with Cancer Alley and reproductive disorders. After looking for data, I could not find tract-level, exportable datasets that linked reproductive outcomes to facility proximity in a clean way. I pivoted to forecasting petrochemical buildout and its impacts on nearby neighborhoods, using Cancer Alley as the case example and calibration point. This gave me a clearer story about how clusters form, who lives nearby, what current modeled risk looks like, and what likely happens if siting continues.

My data stack shifted. I moved from small-area health datasets to public, repeatable layers including AirToxScreen and RSEI for modeled cancer risk, EIA and TRI for facility locations, and census tracts and parishes for boundaries. I rebuilt the visuals in ArcGIS and Tableau. I made a baseline tract map shaded by risk percentile with refinery and petrochemical points. I added a corridor versus the rest of Louisiana comparison using average percentiles. I created a source mix view to show industrial versus traffic and ports. I built a national buildout panel that converts projected emissions into coal plant and car equivalents. I also added a product mix forecast comparing 2017 actual with 2027 projected volumes to show why capacity growth locks in emissions. Feedback pushed me to be more policy facing and forward looking with short callouts, uncertainty notes, and a concrete action section.


## The Audience

My primary audience is policymakers who control siting, zoning, and permits. A secondary audience is community organizations that need clear visuals and language for advocacy. Interviews told me to keep it plain, visual first, and always show what to do next. I adjusted with short captions that state the takeaway, side by side comparisons, and a closing panel that maps findings to actions such as buffers, cumulative impact reviews, monitoring, and equity checks. I added equity context so readers see who bears added risk, not just where plants are.


## Final Design Decisions

I used percentiles for comparability so readers can see how a tract ranks against national peers. I combined choropleths with facility points so proximity and pattern are visible in a single frame, and outlined the river parish corridor so clustering is obvious. I explained the growth engine with a 2017 to 2027 product chart. I converted 153.8 MMT per year into familiar equivalents to set the scale. I wrote mobile-friendly labels, used clear color ramps, and placed a short note on limitations under each figure.


## AI Acknowledgements

I used AI to troubleshoot Tableau joins (GEOID string padding, extract tips); and outline policy and community action sections in plain language.

# Final Thoughts

What worked was leaning into the forecast and case analysis, which made the story clearer and more actionable. What I’d add with more time is population-weighted results, a small scenario map for proposed sites, and a tighter uncertainty panel. I’m most excited that the visuals now bridge from Cancer Alley’s lived reality to today’s siting decisions so readers see not just where we are, but how to change course before more corridors look the same.


