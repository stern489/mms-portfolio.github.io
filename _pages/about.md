---
permalink: /projects/
title: "Work Samples"
layout: splash
header:
    overlay_image: /assets/images/GIS-Data-Header.png
    overlay_filter: 0.3
    caption: "Image Source: Tri-County Regional Planning Commission"
---
<p style="max-width: 800px; margin: 2rem auto; font-size: 1rem; line-height: 1.5; text-align: center;">
  The projects showcased below demonstrate: 
  1. How I have successfully leveraged my undergraduate background in geoscience within my GIS work.
  2. My experience distributing automated GIS workflows via repositories such as GitHub.
  3. The sheer variety of topics I have covered in my professional development.
  (2 and 3 will be 'truer' as I add more projects in the future)
</p>
<style>
a:hover div.overlay {
  opacity: 1 !important;
}
</style>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 2rem; padding: 3rem 2rem;">

  <div style="flex: 1 1 300px; max-width: 350px; text-align: center;">
    <h3 style="margin-bottom: 1rem;">Web Map - Impaired Streams</h3>
    <a href="https://umn.maps.arcgis.com/apps/mapviewer/index.html?webmap=39344d1e8dbc4471a81ceec5dd4a8415" style="display: block; position: relative; border-radius: 10px; overflow: hidden; text-decoration: none; color: inherit;">
      <img src="{{ '/assets/images/project_one.png' | relative_url }}" 
           alt="Flood Risk Mapping Project"
           style="width: 100%; height: 250px; object-fit: cover; border-radius: 10px;">
      <div class="overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; 
                  background: rgba(0, 0, 0, 0.6); color: white; opacity: 0;
                  display: flex; align-items: center; justify-content: center;
                  transition: opacity 0.3s ease; padding: 1rem; text-align: center;
                  z-index: 2; font-size: 14px;">
        <p>Stylized ArcGIS Online Web Map depicting imparied streams in Minnesota. This map was created for GIS 5574 (WebGIS). [This was not a high-effort project, the standards of displayed projects will be much higher as my portfolio progresses].</p>
      </div>
    </a>

  </div>

  <div style="flex: 1 1 300px; max-width: 350px; text-align: center;">
    <h3 style="margin-bottom: 1rem;">Driftless Area Geology - StoryMap</h3>
    <a href="https://storymaps.arcgis.com/stories/49b83064b4314ecabd5f61ebd6cbb810" style="display: block; position: relative; border-radius: 10px; overflow: hidden; text-decoration: none; color: inherit;">
      <img src="{{ '/assets/images/gis-integration.jpg' | relative_url }}" 
           alt="Overview to geology and geomorphology of the driftless area"
           style="width: 100%; height: 250px; object-fit: cover; border-radius: 10px;">
      <div class="overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; 
                  background: rgba(0, 0, 0, 0.6); color: white; opacity: 0;
                  display: flex; align-items: center; justify-content: center;
                  transition: opacity 0.3s ease; padding: 1rem; text-align: center;
                  z-index: 2;">
        <p>StoryMap with interactive web maps which discusses the history and stratigraphic column of the Driftless Area geology in Houston County, Minnesota. This StoryMap was created as my final project for GIS 5574 (WebGIS)</p>
      </div>
    </a>
  </div>

  <div style="flex: 1 1 300px; max-width: 350px; text-align: center;">
    <h3 style="margin-bottom: 1rem;">Example Project Three</h3>
    <a href="#" style="display: block; position: relative; border-radius: 10px; overflow: hidden; text-decoration: none; color: inherit;">
      <img src="{{ '/assets/images/gis-integration.jpg' | relative_url }}" 
           alt="Example Project"
           style="width: 100%; height: 250px; object-fit: cover; border-radius: 10px;">
      <div class="overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; 
                  background: rgba(0, 0, 0, 0.6); color: white; opacity: 0;
                  display: flex; align-items: center; justify-content: center;
                  transition: opacity 0.3s ease; padding: 1rem; text-align: center;
                  z-index: 2;">
        <p>Description of Project Three</p>
      </div>
    </a>
  </div>

</div>
