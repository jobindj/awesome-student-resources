<!--- use this to make TOC https://ecotrust-canada.github.io/markdown-toc/ -->

<div align="center">
    <img width="500" height="350" src="media/awesomelogo.png" alt="commawesome">
    <br>
    <br>

<br>

<div align="center">


Tools, tips, & resources for STEM students/researchers 

<div align="left">

# Getting started

Below is a list of resources relevant to any STEM student/researcher.

(This list is a fork from the resources compiled by fellows at the MIT BE Communication Lab)

This list compiles resources to transform data into a clear message through:
- **data analysis and visualization,**
- **figure design,**
- **writing and reference management,**
- **design tools and resources,**
- **professional resources.**

It also includes **resources for reproducibility** and miscellaneous tools for engineering research

- [Getting started](#getting-started)
  - [Legend](#legend)
  - [Computing](#computing)
    - [Programming](#programming)
  - [Data Visualization](#data-visualization)
    - [Data Visualization Resources](#data-visualization-resources)
    - [Plotting Tools](#plotting-tools)
      - [Python Plotting](#python-plotting)
      - [R Plotting](#r-plotting)
      - [Other Plotting tools](#other-plotting-tools)
  - [Reproducible Analysis](#reproducible-analysis)
    - [General Principles](#general-principles)
    - [R workflows](#r-workflows)
    - [Python workflows](#python-workflows)
  - [Scientific Communication](#scientific-communication)
    - [Writing Papers](#writing-papers)
  - [Writing Tools](#writing-tools)
    - [LaTeX](#latex)
    - [Markdown](#markdown)
    - [Citations and Reference Management](#citations-and-reference-management)
  - [Figures](#figures)
    - [Drawing](#drawing)
    - [Image Manipulation](#image-manipulation)
  - [Design Tools & Resources](#design-tools--resources)
    - [Color](#color)
    - [Fonts & Typography](#fonts--typography)
    - [Icons](#icons)
    - [Images](#images)
  - [Poster Design](#poster-design)
    - [Poster Design Tools](#poster-design-tools)
    - [Poster Templates](#poster-templates)
    - [Poster Galleries](#poster-galleries)
  - [Professional Resources](#professional-resources)
  - [Miscellaneous & Unsorted](#miscellaneous--unsorted)
  - [License](#license)

## Legend

|   Symbol   |      Meaning      |
|:----------:|:-----------------:|
|   :free:   |  no upfront cost  |
|  :unlock:  |    open source    |
|  :dollar:  |    small cost     |
| :moneybag: |    large cost     |
| :package:  | Computing Package |
|  :books:   |     Resource      |

---

## Computing
 * [Programming](#programming)
### Programming
*Students typical use the follow resources to analyze and plot data for class and research purposes.*

- [Python](https://www.python.org/) :free: :unlock: – general applicability, open-source; commonly used with [Anaconda](https://anaconda.org/), a package and environment manager

- [R](https://www.r-project.org/) :free: :unlock: - popular for bioinformatics, genomics, statistics; typically used with [RStudio](https://www.rstudio.com/) :free: using packages from [CRAN](https://cran.r-project.org/)
    - [RStudio introduction to R](https://support.rstudio.com/hc/en-us/articles/201141096-Getting-Started-with-R) - a good place to start for complete beginners.
    - [Swirl](https://swirlstats.com/) teaches R within RStudio. A great interactive resource for beginners.

- [MATLAB](https://www.mathworks.com/products/matlab.html) :moneybag: - commercial computing environment offered at MIT for affiliates. See [Gnu Octave](https://www.gnu.org/software/octave/) for an open source :unlock: alternative.

- Other computing languages/platforms used include [Julia](https://julialang.org/) and  [Go](https://golang.org/), but their user bases are much smaller.

## Data Visualization
* [Data Visualization Resources](#data-visualization-resources)
  * [Plotting Tools](#plotting-tools)
    + [Python Plotting](#python-plotting)
    + [R Plotting](#r-plotting)
    + [Other Plotting tools](#other-plotting-tools)

### Data Visualization Resources

-   [Trees, Maps, and Theorems: Effective Communication for Rational Minds by Jean-Luc Doumont](http://www.principiae.be/X0800.php) - The CommLab Bible
-   [http://serialmentor.com/dataviz/](http://serialmentor.com/dataviz/)
-   [https://datavizcatalogue.com/](https://datavizcatalogue.com/)
-   [http://www.cookbook-r.com/Graphs/](http://www.cookbook-r.com/Graphs/)
-   [https://python-graph-gallery.com/](https://python-graph-gallery.com/)
-   [https://www.data-to-viz.com/](https://www.data-to-viz.com/)
- [Grammar of Graphics](https://www.amazon.com/Grammar-Graphics-Statistics-Computing/dp/0387245448/ref=as_li_ss_tl?ie=UTF8&qid=1477928463&sr=8-1&keywords=the+grammar+of+graphics&linkCode=sl1&tag=ggplot2-20&linkId=f0130e557161b83fbe97ba0e9175c431):books::moneybag: - landmark book on foundations in data visualization
- [Plotting One Variable Distributions](https://github.com/MIT-BECL/Plotting-Distributions) - BECL-produced resource for plotting bar graphs, boxplots, violin plots, and more. Includes example data set and raw code files.

### Plotting Tools

#### Python Plotting

-   [matplotlib](https://matplotlib.org/) – the most popular plotting framework
-   Pandas - table management
-   bokeh – interactive web-based visualization
-   [seaborn](https://seaborn.pydata.org/index.html) – opinionated plotting framework for statistical visualizations
-   plotly – interactive web-based visualization
-   altair – straightforward visualization framework, biased towards statistical plotting
-   [Rpy2](http://rpy2.readthedocs.io/en/version\_2.8.x/) - use R code in jupyter notebook
-   [BECL notes](https://github.com/mrsunny0/python-plotting-notes) - BECL-produced resource for python related plotting and getting started.

#### R Plotting
*This is an opinionated summary of key tools for plotting in R, focusing primarily on the [tidyverse](https://www.tidyverse.org/) group of packages*:package:*.*
-   [ggplot2](https://ggplot2.tidyverse.org/):package::unlock: – the most popular plotting framework based on the book, *Grammar of Graphics*
-   [plotly](https://plot.ly/):package::unlock: – commercially supported interactive web-based visualization tools
-   [Shiny](https://shiny.rstudio.com/):package::unlock: – interactive charts and applications on the web, great for displaying public data and generating publication website
-   [reticulate](https://blog.rstudio.com/2018/03/26/reticulate-r-interface-to-python/):package::unlock: - interface with Python via R
-   [ggplot2 Cheatsheet sheet](https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf):books: - quick overview of ggplot2 plotting functions and aesthetics
- [ggplot2 Tutorial](https://tutorials.iq.harvard.edu/R/Rgraphics/Rgraphics.html#introduction):books: - Harvard tutorial on getting started with ggplot2
- [R Graph Gallery](https://www.r-graph-gallery.com/):books: - gallery of plots generated using R
- [R for Data  Science](http://r4ds.had.co.nz/):books: - a **comprehensive** resource to become proficient at using R for all data science needs, written by lead instructors at [RStudio](https://www.rstudio.com/)

#### Other Plotting tools

-   RAW – fast, easy graphs from Excel or CSV files
-   Graphpad Prism – stand-alone plotting program
-   Excel – the one and only
-   Datawrapper – fast, easy graphs from Excel or CSV files
-   Octave – Free version MATLAB
-   [WebPlotDigitiazer](https://automeris.io/WebPlotDigitizer/)

## Reproducible Analysis
* [General Principles](#general-principles)
  * [R workflows](#r-workflows)
  * [Python workflows](#python-workflows)

### General Principles

- [Naming files and projects](https://speakerdeck.com/jennybc/how-to-name-files) :notebook:, a slide deck compiled by Jenny Bryan (@JennyBryan), software engineer at RStudio

### R workflows
- [drake](https://github.com/ropensci/drake) :package: – toolkit to build reproducible workflows that scale
- rapport
- knitr - allows to convert markdown, R, and plots/tables to html or PDF files, similar to Jupyter for python
- workflowr
- here - makes it easy for users to set directories and paths
- ROpenSci

### Python workflows
- [Crash course in reproducible research in Python](http://t-redactyl.io/blog/2016/10/a-crash-course-in-reproducible-research-in-python.html) :notebook:

## Scientific Communication

### Writing Papers

- MIT CommKits ([Biological Engineering](https://mitcommlab.mit.edu/be/use-the-commkit/), [Mechanical Engineering](https://mitcommlab.mit.edu/meche/use-commkit/), [Electrical Engineering and Computer Science](https://mitcommlab.mit.edu/eecs/use-the-commkit/))


## Writing Tools

 
-   [Comparison of different text editors](https://pandoc-scholar.github.io/)

### LaTeX

- [LaTeX primer](https://github.com/mrsunny0/LaTeX-intro)
- [LaTeX Thesis Proposal Template](https://github.com/mrsunny0/LaTeX-thesis-proposal)
- [LaTeX Thesis Defense Template](https://github.com/mrsunny0/LaTeX-thesis-defense)
- [Rticles](https://github.com/rstudio/rticles)
- [Wikibooks](https://en.wikibooks.org/wiki/LaTeX)

### Markdown

-   [Pandoc](https://pandoc.org/) - for switching between .doc/.tex/.md/etc file types
-   Microsoft Word

### Citations and Reference Management

-   [Zotero](https://www.zotero.org/) :free: :unlock:
-   [Mendeley](https://www.mendeley.com/) :free:
-   EndNote :dollar:
-   Papers :dollar:
-   Readcube
-   Jabref

## Figures

 * [Drawing](#drawing)
 * [Image Manipulation](#image-manipulation)
### Drawing

-   Adobe Illustrator :moneybag:
-   [Inkscape](https://inkscape.org/en/) :free: :unlock:
-   Microsoft Powerpoint :hankey:
-   [Affinity Designer](https://affinity.serif.com/en-us/designer/) :dollar:
-   [BioRender](https://biorender.io/) :free:

### Image Manipulation

-   Adobe Photoshop :moneybag:
-   [Affinity Designer](https://affinity.serif.com/en-us/designer/) :dollar:
-   [GIMP](https://www.gimp.org/) :free: :unlock: The GNU Image Manipulation Program
-   ImageJ/Fiji :free: :unlock:


## Design Tools & Resources
 * [Color](#color)
 * [Fonts & Typography](#fonts---typography)
 * [Icons](#icons)
 * [Images](#images)

### Color

-   [ColorBrewer](http://colorbrewer2.org/) - web-based color palette tool with accessibility options ([R package](https://cran.r-project.org/web/packages/RColorBrewer/index.html))
-   [Palettable](https://www.palettable.io) - similar to ColorBrewer with customizable color schemes ([Python package](https://jiffyclub.github.io/palettable/))
-   [Adobe Color CC](https://color.adobe.com/create/color-wheel/) - select color schemes based on color wheel and color harmony
-   [Ggsci](https://nanx.me/ggsci/) - color themes inspired by scientific journals, science fiction, and media
-   [Viz-Palette](http://projects.susielu.com/viz-palette)
-   [GenZ Yellow](https://tul.imgix.net/content/article/gen-z-yellow.jpg?auto=format,compress&w=740&h=486&fit=crop&crop=edges) :trollface:
-   [Millenial Pink](https://i.guim.co.uk/img/media/d0105731685e5b2b3daecf2fa00c9affaba832f1/0_0_2560_1536/master/2560.jpg?width=620&quality=85&auto=format&usm=12&fit=max&s=264f8669796563668ae798cdc3073e35) :trollface:

### Fonts & Typography

-   [Butterick’s Practical Typography](https://practicaltypography.com/) - typography best practices
-   [Google Fonts](https://fonts.google.com/) - select from fonts based on characteristics
-   [Canva](https://www.canva.com/font-combinations/) - font combinations based on starter font
-   [Font Squirrel](https://www.fontsquirrel.com/) - downloadable fonts based on characteristics
-   [Neue Haas Grotesk](http://www.fontbureau.com/nhg/)

### Icons

-   [Noun Project](https://thenounproject.com/) - downloadable icons
-   [IcoMoon](https://icomoon.io/) - more icons

### Images

-   [Unsplash](https://unsplash.com/) - downloadable high-quality images

## Poster Design
* [Poster Design Tools](#poster-design-tools)
* [Poster Templates](#poster-templates)
* [Poster Galleries](#poster-galleries)

### Poster Design Tools

-   Adobe Illustrator :moneybag:
-   [Inkscape](https://inkscape.org/en/)
-   Microsoft Powerpoint :hankey:
-   Adobe InDesign :moneybag:

### Poster Templates

- [Horizontal and Vertical Microsoft PowerPoint and Adobe Illustrator Poster Templates](https://github.com/MIT-BECL/Poster_Resources) :free: :books: - by Tyler Toth and Alex Triassi. Takeaway: white-space friendly poster templates to get you started

### Poster Galleries

- [null](link)

## Professional Resources

- [Github Personal Webpage Boilerplate](https://academicpages.github.io/)
- PhD/Post-Doctoral website examples
    + [https://jef.works/](https://jef.works/) (Harvard, Bioinformatics)
    + [https://www.nikhitasingh.com/](https://www.nikhitasingh.com/) (MIT Media Lab, AI)
    + [https://davidlazar.org/](https://davidlazar.org/) (MIT CSAIL, Computing)
    + [https://www.anishathalye.com/](https://www.anishathalye.com/) (MIT CSAIL, Computing)
    + [https://slowkow.com/](https://slowkow.com/) (Harvard, Immunogenomics)

## Miscellaneous & Unsorted



## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [*MIT BECL*](https://github.com/MIT-BECL) has waived all copyright and related or neighboring rights to the compilation of this list, but not the resources included.
