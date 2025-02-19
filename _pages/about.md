---
permalink: /
title: "Overview"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a recent DPhil graduate in Statistics at Oxford University working at the cross-section of [neuroscience](http://dynamic-brains.com/team), [biology](https://www.pharm.ox.ac.uk/research/emptage-group-synaptic-pharmacology-group) and [data science](http://opig.stats.ox.ac.uk//), with interests in machine learning, networks analysis and [brain-computer interaction](https://www.stx.ox.ac.uk/article/moritz-moeller-and-james-wilsenach-win-br41n.io-hackathon). My research is in biological complex systems with a focus on controlling for and explaining sources of inhomogeneous noise in drug and [protein networks](http://costnet18.wzim.sggw.pl/wp-content/uploads/2018/10/Costnet18_book_of_abstracts.pdf), [time series](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.95.042401) and [neural data](https://appliednetsci.springeropen.com/articles/10.1007/s41109-022-00454-2) using both supervised and unsupervised methods.

My current work at University College London, Wellcome Centre for Neuroimaging is focused on delivering web-based tools for the detection and treatment of [epilepsy](https://en.wikipedia.org/wiki/Epilepsy) using modelling and simulation approaches. These approaches rely on Bayesian estimation of [Dynamic Causal Models](https://en.wikipedia.org/wiki/Dynamic_causal_modeling) of patient EEG data to inform seizure localisation and treatment. I work closely with medical specialists to deliver medically useful computational tools. 

Interests
======
I have a wide range of interests across topics in science and philosophy including questions of consciousness, the [hard problem of consciousness](https://en.wikipedia.org/wiki/Hard_problem_of_consciousness), epistomology and ethics. I want to create real change that improves the lives of people through discovery of how the mind and body work. In my academic life, I have sought to obtain a wide range of skills in artificial intelligence, statistics and biological sciences, with degrees in bioinformatics, neuroinformatics, and machine learning.

I have pursued projects in designing assistive technologies, winning (as part of team [Unibrowser](https://www.br41n.io/Bari-2019#projects)) the Brain Designers Prize at the IEEE Systems, Man and Cybernetics Conference at the (BCI Designers Hackathon) in Bari in 2019, organised by g.tec neurotechnology. Unibrowser is a User Interface (UI) navigation tool, designed to help users with a limited range of motion, to  navigate complex UI systems more easily, through a series of dynamically selected, simple to answer questions.

![Presenting Unibrowser to the Judges at IEEE SMC](/images/pres.png)
<i>Unibrowser final presentation at the Brain-Computer Interface Designers Hackathon in Bari</i>

I completed an internship at Neuroelectrics, a neuromodulation based engineering and research company interested in developing transcranial Electrical Stimulation (tES) based approaches to tackling a range of neurological diseases including epilepsy and Alzheimer's disease as well as Disorders of Consciousness (DOCs). I contributed to various areas of ongoing research including neuronal mass modelling, anatomical reconstruction of neurons and white matter tracts and unsupervised learning and analysis of pathological stereo EEG (sEEG) recordings. Neuroelectrics' flagship tES tool, [Stimweaver](https://www.neuroelectrics.com/solutions/modeling-services), provides an intelligent ways to develop stimulation montages that target specific brain areas, which they plan to utilise to enhance neurofunctionality and fight disease.

<div class="video-container">
<iframe  title="Laminar" width="480" height="390" src="https://youtube.com/embed/OBiVi9CArg8" frameborder="0" allowfullscreen></iframe>
</div>
<i>An early version of the laminar NMM, presented by Roser Sanchez-Todo at Neuroelectrics</i>

In my spare time I am also interested in finding a way to translate between different neuroimaging modalities, namely from cortical Electroencephologram (EEG) to cortical (and possibly subcortical) functional Magnetic Resonance Imaging (fMRI). I believe new developments in this area could be of great use during surgery where high frequency, but low spatial resolution EEG monitoring is easy but more complex mapping of regional activity is difficult. Many current studies show limited amounts of translatability between these modalties, which I hope can be improved upon with new data and machine learning techniques.


<!-- Getting started
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
 -->
