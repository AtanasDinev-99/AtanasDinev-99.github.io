---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my webpage! My name is Atanas Dinev and I am third-year Ph.D. student at the [Operations Research Center](https://orc.mit.edu) at [MIT](https://www.mit.edu) where I am advised by [Prof. Thodoris Lykouris](https://mitmgmtfaculty.mit.edu/tlykouris/). 

My research interests broadly lie in sequential decision-making, machine learning, online algorithms, game theory and their applications to online marketplaces and platforms. I am also generally interested in revenue management and applied modelling. 

Prior to joining MIT, I graduated magna cum laude from [Princeton University](https://www.princeton.edu) with Bacherlor's degree in Mathematics. While at Princeton, I worked with [Prof. Matt Weinberg](https://www.cs.princeton.edu/~smattw/) on projects in Algorithmic Game Theory and Algorithms Under Uncertainty. Here is my [CV](https://AtanasDinev-99.github.io/files/Atanas_Dinev_Resume.pdf). 

In my free time, I enjoy playing table tennis, basketball, and running outdoors. 

Publications
======
[**Social Learning with Limited Attention: Negative Reviews Persist under Newest First**](https://arxiv.org/abs/2406.06929) \\
with Jackie Baek and Thodoris Lykouris \\
Major Revision Operations Research
- 25th ACM Conference on Economics and Computation (EC 2024)
- INFORMS Manufacturing and Service Operations Management Conference SIG Day (MSOM SIG 2025)
- INFORMS Revenue Management and Pricing Section Conference (RMP 2024)


[**Simple and Optimal Online Contention Resolution Schemes for k-uniform matroids**](https://arxiv.org/abs/2309.10078) \\
with S. Matthew Weinberg
- 15th Innovations in Theoretical Computer Science Conference (ITCS 2024)

[**Tight bounds on 3-team manipulations in Randomized Death Match**](https://arxiv.org/abs/2301.07862) \\
with S. Matthew Weinberg
- 18th Conference on Web and Internet Economics (WINE 2022)


Talks
======
**Social Learning with Limited Attention: Negative Reviews Persist under Newest First**
- INFORMS Manufacturing and Service Operations Management Conference SIG Day (MSOM SIG 2025)
- Marketplace Innovation Workshop (MIW 2025)
- INFORMS Annual Meeting in Seattle, WA (INFORMS 2024)
- INFORMS Revenue Management and Pricing Section Conference (RMP 2024)
- 25th ACM Conference on Economics and Computation (EC 2024)
- INFORMS Manufacturing and Service Operations Management Conference (MSOM 2024)

**Simple and Optimal Online Contention Resolution Schemes for k-uniform matroids**
- 15th Innovations in Theoretical Computer Science Conference, Berkeley (ITCS 2024)

**Tight bounds on 3-team manipulations in Randomized Death Match**
- 18th Conference on Web and Internet Economics (WINE 2022)
- [Combinatorics-related Open Problems Seminar (CROPS)](https://stoyandimitrov.net/crops.html?fbclid=IwAR2YP_K7E4hu2kpfAjTL5djYg1rxMdIvRWulIRUNWyP__DD8SPd28OZXXb8), Rutgers University, September 2022


Teaching Experience
====== 
**Data, Models, and Decisions (15.060), Graduate (MBA Core), Fall 2024,  MIT, Teaching Assistant** 

**The Analytics Edge (15.071), Graduate (MBA), Spring 2024,  MIT, Head Teaching Assistant** 

**Economics and Computation (COS 445), Undergraduate, Spring 2022,  Princeton University** 



Academic Serivce
======
**Seminar Coordinator, MIT Operations Research Center Seminar Spring 2025**

**Reviewer for ICML 2025**









<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

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
