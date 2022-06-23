---
permalink: /
title: "Summary"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Miguel Molinos is a recent Ph.D. graduate in Computational Mechanics. His main line of
research is the mathematical and numerical modelling of the inelastic behaviour of structures,
geostructures, and engineering materials (soils, concrete, steel, and rubber-like substances)
using mesh-free techniques.

He received his (4 years) B.Eng. degree in Civil Engineering from the Universidad de Sevilla,
awarding an honours grade for his bachelor’s thesis in tsunami simulation. As an
undergraduate student he did a part-time internship in Drops and Bubbles Technology, a spin-
off of the Department of Aerospace Engineering and Fluid Mechanics of the University of
Seville where he worked in the simulation of bi-phasic flows with the commercial
Computational Fluid Dynamics (CFD) software ANSYS-Fluent. In September 2016 he moved to
Madrid to continue his studies in the School of Civil Engineering of the Universidad Politécnica
de Madrid (UPM).

In 2018 he obtained his (2 years) M.Eng. degree in Civil Engineering finishing in the first decile
of his promotion. Simultaneously, during a part-time internship in the Centre for Hydrographic
Studies (CEDEX, Spanish Public Administration), he contributed to the implementation of a
multi-thread GPU solver for Iber2D (CFD software). This internship provided him with
CV date 28/01/2022 important experience on practical engineering problems in a Technical Laboratory which is a
reference centre of Spain in its domain. This practical experience complements well his solid
theoretical background.

In September 2018 started his predoctoral research career in the Computational Mechanic
field in the Applied Mathematics Department of the Civil Engineering School of the UMP with
the M2i group led by Professor Manuel Pastor. After the first period of training where he took
courses to improve his programming skills (Introduction to R, Python for Engineers, and
Programming in the GPU with CUDA), he started the implementation from scratch of an open-
source code for mesh-free simulations ([NL-PartSol](https://github.com/migmolper/NL-PartSol), C). His research has been focused on the
proposal, development and assessment of the Local maximum-entropy Material Point
Method (LME-MPM) for dynamic, fracture mechanics, finite strains, and poromechanics
problems. His contributions to the M2i group have been relevant. Indeed, he has overseen
opening a new research line, modelling materials with complex behaviour using the LME-MPM
method, instead of the classical SPH approach used so far. His research was financed between
2018 and 2020 by the Agustín de Betancourt foundation and in 2021 by the José Entrecanales
Ibarra foundation.

In 2021 he was granted by the UPM to do a 5-month research stay at the University of
California Berkeley (UCB) where he joined the research group of Professor Kenichi Soga ([SRG](https://geomechanics.berkeley.edu/)).
As a visiting scholar at UCB, he investigated two main topics: (i) the implementation of finite
strain formulations in elastoplasticity in the framework of the LME-MPM method, and (ii) in
the development of a Lagrangian formulation for fluid mechanics problems. During the stage
in UCB, he contributed to enhancing their local code ([CB-Geo](https://github.com/geomechanics/mpm), HPC C++) with the
implementation of the Local maximum-entropy shape functions. It Is worth mentioning that
he currently continues his collaboration with the SRG group in Berkeley via periodic meetings.
In August 2021 he returned to Spain to present a component-free formulation for finite strain
poromechanics problems at the XVI International Conference of Computational Plasticity.
Finally, in December of 2021, he defended his thesis entitled ["The Local Maximum-EntropyMaterial Point Method"](https://oa.upm.es/69327/) obtaining the qualification of cum laude and the recognition of
international doctor. Apart from investigating the research line derived from his thesis, he is
an active collaborator of the existing research line in the M2i group. From the published
papers, it can be seen this interaction, as he has contributed to developing SPH models for soil
dynamics problems domain in which he has acquired the long and solid experience of the
group, together with papers led by him, where is the group who has benefitted. He is an active
member of the competitive projects, ALAS (Plan Estatal 2016), PLAND (Plan Estatal 2019), and
DiscCO2 Store (H2020 Marie Skłodowska-Curie Actions). Indeed, he has contributed to the
elaboration of research proposals, being worth mentioning the last Plan Nacional project,
PLAND, which explicitly includes the novel MPM approach, line of which he is responsible.
Regarding formation activities, he has contributed to the ellaboration of a Massive open
online course (MOOC) entitled “Principales riesgos naturales y su afección a la Sociedad”.
Indeed, the experience of the candidate in advanced calculation schemes (particle and
meshfree methods) and the suitability of such methodologies within the project, make
complementary the skills of the receiving group and the researcher.


A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, migmolper makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/migmolper/migmolper.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://migmolper.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/migmolper/migmolper.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/migmolper/migmolper.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/migmolper/migmolper.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/migmolper/migmolper.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://migmolper.github.io/talks), each [individual page](https://migmolper.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://migmolper.github.io/cv), and the [map of places you've given a talk](https://migmolper.github.io/talkmap.html) (if you run this [python file](https://github.com/migmolper/migmolper.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/migmolper/migmolper.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/migmolper/migmolper.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the migmolper template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/migmolper/migmolper.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring migmolper can be found in [the guide](https://migmolper.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
