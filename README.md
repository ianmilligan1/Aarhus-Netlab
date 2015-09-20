# Aarhus-Netlab
NetLab Meeting, 22 September 2015, Aarhus University (Denmark)

![Virtual Machine with Gephi running](https://raw.githubusercontent.com/ianmilligan1/Aarhus-Netlab/master/Gephi-VM-In-Action.png)

I was invited to speak to the Danish [NetLab](http://netlab.dk/) about historians and web archives. The presentation includes:
- why I think historians need to use web archives;
- why existing acccess methods (i.e. Wayback Machine or Archive-It search) are insufficient;
- how a combination of Warcbase and Shine can help you unlock your collections!

Slidedeck has been uploaded as a PDF, [available here](https://github.com/ianmilligan1/Aarhus-Netlab/blob/master/Large-Scale-Web-Archive-Mining-Slidedeck.pdf).

I was also invited to speak, later in the day, at the Centre for Internet Studies on my work with the GeoCities torrent. [The page about my talk is available here](http://cfi.au.dk/news/article/artikel/cfi-seminar-web-history-geocities-and-news-websites/).

Some links:

## Warcbase
[The Warcbase Wiki is available here](https://github.com/lintool/warcbase/wiki)  
[The Gephi: Converting Site Link Structure is available here](https://github.com/lintool/warcbase/wiki/Gephi:-Converting-Site-Link-Structure-into-Dynamic-Visualization)

And sample data provided in this repo: output from [Site Link Structure](https://github.com/lintool/warcbase/wiki/Pig:-Analysis-of-Site-Link-Structure) is part-r-00000; output from `pig2gdf.py` can be found in `political-links.csv`.

I will show a brief example with Gephi. It's best if you're running this on your own machine, but if like me you get frustrated with constant updates (esp. with OS X 10.11 looming), a VM can be a good way to experiment with software.

## Shine
[WebArchives.ca](http://webarchives.ca/): a search interface for Archive-It's collection of [Canadian Political Parties and Interest Groups](https://archive-it.org/collections/227).

![Shine](https://raw.githubusercontent.com/ianmilligan1/Aarhus-Netlab/master/Shine.png)

WebArchives.ca is an implementation of the UK Web Archive's [Shine Interface](https://github.com/ukwa/shine) – an amazing front end that I'll be talking about in the lecture.

It received [some media attention in Canada](http://www.cbc.ca/news/canada/kitchener-waterloo/waterloo-professor-restores-deleted-political-platforms-promises-1.3204877), showing an appetite for this sort of material.

## HistoryCrawler Virtual Machine
[Gephi](http://gephi.github.io/) can occasionally be a nightmare to get running, at least on Mac OS X. Seemingly, every time you upgrade an OS X version it breaks. To get around these incompatabilities, I use virtual machines. 

One example is [HistoryCrawler](http://ianmilligan.ca/historycrawler/), developed at Western University and the University of Waterloo. It does not have Gephi included, but the install instructions [on their webpage](http://gephi.github.io/users/install/) work swimmingly (tested 20 September 2015).

## Questions/Comments
I am always happy to chat. My personal website is at [ianmilligan.ca](http://ianmilligan.ca) or you can [e-mail me](mailto:i2millig@uwaterloo.ca].