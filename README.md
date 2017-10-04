# Getting Started with AAC books

This repository is the home of the source code of the books that create the "Getting Started with AAC" published by the ACE Centre.

## How to add to the project

1. Mark issues in the [issue queue](https://github.com/ACECentre/GettingStartedwithAAC/issues)
2. Fork this repo and make changes. When you are done [submit a pull request](https://help.github.com/articles/fork-a-repo/).
3. If none of that makes sense [drop us a line](http://acecentre.org.uk/contact-us) what you would like to do and we will try and help!

## Roadmap - things we want help with

* Internationalisation(!). i.e. Making the books accessible for other countries. If you have a language translation of the text please let us know - we would love to help. To do this properly you should be prepared to update the videos and resources too! Warning: A lot of work!
 
## A bit of background on this project

There are 3 "branches". 

* Master: This is where the real books are. In each directory there is a "Main.adoc" file. This is a "asciidoctor" file - you can read more on this format [here](http://asciidoctor.org)
* Site: This is the branch that the website aacbooks.net is created from. Its a Jekyll site that is built ontop of [this jekyll theme](https://github.com/ACECentre/aac-theme). 
* gh-pages: This is where the compiled site is stored. Note if either site or master changes then [codeship](https://codeship.com) will build the site here from both branches. 

## Licence:

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Getting Started with AAC</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://acecentre.org.uk" property="cc:attributionName" rel="cc:attributionURL">ACE Centre</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="http://aacbooks.net" rel="dct:source">http://aacbooks.net</a>.
