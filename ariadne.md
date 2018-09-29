---
layout: page
title: "WALA Ariadne"
sidebar-title: "WALA Ariadne"
---

## What is it? 
WALA Ariadne uses static analaysis of Python for TensorFlow to give
machine learning practitioners modern software development
support.  The video below gives a flavor of Ariadne, in this case
integrated into JupyterLab:
* Integrated into common IDEs, such as JupyterLab
* Information loads asynchronously, displaying when available
* Information about tensor shapes displayed in code lenses and hovers
* Warning and error diagnostics using standard IDE mechanisms
* Quick fixes using standard IDE mechanisms

<video width="587" height="356" controls>
  <source src="/video/AriadneInJupyterLab.8.3.18.mp4" type="video/mp4"/>
Your browser does not support the video tag.
</video>

# [Installing Ariadne](./IDE/index.md)

 Right now, we support almost every environment and editor that
utilizes the [Language Server Protocol (LSP)](https://github.com/Microsoft/language-server-protocol): Atom, Eclipse, Emacs, JupyterLab, NeoVim, PyCharm, Sublime, Spyder, Vim and VSCode are known to work to varying degrees.

 Information on obtaining/installing Ariadne into your favorite IDE is 
available [here](./IDE/index.md), or click the logo of your 
favorite IDE below: 

[<img src="/logos/jupyter.png" height="50"/>](/IDE/jupyterlab)[<img src="/logos/VisualCode.png" height="50"/>](/IDE/vscode) [<img src="/logos/pycharm.png" height="50"/>](/IDE/pycharm) [<img src="/logos/eclipse-11-logo-png-transparent.png" height="50"/>](/IDE/eclipse) [<img src="/logos/2000px-Spyder_logo.svg.png" height="50"/>](/IDE/spyder) [<img src="/logos/mslogo.png" height="50"/>](/IDE/monaco) [<img src="/logos/atom-4-logo-png-transparent.png" height="50"/>](/IDE/atom) [<img src="/logos/Apps-Sublime-Text-icon.png" height="50"/>](/IDE/sublime) [<img src="/logos/1024px-EmacsIcon.svg.png" height="50"/>](/IDE/emacs) [<img src="/logos/Vimlogo.svg.png" height="50"/>](/IDE/vim) 

## How does it work?
Through static analysis techniques (provided by WALA) such as Data Flow analysis, WALA Ariadne is able to provide type-like functionality that tracks tensors, provides backward slicing to track variables, and much more. We make this functionality available through the Language Server Protocol, meaning in most cases, it's as easy as a simple configuration to get any LSP-supported enviroment up and running.

## Source
The Ariadne framework is open source, hosted on GitHub, with projects
for the [analysis itself](https://github.com/wala/ML), the
[Language Server Protocol support](https://github.com/wala/IDE) and the
[underlying analysis framework](https://github.com/wala/WALA).


## How can I help?
We are currently looking for real life code examples to analyze. Leave it messy, leave it commented, we prefer to see the code in its natural state. Let us know what made it annoying or difficult to write, the bugs your encountered, and what kinds of support you'd like to see from a *static* analysis tool.
[Share your feedback here](https://goo.gl/forms/JkQhgOkkEvrtydVc2)

# Mapl 2018 Resources 
* [Slides - WALA Ariadne: Analysis for Machine Learning](https://juliandolby.github.io/mapl/talk/2018/06/14/mapl-ariadne-analysis.html#/)
* [Paper - WALA Ariadne: Analysis for Machine Learning](https://arxiv.org/pdf/1805.04058)
<a href="/poster/MAPL-POSTER-0.9.pdf"><img src="https://raw.githubusercontent.com/wala/wala.github.io/master/poster/MAPL-POSTER-1.0.001.png" alt="MAPL 2018 Poster " class="inline" width="50%" height="50%"/></a>

# JupyterCon 2018 Resources 
<a href="/poster/JupyterConPoster-2018.pdf"><img src="https://raw.githubusercontent.com/wala/wala.github.io/master/poster/JUPYTERCON-POSTER-1.0.001.png" alt="JupyterCon 2018 Poster " class="inline" width="75%" height="75%"/></a>


