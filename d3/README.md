"Rather than introduce a novel graphical grammar, D3 solves a different,  smaller problem: efficient manipulation of documents based on data." [1]

D3 provides a declarative framework for mapping data to visual elements.

What does that mean?

SQL! Tell the computer what you want, not how to do it.

In viz land?

"custom views of data with simple graphical primitives like bars and
dots. These primitives are called marks, and each mark encodes data
visually through dynamic properties such as color and position.  In
essence, a mark is simply a collection of bound properties for an asso-
ciated graphical form. Figure 1 shows these graphical primitives."[2]

![protovis](/figs/protoviz.png)


How does that play out?

HTML - Markup - Content and Structure
CSS - Styling - Presentation/Appearance
JS - Behavior - Interactivity/Responsiveness

With respect to D3?

HTML - anchors the graph in the  page
CSS - style the graph - aesthetics like color and fill
JS - declare the type of graph and attach elemnts to data

![d3](/figs/d3.png)

Interaction:
* event listeners: callback functions that recieve user input events targeted at specific elements. Callback recieves the data and index (d, i)

Modules:
 * shapes - d3.svg, bound to the d attribute of the svg path
 * scales - visually encode data - oridinal and quantative 
 * layouts - visualization techniques via abstract data structures such as charts and trees
 * behaviors - reusable interaction techniques such as zoom, filtering, etc
 * geo & geom - utilities for projecting data and working with it in pixel space
 * data processing utilites 


Resources:

[1] [D3: Data-Driven Documents](http://vis.stanford.edu/files/2011-D3-InfoVis.pdf)
[2] [Declarative Language Design for Interactive Visualization](http://vis.stanford.edu/files/2010-Protovis-InfoVis.pdf) 
Slides:

Mick Bostock (creator of D3): https://bost.ocks.org/mike/d3/workshop/#0
David Leonard - HTML/CSS/JS to D3: http://slides.com/drksephy/deck-8#/47

