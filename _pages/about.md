---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I recently started working as an oceanographer at the [Bureau of Ocean Energy Management (BOEM)](https://www.boem.gov) headquarters in Virginia, part of the [U.S. Department of the Interior](https://www.doi.gov). Prior to that I was a postdoc and project scientist at the [Scripps Institution of Oceanography](https://scripps.ucsd.edu), U.C. San Diego.

My research aims to better understand regional-scale atmosphere-ocean interactions, which have a strong influence on the climate variability that is felt by communities, including the impacts of climate change. At Scripps I worked with Prof. [Shang-Ping Xie](https://sxie.scrippsprofiles.ucsd.edu/), a world leader in atmosphere-ocean interactions and their impact on climate. We were funded by the [NASA physical oceanography program](https://science.nasa.gov/earth-science/oceanography/physical-ocean) and I worked heavily with satellite observations of oceanic variables such as sea surface temperature, [sea level](https://sealevel.jpl.nasa.gov/missions/), and ocean color; and atmospheric variables such as [surface winds](https://winds.jpl.nasa.gov/missions/quikscat/), rainfall, and clouds. We supplemented satellite data where appropriate with in situ observations from buoys, ships, and gliders.

I run computer simulations with the [Weather Research and Forecasting (WRF)](https://github.com/wrf-model) model and [Regional Ocean Modeling System (ROMS)](https://www.myroms.org/), and utilize gridded reanalyses such as [ERA5](https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/era5) and [NCEP](https://climatedataguide.ucar.edu/climate-data/ncep-reanalysis-r2). I have found that combining satellite observations with numerical modeling is a powerful approach for developing robust explanations about processes in our environment. 

Specific problems I worked on at Scripps include:
* orographic wind forcing of ocean circulation and upwelling in the Southern California Bight
* coupling between surface winds and rainfall
* satellite wind retrieval errors near coastal mountains

I am interested in the application of machine learning and artificial intelligence methods in earth science, and have worked with [Will Chapman](https://scholar.google.com/citations?user=C1ox2CEAAAAJ) at Scripps to utilize convolutional neural networks (deep learning) for the improvement of satellite wind retrievals.

I received a Ph.D. in physical oceanography from the [University of Hawaii](http://www.soest.hawaii.edu/oceanography/index.html) in 2013, working on air-sea interaction around SST fronts; and a S.B. in mathematics from [MIT](https://math.mit.edu/index.php) in 2006. 


AMS Air-Sea Interaction Committee
------
Since 2017, I have served on the American Meteorological Society Air-Sea Interaction Committee. As part of this responsibility, I am helping organize the [Air-Sea Interaction Conference](https://annual.ametsoc.org/index.cfm/2021/program-events/conferences-and-symposia/22nd-conference-on-air-sea-interaction/) at the upcoming [AMS Annual Meeting](https://annual.ametsoc.org/index.cfm/2021/), which will be held in virtual format January 10-14, 2021. Hope to see you there!

Other interests
------
I love spending time outdoors (beaches, hiking, etc.) and indulging my passion for college football. Feel free to reach out to me if you have any questions or just want to say hello (tomk at alum.mit.edu).




Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
