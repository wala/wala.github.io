# WALA Ariadne

## What is it? 
WALA Ariadne uses static analayis of Python for TensorFlow to give
machine learning practitioners modern software development
support.  The video below gives a flavor of Ariadne:
* Integrated into common IDEs, such as JupyterLab
* Information loads asynchronously, displaying when available
* Information about tensor shapes displayed in code lenses and hovers
* Warning and error diagnostics using standard IDE mechanisms
* Quick fixes using standard IDE mechanisms

<video width="587" height="356" controls>
  <source src="/video/AriadneInJupyterLab.8.3.18.mp4" type="video/mp4"/>
Your browser does not support the video tag.
</video>

# [Download/Install](./ariadne_building.md)

Information on obtaining/installing Ariadne into your favorite IDE is available [here](./ariadne_building.md)

## What IDEs / Editors are supported?
Right now, we support almost every environment and editor that utilizes LSP.
Atom, VSCode, PyCharm, Sublime, Emacs, Vim and NeoVim are known to work.
Additionally, Spyder, Eclipse, and JupyterLabs are all experimentally supported, see their dedicated setup pages for more detail.

## How does it work?
Through static analysis techniques (provided by WALA) such as Data Flow analysis, WALA Ariadne is able to provide type-like functionality that tracks tensors, provides backward slicing to track variables, and much more. We make this functionality available through the Language Server Protocol, meaning in most cases, it's as easy as a simple configuration to get any LSP-supported enviroment up and running.

## Source
The Ariadne framework is open source, hosted on [GitHub](https://github.com/wala/ML).


## How can I help?
We are currently looking for real life code examples to analyze. Leave it messy, leave it commented, we prefer to see the code in its natural state. Let us know what made it annoying or difficult to write, the bugs your encountered, and what kinds of support you'd like to see from a *static* analysis tool.
[Share your feedback here](https://goo.gl/forms/JkQhgOkkEvrtydVc2)

# Mapl 2018 Resources 
* [Slides - WALA Ariadne: Analysis for Machine Learning](https://juliandolby.github.io/mapl/talk/2018/06/14/mapl-ariadne-analysis.html#/)
* [Paper - WALA Ariadne: Analysis for Machine Learning](https://arxiv.org/pdf/1805.04058)
<a href="/poster/MAPL-POSTER-0.9.pdf"><img src="https://raw.githubusercontent.com/wala/wala.github.io/master/poster/MAPL-POSTER-1.0.001.png" alt="MAPL 2018 Poster " class="inline" width="50%" height="50%"/></a>

# JupyterCon 2018 Resources 
<a href="/poster/JupyterConPoster-2018.pdf"><img src="https://raw.githubusercontent.com/wala/wala.github.io/master/poster/JUPYTERCON-POSTER-1.0.001.png" alt="JupyterCon 2018 Poster " class="inline" width="75%" height="75%"/></a>


