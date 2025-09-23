---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
In 2015 I graduated from Imperial College London with an MSci Physics degree after which I worked at Goldman Sachs for 5 years and developed an interest in data analytics and efficient decision modelling. In September 2020 I joined the Interactive Artificial Intellgence CDT at the University of Bristol. After the research masters year 2020-2021 I completed my PhD from 2021-2025 and recently passed my viva! My thesis is titled 'Bridging Neuroscience and Machine Learning: EEG Classification for Parkinson’s Disease and Beyond'.

Research Interests
======
My research focuses on applying machine learning to complex time series data to obtain insights through classification and forecasting. I am particularly drawn to the challenges inherent in real-world data, such as missingness, noise, and high dimensionality.

I have extensive experience with Electroencephalography (EEG) data. In one project, we developed a classification method involving a novel transformation of the EEG data, achieving high performance on early-stage Parkinson's classification. This work was presented at the Health Intelligence workshop at AAAI 2024 (pre-print). We extended this research for the Machine Learning and Signal Processing (MLSP) 2024 conference, where we investigated combining connectivity metrics with regional statistics for classification (see [projects and publications](https://amarpal.net//publications/) for further details).

More recently, we explored state-of-the-art deep learning methods for a range of EEG tasks, including emotion detection, mental workload, and eyes-open/closed classification. Our knowledge-based pipeline outperformed established deep learning architectures adapted for EEG, with the added advantage of interpretability via feature attribution. A pre-print of this paper is available [here](https://arxiv.org/pdf/2505.00541) . Below is a figure from this work showing the increased alpha band coherence observed on average for participants with their eyes closed versus open.

[Your figure from the EEG paper will go here]

My work also extends to other domains, such as applying data analysis and visualization techniques to atmospheric data. I have developed projects in Python and Unity to plot and visualize global climate trends over time. The animation below is from a Unity project featuring an interactive 3D visualization.

[Your GIF from the climate modelling project will go here]

Please see [projects and publications](https://amarpal.net//publications/) for further details on my work!

<!---
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

-->