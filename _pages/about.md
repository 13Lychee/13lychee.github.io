---
permalink: /
title: "Liqi Cheng's Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About Me

I am currently a 3th-year Ph.D. candidate at Zhejiang University, under the supervision of [Prof. Yingcai Wu (巫英才)](https://person.zju.edu.cn/ycwu).  I am studying at the State Key Lab of CAD&CG, Zhejiang University and a member of [Interactive Data Group (IDG)](https://zjuidg.org/).

My research revolves around the intersection of computer and sports science. My work encompasses Sports Visual Analytics, Immersive Analytics, and Human-Computer Interaction.

Contact: [lycheecheng@zju.edu.cn](mailto:lycheecheng@zju.edu.cn)



# News

- 07/2024: A paper accepted to ACM UIST 2024 and a paper accepted to IEEE VIS 2024.
- 04/2024: A paper about "sports news generation" accepted to IEEE TVCG.
- 12/2023: A paper accepted to AAAI.

# Publications

<style> td, th {    border: none!important; } </style>
<div align="center"> <table rules="none"> 
    <tr>  
    <td> <img src="/images/viscourt.png" style="zoom:50%"  alt="图片名称"/> </td> <td> 
    <p><b>VisCourt: In-Situ Guidance for Interactive Tactic Training in Mixed Reality | ACM UIST'24</p></b> <p>
    <em>The 37th ACM Symposium on User Interface Software and Technology.</em>
    </p> 
    <p><b>Liqi Cheng</b>, Hanze Jia, Lingyun Yu, Yihong Wu, Shuainan Ye, Dazhen Deng, Hui Zhang, Xiao Xie, and Yingcai Wu</p>
     <p><a href="/files/viscourt.pdf">Paper</a> </p> </td></tr>
    <tr>  
    <td> <img src="/images/smartboard.png" style="zoom:50%"  alt="图片名称"/> </td> <td> 
    <p><b>Smartboard: Visual Exploration of Team Tactics with LLM Agent | IEEE VIS'24</p></b> <p>
    <em>IEEE Transactions on Visualization and Computer Graphics, 2024. (VIS 2024)</em>
    </p> 
    <p>Ziao Liu, Xiao Xie, Moqi He, Wenshuo Zhao, Yihong W, <b>Liqi Cheng</b>, Hui Zhang, and Yingcai Wu</p>
     <p><a href="/files/smartboard.pdf">Paper</a> <b> | </b> <a href="https://ieeexplore.ieee.org/document/10670515">DOI</a> </p> </td></tr> 
 <tr>  <td> <img src="/images/snil.png" style="zoom:50%"  alt="图片名称"/> </td> <td> <p><b>SNIL: Generating Sports News From Insights With Large Language Models | TVCG 24</p></b>
     <em>IEEE Transactions on Visualization and Computer Graphics, 2024.</em>
     <p><b>Liqi Cheng</b>, Dazhen Deng, Xiao Xie, Rihong Qiu, Mingliang Xu, and Yingcai Wu</p>
     <p><a href="/files/snil.pdf">Paper</a> <b> | </b> <a href="https://ieeexplore.ieee.org/document/10507016/">DOI</a> </p> </td></tr>
 <tr>  <td> <img src="/images/vistec.png" style="zoom:50%"  alt="图片名称"/> </td> <td> <p><b>
ViSTec: Video Modeling for Sports Technique Recognition and Tactical Analysis | AAAI'24</p></b> 
     <p>
    <em>Proceedings of the 38th AAAI Conference on Artificial Intelligence.</em>
    </p>
     <p>Yuchen He, Zeqing Yuan, Yihong Wu, <b>Liqi Cheng</b>, Dazhen Deng, and Yingcai Wu</p> 
     <p><a href="/files/vistec.pdf">Paper</a> <b> | </b> <a href="https://vistec2024.github.io/">Video</a> <b> | </b> <a href="https://doi.org/10.1609/AAAI.V38I8.28692">DOI</a>  </p> </td></tr></table>     </div>

Educations
======
- [2022.09-current] Ph.D. Candidate, Zhejiang University, Hangzhou
- [2018.09-2022.06] Undergraduate, Zhejiang University, Hangzhou

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
