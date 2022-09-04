---
layout: page
title: PhilologEg
description: formerly AELalign
img: assets/img/12.jpg
importance: 1
category: work
---
This is the home page of PhilologEg (formerly AELalign), a tool and data formats for representing and exchanging electronic resources on texts in the Ancient Egyptian language.

## General documentation
- M.-J. Nederhof. Alignment of resources on Egyptian texts based on XML. In Proceedings of the XIV Computer-aided Egyptology Round Table, Pisa, Italy, July 2002. [pdf]
- M.-J. Nederhof. Egyptological language resources and interlinear representation. Presentation at IAE Computer Group Meeting 2006, Oxford, UK, August 2006. [pdf]
- M.-J. Nederhof. Automatic alignment of hieroglyphs and transliteration. In N. Strudwick, editor, Information Technology and Egyptology in 2008, Proceedings of the meeting of the Computer Working Group of the International Association of Egyptologists, Vienna, July 2008. Gorgias Press. [pdf]
- M.-J. Nederhof. Automatic Creation of Interlinear Text for Philological Purposes. Traitement Automatique des Langues, 50(2):237-255, 2009. [pdf]
- M.-J. Nederhof. Flexible use of text annotations and distance learning. In S. Polis and J. Winand, editors, Texts, Languages & Information Technology in Egyptology, pp. 75-88. Presses Universitaires de Liège, 2013. [pdf]
- M.-J. Nederhof. OCR of handwritten transcriptions of Ancient Egyptian hieroglyphic text. Work presented at Altertumswissenschaften in a Digital Age: Egyptology, Papyrology and Beyond, Leipzig, Germany, November 2015. [pdf]

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
