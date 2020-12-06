---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
categories: ["", ""]
slug: ""
summary: ""
thumbnail: ""
---
{{< rawhtml >}}
<article class="gallery-article align-right">
    <hgroup class="gallery-title-group">
        <span>galerie :</span>
        <h3 class="gallery-title"></h3>
    </hgroup>
	<p></p>
	<p class="signature">Planas de Font</p>
</article>
<ul class="parent">
    <li class="child">
    	<img src="01.jpg" alt="n°1">
    </li>
    <li class="child">
    	<img src="02.jpg" alt="n°2">
    </li>
    <li class="child">
    	<img src="03.jpg" alt="n°3">
    </li>
</ul>
{{< /rawhtml >}}