---
permalink: /
title: "Garima Sharma"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a post-doctoral fellow in the Industrial Relations Section at Princeton University. My research is in development and labor economics. I study market power in developing countries, the causes and consequences of gender disparities in the labor market, and the role of social protection in improving the lives of the poor. In 2024, I will begin as an Assistant Professor of Economics at Northwestern University. I received my Ph.D. from MIT in 2023 and BA from Stanford.

Publications
======
Long-Term Effects of the Targeting the Ultra Poor Program (with Abhijit Banerjee and Esther Duflo). _American Economic Review: Insights_, Volume 3, No. 4, December 2021, Pages 471-486.

Depression and Loneliness Among the Elderly in Low and Middle-Income Countries (with Abhijit Banerjee, Esther Duflo, Erin Grela, Madeline McKelway, Frank Schilbach, and Girija Vaidyanathan). _Journal of Economic Perspectives_, Vol. 3, No.2, Spring 2023.

Effects of Cognitive Behavioral Therapy and Cash Transfers on Older Persons Living Alone in India: A Randomized Trial (with Abhijit Banerjee, Esther Duflo, Erin Grela, Madeline McKelway, Frank Schilbach, Miriam Sequeira, and Girija Vaidyanathan). _Annals of Internal Medicine_, April 2023.

Working Papers
======
[Monopsony and Gender.](/files/monopsony_gender_gsharma.pdf) [April 2023]

Collective Bargaining for Women: How Unions Can Create Female-Friendly Jobs (with Viola Corradini and Lorenzo Lagos). [May 2023]. _Reject and Resubmit: The Quarterly Journal of Economics._ 

Selected Work in Progress
======
Collusion Among Employers in India.

The Effects of Mandated Maternity Leave on Young Women's Labor Market Outcomes (with Lisa Ho and Pulak Ghosh).


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
