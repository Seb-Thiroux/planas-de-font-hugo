---
title: "Sous Le Petit Pont"
date: 2020-11-29T21:27:04+01:00
draft: false
categories: ["themes"]
slug: "sous-le-petit-pont"
summary: ""
thumbnail: ""
---
{{< rawhtml >}}
<div class="float-sidenav js-float-sidenav" id="float-sidenav-1">
    <nav class="float-sidenav__nav">
      <button class="reset float-sidenav__close-btn js-float-sidenav__close-btn js-tab-focus" aria-label="Close page navigation">
        <svg class="icon" viewBox="0 0 16 16"><g stroke-width="1" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10"><line x1="13.5" y1="2.5" x2="2.5" y2="13.5"></line><line x1="2.5" y1="2.5" x2="13.5" y2="13.5"></line></g></svg>
      </button>
      <ul class="float-sidenav__list js-float-sidenav__list">
        <li class="float-sidenav__item">
          <a href="#peinture-1" class="float-sidenav__link js-smooth-scroll">
            <span class="float-sidenav__label">Painting 1</span>
            <span aria-hidden="true" class="float-sidenav__marker"></span>
          </a>
        </li>
      </ul>
    </nav>
</div>
<!-- <button class="btn btn--subtle margin-bottom-md hide@md" aria-controls="float-sidenav-1">Show Page Navigation</button> -->
<ul class="parent js-float-sidenav-target">
    <li id="peinture-1" class="child">
      <img src="sous-le-petit-pont.jpg" alt="n°1">
    </li>
</ul>
<h3 class="gallery__title-block" aria-controls="modal-full-width">
<span class="gallery__title-prefix">gallery: </span>
<span class="gallery__title">Sous Le Petit Pont</span>
<button class="gallery__title-trigger">
  <svg class="icon" viewBox="0 0 20 20">
    <title>Open the window</title>
    <g fill="none" stroke="currentColor" stroke-miterlimit="10" stroke-width="1" stroke-linecap="round" stroke-linejoin="round">
      <line x1="3" y1="3" x2="15" y2="15" />
      <line x1="15" y1="3" x2="3" y2="15" />
    </g>
  </svg>
</button>
</h3>
<div class="modal modal--animate-fade bg-contrast-higher bg-opacity-90% js-modal" id="modal-full-width">
<div class="modal__content bg height-100% flex flex-column flex-center" role="alertdialog" aria-labelledby="modal-title" aria-describedby="modal-description">
  <div class="">
    <header class="padding-y-sm padding-x-md flex items-center justify-between">
      <h3 class="gallery__title" id="modal-title">Sous Le Petit Pont</h3>
      <button class="reset modal__close-btn modal__close-btn--inner js-modal__close js-tab-focus">
        <svg class="icon" viewBox="0 0 20 20">
          <title>Close the window</title>
          <g fill="none" stroke="currentColor" stroke-miterlimit="10" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <line x1="3" y1="3" x2="17" y2="17" />
            <line x1="17" y1="3" x2="3" y2="17" />
          </g>
        </svg>
      </button>
    </header>
    <article class="padding-y-sm padding-x-md flex-grow overflow-auto">
      <div class="text-component v-space-md line-height-lg">
        <p class="drop-cap gallery__desc-first-line" id="modal-description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae culpa, inventore alias ab atque similique quod ea reprehenderit.</p>
        <p class="signature">Planas de Font</p>
      </div>
    </article>
  </div>
</div> 
</div>
{{< /rawhtml >}}