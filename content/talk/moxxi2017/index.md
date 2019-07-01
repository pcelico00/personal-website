---
title:  'TranscodX: A Generation of Full Stack Environmental Data'
event: 'IAHS Measurements and Observations in the XXI Century (MOXXI) and WMO Hydrohub Joint Meeting (Innovation in Hydrometry: from ideas to operation)'
event_url: 'https://iahs.info/Commissions--W-Groups/Working-Groups/MOXXI/Information/MOXXI-2017.do'
location: 'WMO headquarters, Geneva, Switzerland'
#summary: An example talk using Academic's Markdown slides feature.
abstract: 'In situ monitoring remains the best path to acquire accurate high-frequency and long-term environmental data. However, current in situ environmental monitoring systems often overlook the crucially important inclusion of a comprehensive data management system as part of the installation package. Presently, streamlining commercially-available environmental monitoring systems and adopting a data-from-sensor to storage-and-proper-annotation approach involves continuous and often arduous manual data exports and organization; a process that is inherently subject to frequent break-downs and human errors. These issues constitute the incentives that prompted the development of a solution able to combine collection, transmission, management and delivery into a full stack system designed to support automatic field data streaming into data management system.


This paper introduces TranscodX, a system that facilitates automated stewardship-oriented sensor-to-end user environmental data collection. It features a seamless integration of both front-end (field equipment) and back-end (data management) of a sensor network while supporting all aspects of data management. An auto-programmable datalogger-like hardware component is at the core of the system. This device not only performs the tasks of a typical datalogger, it also captures the appropriate system metadata, transcodes, and streams it to the embedded Data Management, Retrieval and Analysis component. Because of its extended capabilities, we labeled it a Transcoder rather than a datalogger. TranscodX™ also supports the integration and processing of community defined semantics and syntax using the Controlled Vocabularies needed to enable information systems interoperability.


We used Python programming language to develop the necessary software components. The captured data and metadata are automatically stored in an extended instance of the Consortium of Universities for the Advancement of Hydrologic Science, Inc. (CUAHSI)’s Observations Data Model (ODM). An easy-to-navigate web interface is linked to it and makes the data publicly available in users’ preferred units via Web Services (using JSON and WaterML2 formatting) and Data Analytics at a central server. The system has been initially tested in outdoor environments with Soil Moisture and Air Temperature sensors and performed well, matching our expectations. The system is easy to deploy and technically shields users from the domain expertise and learning curve needed to perform complex tasks concerning sensor networks programming and deployment. Thus, it will enable, not only geoscientists, but also citizen scientists to pursue stewardship-oriented environmental data collection.


We are currently planning to engage a group of beta tester that will deploy and test the device under real-world conditions before we move to the production phase.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2017-12-04T08:00:00Z"
date_end: "2017-12-04T08:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-12-04T08:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**IAHS**](https://iahs.info/)'
  focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Follow me
  url: https://twitter.com/paulcelicourt
#url_code: ""
#url_pdf: "https://iahs.info/uploads/working%20groups/MOXXI/Celicourt.pdf"
url_slides: "https://iahs.info/uploads/working%20groups/MOXXI/3_Celicourt.pdf"
#url_video: "https://www.youtube.com/watch?v=51qPkwxNKCg"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#- internal-project

# Enable math on this page?
math: true
---
