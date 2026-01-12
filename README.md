Template code to create a GitPage for salmon resource predictions

Author/developer: Emmerson Wilson (emmerson.r.wilson@gmail.com)

Contents:

- Control Website:
  - index.qmd: Home page with project information
  - Sliders.qmd: Input variables controlled by sliders to create predictions of response variables
  - Rocky_map.qmd: Map with predictions of response variables for reaches sampled for Rocky River watershed, NL
  - _quarto.yml: Rendering source, which pages included in site, universal themes

  - Requirements:
    - Git
    - quarto-live
    - data folder with pngs and shapefiles
    - GitPage source as docs folder from main branch

 
- Tutorial:
  - tutorial.qmd: Quarto presentation that explains how the code works and how you can customize the code to make your own version of the website. To view the presentation open in RStudio and click render

  - Requirements:
    - quarto-drop
    - data folder with 'for webpage' folder containing pngs for tutorial

- data:
  - pngs for Slide.qmd
  - /spatial data: shapefiles for Rocky_map.qmd in 
    - Rocky_lakes.shp: lakes in Exploits watershed
    - Rocky_watershed.shp: watershed from Hydrobasin
    - Rocky _hydrorivers.shp: river vectors from HydroSHEDS clipped to watershed
  -/for webpage: pngs used in tutorial

- docs: created and updated upon render

- _site: created and updated upon render

- _extensions: created and updated by quarto-live upon render

- style.css: empty

- about.qmd: empty
