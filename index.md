o---
title: About Alembic
feature_text: |
  ## Sukhi Singh
  I like to think deeply about tensor networks and do cool things with them.
feature_image: "assets/banner.jpeg"
excerpt: "I’m a physicist (and a self-professed part-time philosopher) working at the intersection of quantum information theory, quantum many-body physics, and high-energy physics. I’ve also been applying ideas from quantum physics to compress large neural networks and address NP-hard optimization problems."
---

#### Dec 2023 - Present
I'm a Principle Scientist at [Multiverse Computing](https://multiversecomputing.com/), where I lead a research team to develop tensor network algorithms for [simulating quantum many-body systems on classical computers](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.6.013326), [compressing large neural networks](https://arxiv.org/abs/2401.14109), combinatorial optimization, and quantum chemistry.

#### Jun 2021 - Nov 2023
I was a Senior Research Fellow in the Quantum Information Group led by [Kavan Modi](https://research.monash.edu/en/persons/kavan-modi) at Monash University in Melbourne, Australia. I helped developed a [new theory](https://arxiv.org/abs/2312.04624) of non-Markovian quantum processes with long-range memory, characterized by long-range temporal correlations that decay polynomially. I proposed that a large class of such processes can be represented by tree tensor networks made of causality preserving tensors, which are mathematically described by linear maps between [process tensors](https://arxiv.org/abs/1512.00589), providing a first example of an explicit ansatz for such processes.

#### Jan 2021 - Jun 2021
Had lots of fun and sleepless nights with my twin boys (born in Jan 2021).

#### July 2018 - Dec 2020
I was a Senior Research Fellow in the Quantum Information, Gravity, and Fields group led by [Michal Heller](https://scholar.google.com/citations?user=_zIEMx4AAAAJ&hl=en), where I worked on incorporating conformal symmetry in tensor networks for studying conformal field theories. This work is still incomplete and whatever is finished is unpublished. I've discussed some of the ideas with [Guifre Vidal](https://heritageproject.caltech.edu/interviews/guifre-vidal), [Ingo Runkel](https://www.qu.uni-hamburg.de/cluster/team/runkel.html), [Michal Heller](https://scholar.google.com/citations?user=_zIEMx4AAAAJ&hl=en), and [Dominic Williamson](https://sites.google.com/site/dominicjw/home) and presented them ideas at a couple of workshops -- Mathematics of Conformal Field Theory at the Australian National University in Canberra, Australia (2021), Meeting on string nets and tensor networks in Hamburg, Germany (2020), and the Workshop on Quantum Simulation: Gauge Fields, Holography, and Topology in Bilbao, Spain (2019). 

During this time, I also co-organized and hosted the online [HEP-TN seminars](https://www.youtube.com/playlist?list=PLaib4I4mFNmWKntxAZcB-EQJ_B-PkWEEL). This was before Covid! We were so excited about kickstarting an organized online seminar series that we even posted a [note](https://arxiv.org/pdf/2004.09922) on arXiv trying to convince people that this was a good alternative (or at least a healthy mix) to in-person research visits. 

#### Sep 2018
My beautiful daughter is born, providing my first insight into how humans can, in fact, go for months without much food, sleep, entertainment, etc.

#### Jul 2016 - Jun 2018
I was a Research Fellow in the Quantum Foundations group the Institute of Quantum Optics and Quantum Information, located in the classical city of Vienna, led by [Miguel Navascues](https://www.iqoqi-vienna.at/research/navascues-group). Here, I helped developed a new numerical method for [detecting Bell’s inequalities using tensor networks](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.118.230401) and [renormalization group techniques](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.10.021064) 

#### Sep 2011 - Jun 2016
I was a Research Fellow in the Topological Quantum Computing group at Macquarie University, led by [Gavin Brennen](https://vimeo.com/330707461). 
- I helped generalize the [Time-Evolving Block Decimation algorithm](https://en.wikipedia.org/wiki/Time-evolving_block_decimation) for the classical many-body simulation of [anyons](https://phys.org/news/2024-02-phase-physicists-abelian-anyons-quantum.html). 
- I helped develop a new method for [simulating quantum field theory using wavelets](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.92.032315).
- I [proposed](https://arxiv.org/abs/1409.7873) a new [Matrix Product State](https://tensornetwork.readthedocs.io/en/latest/basic_mps.html)-based algorithm to detect one-dimensional [symmetry protected topological phases of matter](http://topo-houches.pks.mpg.de/wp-content/uploads/2015/01/pollmann_spt.pdf) without using order parameters (local or non-local). I'm actually proud about this work! Regrettably, I never advertised or presented this work (due to unfortunate personal circumstances at the time), so this work went pretty much under the radar. I'm currently exploring a generalization of this method, see list of ongoing projects below.
- I dabbled with a few foundational ideas ([1](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.97.026012), [2](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.97.026013), [3](https://www.nature.com/articles/s41534-020-0255-7)) about [holographic tensor networks](https://www.preposterousuniverse.com/blog/2015/05/05/does-spacetime-emerge-from-quantum-information/).

### Quick setup

To give you a running start I've put together some starter kits that you can download, fork or even deploy immediately:

- ⚗️🍨 Vanilla Jekyll starter kit  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-kit){:style="background: none"}
- ⚗️🌲 Forestry starter kit  
  [![Deploy to Forestry](https://assets.forestry.io/import-to-forestry.svg)](https://app.forestry.io/quick-start?repo=daviddarnes/alembic-forestry-kit&engine=jekyll){:style="background: none"}  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-forestry-kit){:style="background: none"}
- ⚗️💠 Netlify CMS starter kit  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-netlifycms-kit&stack=cms){:style="background: none"}

- ⚗️:octocat: GitHub Pages with remote theme kit  
  {% include button.html text="Download kit" link="https://github.com/daviddarnes/alembic-kit/archive/remote-theme.zip" color="#24292e" %}
- ⚗️🚀 Stackbit starter kit  
  [![Create with Stackbit](https://assets.stackbit.com/badge/create-with-stackbit.svg)](https://app.stackbit.com/create?theme=https://github.com/daviddarnes/alembic-stackbit-kit){:style="background: none"}

### As a Jekyll theme

1. Add `gem "alembic-jekyll-theme"` to your `Gemfile` to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the theme and its dependancies
3. Add `theme: alembic-jekyll-theme` to your `_config.yml` file to set the site theme
4. Run `bundle exec jekyll serve` to build and serve your site
5. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

### As a GitHub Pages remote theme

1. Add `gem "jekyll-remote-theme"` to your `Gemfile` to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
3. Add `jekyll-remote-theme` to the list of `plugins` in your `_config.yml` file
4. Add `remote_theme: daviddarnes/alembic@main` to your `_config.yml` file to set the site theme
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

### As a Boilerplate / Fork

_(deprecated, not recommended)_

1. [Fork the repo](https://github.com/daviddarnes/alembic#fork-destination-box)
2. Replace the `Gemfile` with one stating all the gems used in your project
3. Delete the following unnecessary files/folders: `.github`, `LICENSE`, `screenshot.png`, `CNAME` and `alembic-jekyll-theme.gemspec`
4. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

## Customising

When using Alembic as a theme means you can take advantage of the file overriding method. This allows you to overwrite any file in this theme with your own custom file, by matching the file name and path. The most common example of this would be if you want to add your own styles or change the core style settings.

To add your own styles copy the [`styles.scss`](https://github.com/daviddarnes/alembic/blob/master/assets/styles.scss) into your own project with the same file path (`assets/styles.scss`). From there you can add your own styles, you can even optionally ignore the theme styles by removing the `@import "alembic";` line.

If you're looking to set your own colours and fonts you can overwrite them by matching the variable names from the [`_settings.scss`](https://github.com/daviddarnes/alembic/blob/master/_sass/_settings.scss) file in your own `styles.scss`, make sure to state them before the `@import "alembic";` line so they take effect. The settings are a mixture of custom variables and settings from [Sassline](https://medium.com/@jakegiltsoff/sassline-v2-0-e424b2881e7e) - follow the link to find out how to configure the typographic settings.
