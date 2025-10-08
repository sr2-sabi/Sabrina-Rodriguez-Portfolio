| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# The final data story
> Shorthand Link: https://carnegiemellon.shorthandstories.com/the-next-petrochemical-footprint/index.html 

**Reflection on changes since Part II**

Since part two, I narrowed the focus. I began with Cancer Alley and reproductive disorders. After looking for data, I could not find tract-level, exportable datasets that linked reproductive outcomes to facility proximity in a clean way. I pivoted to forecasting petrochemical buildout and its impacts on nearby neighborhoods, using Cancer Alley as the case example and calibration point. This gave me a clearer story about how clusters form, who lives nearby, what current modeled risk looks like, and what likely happens if siting continues.

My data stack shifted. I moved from small-area health datasets to public, repeatable layers including AirToxScreen and RSEI for modeled cancer risk, EIA and TRI for facility locations, and census tracts and parishes for boundaries. I rebuilt the visuals in ArcGIS and Tableau. I made a baseline tract map shaded by risk percentile with refinery and petrochemical points. I added a corridor versus the rest of Louisiana comparison using average percentiles. I created a source mix view to show industrial versus traffic and ports. I built a national buildout panel that converts projected emissions into coal plant and car equivalents. I also added a product mix forecast comparing 2017 actual with 2027 projected volumes to show why capacity growth locks in emissions. Feedback pushed me to be more policy facing and forward looking with short callouts, uncertainty notes, and a concrete action section.


## The audience

My primary audience is policymakers who control siting, zoning, and permits. A secondary audience is community organizations that need clear visuals and language for advocacy. Interviews told me to keep it plain, visual first, and always show what to do next. I adjusted with short captions that state the takeaway, side by side comparisons, and a closing panel that maps findings to actions such as buffers, cumulative impact reviews, monitoring, and equity checks. I added equity context so readers see who bears added risk, not just where plants are.


## Final design decisions

I used percentiles for comparability so readers can see how a tract ranks against national peers. I combined choropleths with facility points so proximity and pattern are visible in a single frame, and outlined the river parish corridor so clustering is obvious. I explained the growth engine with a 2017 to 2027 product chart. I converted 153.8 MMT per year into familiar equivalents to set the scale. I wrote mobile-friendly labels, used clear color ramps, and placed a short note on limitations under each figure.


## AI acknowledgements

I used AI to troubleshoot Tableau joins (GEOID string padding, extract tips); and outline policy and community action sections in plain language.

# Final thoughts

What worked was leaning into the forecast and case analysis, which made the story clearer and more actionable. What I’d add with more time is population-weighted results, a small scenario map for proposed sites, and a tighter uncertainty panel. I’m most excited that the visuals now bridge from Cancer Alley’s lived reality to today’s siting decisions so readers see not just where we are, but how to change course before more corridors look the same.


