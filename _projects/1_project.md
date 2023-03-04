---
layout: page
title: Huntinality
description: Cardinality's first online hunt
img: assets/img/huntinality1_title.png
importance: 1
category: Puzzles
---

The first hunt I ever wrote for, <a href="https://2021.huntinality.com/">Huntinality</a>, was one that I wrote with about 10 of my MIT Mystery Hunt teammates on Cardinality. I was the creative director and lead puzzle editor for this hunt, which consisted of around 20 puzzles. Nearly 500 teams participated in this hunt, which was exciting for what was our first writing effort. I've highlighted some of the puzzles I wrote below.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/datingsim1.png" title="dating sim" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/datingsim2.png" title="dating sim" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    These are screenshots from <a href="https://2021.huntinality.com/puzzle/thedatingsim.html">Dating Sim</a>, a puzzle embedded in a brief dating sim visual novel developed in RenPy. This puzzle was about determining how to satsify constraints about each of the dating show's contestants and making deductions about said constraints to get to an answer. (You might need to download the executables to play since the site is archived at this point.)
</div>


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
