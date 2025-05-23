---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am an Information science grad student at the University of Pittsburgh. At present, I am working as a graduate student researcher in the IRIS lab at the University of Pittsburgh where I am advised by Prof. [Daqing He](https://sites.pitt.edu/~dah44/)<br>
  Currently, my scholarly pursuits are concentrated on leveraging Large Language Models (LLMs) to effectively distill voluminous clinical notes into succinct and informative summaries. 
 In the future am interested in exploring the field of Multimodal machine learning and Explainable AI.<br>
  Previously I was a research intern under [Prof. Pengtao Xie](https://pengtaoxie.github.io/) at UCSD. Back in India, I spent 6 months at TCS Research, Pune.<br>
  Starting from the summer of 2024, I am actively seeking opportunities that align with my research trajectory. I welcome any inquiries about my research endeavors and am enthusiastic to engage in meaningful conversations. Feel free to reach out at your convenience. Here is my [CV](https://github.com/abhibha1807/abhibha1807.github.io/blob/master/Abhibha_Gupta_1Page.pdf)

Timeline
======
* October 2023 - Attending IEEE-EMBS conference on Biomedical and Health Informatics (BHI) at Pittsburgh.
* October 2023 - Our paper 'Argumentative Stance Prediction: An Exploratory Study on Multimodality and Few-Shot Learning' was accepted as part of the 10th Workshop on Argument Mining at EMNLP 2023. 
* September 2023 - Excited to announce that I will be attending Grace Hopper Conference (2023) at Orlando, Florida.
* August 2023 -  Our paper 'Towards Accurate and Clinically Meaningful Summarization of Electronic Health Record Notes: A Guided Approach' was accepted at IEEE-EMBS International Conference on Biomedical and Health Informatics (BHI’23) for presentation!
* June 2023 - Currently collaborating with the SISL lab at Stanford University. 
* August 2022 - Commenced enrollment as a graduate student at the University of Pittsburgh.
* Sept 2022 -  My second paper 'Disambiguating spatial prepositions: The case of geo-spatial sense detection' was published in the Transactions in GIS journal.
* July 2022 -  Our paper 'Neural Architecture Search for Pneumonia Diagnosis from Chest X-Rays' was published at the journal of Nature Scientific reports!
* May 2021 - Started research in the ECE Department at UCSD
* June 2021 - Completed my bachelor's in Computer Science and Engineering 
* May 2020 - Interned at TCS Research, Pune
* July 2017 - Commenced my bachelor's degree from the Indian Institute of Information Technology, Nagpur

Personal Bio
=========

Born in India's diverse tapestry, my life has been a journey across its varied landscapes. Each locale has enriched my identity, fostering a deep appreciation for our cultural richness and honing my adaptability. Traveling is my sanctuary, a means to reconnect and gain fresh perspectives. Nature offers solace, while interactions during my travels have expanded my worldview. My love for photography captures these moments, and my culinary adventures celebrate global flavors. Professionally, my diverse experiences have cultivated an ability to resonate with varied perspectives, aiding my integration into diverse settings. If my journey intrigues you, let's connect and share stories.





<!--
Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
