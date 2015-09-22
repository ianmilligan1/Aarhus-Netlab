# NetLab Meeting, 22 September 2015, Aarhus University (Denmark)

![Virtual Machine with Gephi running](https://raw.githubusercontent.com/ianmilligan1/Aarhus-Netlab/master/Gephi-VM-In-Action.png)
_Figure 1: Virtual Machine with Gephi running_

I was invited to speak to the Danish [NetLab](http://netlab.dk/) about historians and web archives. The presentation includes:
- why I think historians need to use web archives;
- why existing acccess methods (i.e. Wayback Machine or Archive-It search) are insufficient;
- how a combination of Warcbase and Shine can help you unlock your collections!

Slidedeck has been uploaded as a PDF, [available here](https://github.com/ianmilligan1/Aarhus-Netlab/blob/master/Large-Scale-Web-Archive-Mining-Slidedeck.pdf). [Download it here](https://github.com/ianmilligan1/Aarhus-Netlab/raw/master/Large-Scale-Web-Archive-Mining-Slidedeck.pdf)

I was also invited to speak, later in the day, at the Centre for Internet Studies on my work with the GeoCities torrent. [The page about my talk is available here](http://cfi.au.dk/news/article/artikel/cfi-seminar-web-history-geocities-and-news-websites/).

Some links:

## Warcbase
[The Warcbase Wiki is available here](https://github.com/lintool/warcbase/wiki)  
[The Gephi: Converting Site Link Structure is available here](https://github.com/lintool/warcbase/wiki/Gephi:-Converting-Site-Link-Structure-into-Dynamic-Visualization)

And sample data provided in this repo: output from [Site Link Structure](https://github.com/lintool/warcbase/wiki/Pig:-Analysis-of-Site-Link-Structure) is part-r-00000; output from `pig2gdf.py` can be found in `political-links.csv`.

I will show a brief example with Gephi. If you have trouble using Gephi, see my section on troubleshooting below.

## Shine
[WebArchives.ca](http://webarchives.ca/): a search interface for Archive-It's collection of [Canadian Political Parties and Interest Groups](https://archive-it.org/collections/227).

![Shine](https://raw.githubusercontent.com/ianmilligan1/Aarhus-Netlab/master/Shine.png)
_Figure 2: Shine in Action_

WebArchives.ca is an implementation of the UK Web Archive's [Shine Interface](https://github.com/ukwa/shine) – an amazing front end that I'll be talking about in the lecture.

It received [some media attention in Canada](http://www.cbc.ca/news/canada/kitchener-waterloo/waterloo-professor-restores-deleted-political-platforms-promises-1.3204877), showing an appetite for this sort of material.

## Gephi Troubleshooting: HistoryCrawler Virtual Machine
[Gephi](http://gephi.github.io/) can occasionally be a nightmare to get running, at least on Mac OS X. Seemingly, every time you upgrade an OS X version it breaks. One workaround, confirmed to work on OS X Mavericks and OS X Yosemite, can be [found on my blog](http://ianmilligan.ca/2014/07/15/getting-gephi-running-on-os-x-mavericks/).

One way to make sure you can get around Java issues is to use a Virtual Machine. 

One example is [HistoryCrawler](http://ianmilligan.ca/historycrawler/), developed at Western University and the University of Waterloo. It does not have Gephi included, but the install instructions [on their webpage](http://gephi.github.io/users/install/) work swimmingly (tested 20 September 2015). It uses VirtualBox.

## Questions/Comments
I am always happy to chat. My personal website is at [ianmilligan.ca](http://ianmilligan.ca) or you can [e-mail me](mailto:i2millig@uwaterloo.ca].
