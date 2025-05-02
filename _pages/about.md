---
permalink: /
title: "Adithya Vadapalli"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Assistant Professor at the Computer Science and Engineering Department of IIT Kanpur. I did my Ph.D. at Indiana University Bloomington. After my Ph.D., I was a Postdoctoral Fellow at the University of Waterloo in the CrySP group for two years.


Research
-------------------------------------------------------------------------------
In my research, I build data-leak-proof systems. In creating such data-leak-proof systems, I develop cryptographic primitives and tools that have applications beyond the particular system. Some of my past and planned research is:

* Meta-Data Protection
* Oblivious RAMs
* Secure Multi-Party Computation
* Secure Machine Learning

<!-- Over the past few decades, Internet use has grown precipitously worldwide. 
Today, over 4.7 billion people use social media; we go online for music, news, television, and movies and communicate with family and friends; essential day-to-day services like shopping, banking, and even health care are increasingly delivered virtually.
Further, the COVID-19 pandemic has only accelerated these trends. 
On the one hand, shifting to online services increases efficiency and convenience; on the other hand, it has created an ecosystem of surveillance capitalism riddled with severe privacy threats.
One way of protecting data is building systems such that no unauthorized entity can access the data they are not supposed to.
For instance, building firewalls is one option. 
A more robust approach to tackling this problem is making systems that are _data-leak_ proof, i.e., even if an authorized entity gets access to the data they are not supposed to, they cannot make any sense of it. 
My research is in creating systems for the _secure and private processing of data_, ensuring that data leaks cannot happen, even if an adversary penetrates a company's network.
In my research, I build data-leak-proof systems. 
In creating such data-leak-proof systems, I develop cryptographic primitives and tools that have applications beyond the particular system. 
There are three broad approaches to building data-leak-proof systems:

  * Secure hardware, wherein security guarantees derive from physical properties of hardware (e.g., Trusted Platform Modules, Intel SGX, and ARM TrustZone),
  * Homomorphic cryptography, wherein security guarantees derive from mathematical hardness assumptions (e.g., factoring and discrete logarithms are hard), and
  * Distributed trust, wherein security guarantees derive from trust in the honest behavior of some but not all community members (e.g., secret sharing and multi-party computation).


The three aforementioned methods of achieving secure and private data processing have different pros and cons. 
For instance, while homomorphic encryption performs the worst, trust is the most _reliable_. 
Putting one's trust in secure hardware is less reliable, as some recent works have shown, but it leads to good performance.
Distributed trust is a middle ground in settings where a trust assumption is reasonable. 
In such settings, the protocols are secure so long as the parties involved obey the non-collusion assumption.
These lead to what has been described as ``probably private'' protocols. 
My work so far has relied on _distributed_ trust.
In its broadest strokes, my research aims to develop tools that help users protect their privacy online without sacrificing the modern Internet's conveniences. 
To date, my research contributions run the gamut from low-level cryptographic innovations through the design and analysis of complex systems all the way to heavily optimized implementations of primitives and systems alike.  -->




<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.  -->
