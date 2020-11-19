---
permalink: /
title: "Wei Shen"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Associate Professor

AI Institue, Shanghai Jiao Tong University

I'm looking for self-motivated students working with me on Computer Vision and Medical Image Analysis for the fall of 2021. For prospective students, please send me an email with your CV and transcript.

**Research Interests**
======
Computer Vision, Pattern Recognition, Machine Learning, Medical Image Analysis

**Recent News**
======
- One paper has been accepted to IROS 2020.
>* [Towards Unsupervised Learning for Instrument Segmentation in Robotic Surgery with Cycle-Consistent Adversarial Networks] (https://arxiv.org/pdf/2007.04505.pdf)
- One paper has been accepted to ECCV 2020 as oral.
>* [Synthesize then Compare: Detecting Failures and Anomalies for Semantic Segmentation] (https://arxiv.org/pdf/2003.08440.pdf)
- One paper has been accepted to CVPR 2020 as oral
>* [Deep Distance Transform for Tubular Structure Segmentation in CT Scans] (https://arxiv.org/pdf/1912.03383.pdf)
- Two papers have been accepted to MICCAI 2020
>* [Detecting Pancreatic Adenocarcinoma in Multi-phase CT Scans via Alignment Ensemble](https://arxiv.org/pdf/2003.08441.pdf)
>* [Domain Adaptive Relational Reasoning for 3D Multi-Organ Segmentation](https://arxiv.org/pdf/2005.09120.pdf)

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
