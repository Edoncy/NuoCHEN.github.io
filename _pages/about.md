---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<style>
  .rucred {
    display: inline-block;
    background-color: rgb(174, 11, 42);
    color: white;
    font-size: 0.8em;
    padding: 2px 6px;
    border-radius: 3px;
    margin-left: 8px;
    font-weight: bold;
    vertical-align: middle;
  }
  .badge {
    font-weight: 600;
    margin-bottom: 5px;
  }
</style>

<style>
  .logo-row {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.5rem;
    margin-top: 2rem; 
  }
  .logo-row img {
    height: 60px;
    width: auto;
    /* 
       border-radius: 6px;
       box-shadow: 0 0 6px rgba(0,0,0,.15); */
  }
</style>

<style>
  .site-footer {
    text-align: center;
    font-size: 0.85em;
    color: rgb(128, 128, 128);
    margin: 2rem 0 1rem; 
  }
  .site-footer a {
    color: inherit;
    text-decoration: underline;
  }
</style>

<span class='anchor' id='about-me'></span>

About me
======
I'm a PhD student from in Deparmnet of aivil Engineering at the University of Hong Kong (HKU) under supervised by [Prof. Clarence E. Choi](https://www.civil.hku.hk/pp-choice.html). Before start my PhD study, I also had a Msc degree from HKU. I obtained my B.Eng degree from Central South University (CSU) which was advised by [Prof. Jiren Xie](https://faculty.csu.edu.cn/xiejiren/zh_CN/index.htm).

Research interest
======
- Landslides mechanism
- Machine learning in geotechnical engineering
- Landslides early warning and respond

News
======
9/2025- I start my PhD study at HKU!

Education
======
- **2024.09–2025.09**: MSc in Civil Engineering (Geotechnical Engineering Stream)  
  – *The University of Hong Kong (China, Hong Kong SAR)*  
- **2020.09–2024.06**: BEng in Civil Engineering  
  – *Central South University (China, Hunan)*  


Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
