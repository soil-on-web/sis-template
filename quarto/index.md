---
title: "Soil Information System Template"
format: html
page-layout: full
search: true
image: ./img/pit-in-maize.jpg
image-alt: "some soil scientists in a maize field analysing a pit (chatgpt)"
repo-actions: [edit, issue]

about:
  template: solana
  image-width: 32em
  id: hero-heading

---

::: {#hero-heading}
This template for a soil information system can be used by various organisations active in the domain of soil. It brings together soil data from across projects and provides access to consistent, standardized soil data and information to support evidence-based decisions on sustainable land management. The soil data are systematically generated, collated, curated, standardized, catalogued and maintained. This template website is a place to find reliable, readily useable and actionable soil data and information.
:::

&nbsp;

---


## Interactive soil maps

<div id="map" style="width:100%;height:350px" class="rounded shadow"><div id="popup" class="ol-popup" style="display:none;"></div></div>

## Our Commitment

We are committed to:

- Providing **open, standardized, high-quality** soil information  
- Supporting **evidence-based decision-making**  
- Advancing **soil science research** 
- Enabling sustainable management of land and soil resources  

## Contact Us

If you have questions or need support, feel free to contact our team at: 

```
**Example**
phone: xxx-xx-xxx-xxx
email: info@example.com
```

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/ol@10.7.0/ol.css">
<link rel="stylesheet" href="https://unpkg.com/ol-layerswitcher@4.1.0/dist/ol-layerswitcher.css" />
<script src="https://cdn.jsdelivr.net/npm/ol@7.4.0/dist/ol.js"></script>
<script src="https://unpkg.com/geotiff@2.1.3/dist-browser/geotiff.js"></script>
<script src="https://unpkg.com/ol-layerswitcher@4.1.0/dist/ol-layerswitcher.js"></script>
<script src="map.js"></script>
<style>
.ol-popup {
  position: absolute;
  z-index: 999;
  background: white;
  padding: 4px 8px;
  border-radius: 4px;
  border: 1px solid #ccc;
  font-family: Arial,sans-serif;
  font-size: 12px;
  pointer-events: none;
  white-space: nowrap;
}
</style>