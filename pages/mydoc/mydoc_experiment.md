---
title: Experiment
sidebar: mydoc_sidebar
datatable: true
summary: This page is for my experiments with the Jekyll theme. I intend to change it often.
tags: [getting_started, formatting]
keywords: notes, tips, datatable
toc: false
permalink: mydoc_experiment.html
folder: mydoc
---

This is an example of syntax highlighting.

```css
section h1,
#features li strong,
header h2,
footer p {
	font: 100% Rockwell, Arvo, serif;
}

/*
 Styles
 */

* {
	margin: 0;
	padding: 0;
}

body {
	font: 100%/1.5 Questrial, sans-serif;
	tab-size: 4;
	hyphens: auto;
}
```

{% include tip.html content="This is an example of a tip." %}

{% include note.html content="This is an example of a note." %}

<ul id="profileTabs" class="nav nav-tabs">
    <li><a class="noCrossRef" href="#desktop" data-toggle="tab">Desktop</a></li>
    <li class="active"><a class="noCrossRef" href="#web" data-toggle="tab">Web</a></li>
    <li><a class="noCrossRef" href="#mobile" data-toggle="tab">Mobile</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane" id="desktop" markdown="1">

## Desktop

Sample desktop text.

</div>

<div role="tabpanel" class="tab-pane active" id="web">
    <h2>Web</h2>
    <p>Sample web text.</p></div>

<div role="tabpanel" class="tab-pane" id="mobile">
    <h2>Mobile</h2>
    <p>Sample mobile text.</p>
</div>
</div>

<br/><br/>

<div class="datatable-begin"></div>

Term    | Definition                                                                                        
------- | ------------------------------------------------------------------------------------------------- 
Apples  | A small, somewhat round and often red-colored, crispy fruit grown on trees.                       
Bananas | A long and curved, often-yellow, sweet and soft fruit that grows in bunches in tropical climates.

<div class="datatable-end"></div>

<br/><br/>

{% include links.html %}
