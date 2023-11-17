---
layout: archive
title: <center> John A.F. Wendt IV </center>
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

### Education

* PhD in Ecology and Environmental Sciences  
  Montana State University
  * Dissertation topic: _Reconstructing Large Herbivore Abundance and Environmental Interactions in Postglacial North America_
  * Advisor: Dr. David B. McWethy
* B.S. in Rangeland Ecology  
  Colorado State University, 2016
  * Restoration Ecology concentration, Conservation Biology minor 
  * _Magna cum laude_, University Honors Scholar, 3.98 GPA

### Publications

<ul>
  {% assign total_publicatons = site.publications.size %}
  {% if total_publications == 0 %}
    <li>No publications found</li>
  {% else %}
    <li>Total publications: {{ total_publications }}</li>
    {% for index in (total_publications - 1) | down_to 0 %}
      {% assign post = site.publications[index] %}
      <li>
        <strong>Title:</strong> {{ post.title }}<br>
        <strong>Date:</strong> {{ post.date }}<br>
        <strong>Content:</strong> {{ post.content | truncate: 100 }}
      </li>
    {% endfor %}
  {% endif %}

</ul>

### Research Grants

* Yellowstone Doctoral Scholars Fellowship, MSU Institute on Ecosystems, 2023
* Graduate Research Innovation Award, Joint Fire Science Program, 2019, $24,000
* Theodore Roosevelt Memorial Grant, American Museum of Natural History, 2019
* NSF REU Grant Supplement (PI: Dr. Mark Simmons), 2013

### Honors, Awards, and Scholarships

* MSU PhD Dissertation Completion Award, 2023
* 1st Place MAGIP GIS Poster Competition, 2022
* Graduate School PhD Enhancement Award, 2021-2022
* Graduate School Professional Advancement Grant, 2020
* Jim Edie Geography Scholarship, 2019
* Honorable Mention, NSF GRFP, 2019
* Phi Kappa Phi, Inducted 2019
* D.R. and Virginia D. Pulliam Scholarship, 2016
* Benjamin A. Gilman International Scholarship, 2015
* CSU OIP Undergraduate Education Abroad Scholarship, 2015
* FGS Colorado Universities Scholarship, 2015
* SIT Affiliate Scholarship, 2015
* William (Mike) Fenner `54 Scholarship, 2014
* Great Lakes National Scholarship, 2013-2015
* College Access Challenge Grant Scholarship, 2013
* Colonel Marvin & Joye Parker Scholarship, 2013
* Warner CNR General Scholarship, 2013
* University Honors Program Scholarship, 2011-2015
* Warner CNR Dean's Honor Roll, 2011-2016
* CFA Leadership Scholarship, 2011

### Skills

* Programming languages: R, python, SQL
* Statistics and machine learning: generalized additive models, random forests, ordination, classification and regression trees
* Select R packages: ggplot2, dplyr, knitr, rioja, leaflet, shiny
* GIS software: ArcGIS Pro, QGIS, R packages (raster, rgdal, sf, sp, rgeos)
* Climate analysis: netCDF Operators (NCO), Climate Data Operators (CDO)
* Ecological distribution modeling: MaxEnt
* Version control: Git, GitHub

### Talks

<ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

### Teaching

<ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

### Research and professional experience

* Research Asisstant, Fall 2018 - present  
  Paleoecology Lab, Montana State University
  
  - Supporting lab and field research activities including collection of sediment cores and lab analysis of charcoal and pollen.

* Teaching Asisstant, Spring 2019 - Fall 2022  
  Departement of Earth Sciences and Department of Land Resources and Environmental Sciences, Montana State University
  
  - Led instruction of two lab sections for undergraduate students in GPHY 284 - Intro. to GIS Science and Cartography and GPHY 384 - Adv. GIS and Spatial Analysis.

* Instructor, Spring 2022
  
  - Led lectures and class sessions for GPHY 411 - Biogeography

* Visiting Researcher, Fall 2021  
  Department of Environmental Sciences, Informatics and Statistics, Ca' Foscari University of Venice
  
  - Analyzed molecular biomarkers from lake sediments to reconstruct past herbivore activity.

* GIS Specialist, 2018  
  Center for Environmental Management of Military Lands, Colorado State University
  
  * Performed quality control and validation for Air Force environmental GIS databases.

* Rangeland Technician, 2016 - 2017  
  Synergy Resource Solutions, Inc., Belgrade, Montana
  
  * Conducted rangeland vegetation and soil surveys following National Resources Inventory (NRI) and Assessment, Inventory, and Monitoring (AIM) protocol at over 200 sites throughout Wyoming, Montana, Utah, and Nevada.

* Undergraduate Research Assistant, Spring 2016  
  Rangeland Social-Ecological Systems Lab, Colorado State University 
  
  * Assisted Dr. Hailey Wilmer in a study on the collaborative adaptive management process in a rangeland context. Synthesized meeting cliff notes, agendas, and transcripts to elucidate and track stakeholder decisions and social dynamics over the course of the Adaptive Grazing Management Experiment. 

* Ranch and Range Management Intern, Fall 2015  
  Rock Hills Ranch, Lowry, South Dakota
  
  * Integrated landowner knowledge, ecological conditions, and geospatial data to develop a ranch operation manual. Developed a digital map of pasture resources and other ranch assets. Implemented rangeland improvement projects including fencing and water development. Performed rangeland health assessments and monitored forage utilization.

* Field Technician, Summer 2015  
  Rangeland-Social Systems Lab, Colorado State University
  
  * Supported graduate research on greater sage grouse habitat, aspen decline, and soil nitrogen-plant community feedbacks. Identified plant species and collected ecological data on species richness, foliar cover, production, utilization, and basal cover at aspen and sagebrush field sites throughout northwestern Colorado.

* Study Abroad, Spring 2015  
  SIT Mongolia: Geopolitics and the Environment, Ulaanbaatar, Mongolia
  
  * Collaborated with a Mongolian NGO to implement a community-based conservation plan in a rural herding and logging community. Assisted with organization of the Building Resilience of Mongolia's Rangelands research conference. Studied the forces governing and guiding national development and natural resource management.

* Undergraduate Research Assistant, 2014 - 2015  
  Rangeland Social-Ecological Systems Lab, Colorado State University
  
  * Processed soil samples for nitrogen analysis. Entered social and ecological data with Microsoft Access.

* Herbarium Assistant, 2013 - 2015  
  CSU Herbarium, Colorado State University
  
  * Developed a novel image-based plant identification web-portal and a plant characteristic database for all Colorado plant species. Wrote technical species descriptions and created distribution maps for Dr. Jennifer Ackerfield's Flora of Colorado.

* Field Botanist, Summer 2013  
  USGS & Knapp Lab, Colorado State University
  
  * Supported research on the impact of increased nitrogen deposition on mixed grass prairie plant communities in Wind Cave and Badlands National Parks with Dr. Amy Symstad. Measured plant community attributes via point-intercept, nested plot, and biomass harvest methods.

* Undergraduate Research Assistant, 2012 - 2013  
  Restoration Ecology Lab, Colorado State University
  
  * Facilitated studies on grasshopper herbivory, revegetation plantings, seed banks, and post-disturbance dynamics.

* Biological Science Aide, Summer 2012  
  Rocky Mountain National Park, Estes Park, Colorado
  
  * Assisted postgraduate research on cheatgrass response to manipulated soil carbon and nitrogen levels. Established, maintained, and monitored vegetation restoration sites.

* Undergraduate Lab Assistant, 2011-2012  
  National Wildlife Research Center, Fort Collins, Colorado
  
  * Assisted the Reproductive Control Methods Project with the development and production of GonaCon, a fish and wildlife immunocontraceptive Performed troubleshooting and operation of a macro program in MS Excel to evaluate ELISA data.

### Service and outreach

* Leadership & Speaker Series Committee, MSU Grasslands Resilience Working Group, 2018 - present
* Virtual Student Federal Service (VSFS) eIntern, Federal Geographic Data Committee, 2018 - 2019
* Guest Presenter, Nueva School Annual Experiential Learning Trip, April 2019
* Volunteer Instructor, Chief Joseph Middle School Earth Science Day, December 2018
* Secretary, Young Professionals Conclave, Society for Range Management, 2017
* Alumni Mentor, School for International Training (SIT), 2015 - 2016

### Select coursework

#### Graduate

* Analysis of Ecological Communities (MSU BIOE 540)
* Methods of Data Analysis 1 & 2 (MSU STAT 511/512)
* Geospatial Approaches to Problem Solving (MSU GPHY 591)
* Quaternary Environments of the Western US (MSU ERTH 584)
* Topics in Paleoecology (MSU ERTH 583)
* Istope Biogeochemistry (MSU LRES 558)
* Ecosystem Biogeochemistry (MSU LRES 568)
* Biogeochemistry Analysis Synthesis (MSRU LRES 567)

#### Undergraduate

* Quantitative Reasoning for Ecosystem Science (CSU ESS 330)
* Geospatial Applications in Natural Resources (CSU NR 319)
* Ecological Restoration (CSU RS 478)
* Plant Ecology (CSU BZ 450)
* Forest Ecology (CSU F 311)
* Rangeland and Forest Ecogeography (CSU RS 310)
* Ecology (CSU LIFE 320)
* Rangeland Herbivore Ecology and Management (CSU RS 452)
* Integrated Ecosystem Management (CSU NR 420)
* Pastoralism and Natural Resource Management (SIT Mongolia)
* Rangeland Measurements and Monitoring (CSU RS 452)
* Natural Resources History and Policy (CSU NR 320)
* Rangeland Assessment (CSU RS 329)
* Rangeland Conservation and Stewardship (CSU RS 300)
* Plant Identification (CSU BZ 223)
