# Frontline-GFW Repository

This repository supports data sharing and collaboration across Frontline project work packages, with a specific focus on using **Global Fishing Watch (GFW)** data for analysis workflows.

It provides practical examples and reusable Python/R code for:

* Accessing and fetching GFW datasets using APIs
* Pre-processing and cleaning fishing activity/cargo's data
* Exporting analysis-ready products for direct use in Frontline project analyses

The aim is to streamline data handling, ensure reproducibility, and enable consistent use of GFW data across teams.

---

## Repository Structure

```
├── examples/
│   ├── Jupyter notebooks
│   ├── RMarkdown files
│   └── HTML files
│   
│   Examples demonstrating how to fetch, process, and prepare GFW data
│   for analysis using Python and R.
│
├── src/
│   Source code and reusable modules developed for this repository
│   (e.g. data access, processing utilities, helper functions)
```

projectname-example-datasets/
├── README.md
├── examples/
│   ├── jupyter notebooks
│   ├── RMarkdown files
│   └── HTML files
├── windfarms/
│   ├── windfarms.geojson
│   ├── offshore_sites.shp
├── ports/
│   └── ports.geojson
├── boundaries/
│   └── eez.geojson
│   └── Celtic Sea.geojson
└── LICENSE

