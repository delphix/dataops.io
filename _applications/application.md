---
title: Where Can DataOps Be Applied?
permalink: /applications/
layout: default
redirect_from: /applications/index.html
sectionid: application
---
<div class="header-container jumbotron" style="background-image: url('{{ "/img/where.png" | prepend: site.baseurl }}');">
    <div class="container">
        <h1>{{ page.title }}</h1>
        <p>DataOps can be applied anywhere you find data friction. Below are some use cases by category</p>
    </div>
</div>

<div class="card bg-pattern-light">
  <div class="container">
    <div class="card__grid">
      {% for category_hash in site.data.categories %}
      {% assign category = category_hash[1] %}
        <div class="card__item">
          <div class="card__inner">
            <div class="card__img">
            <a href="{{ "/applications/"  | prepend: site.baseurl | append: category.short_name}}">
              <img src="{{ category.image }}" aria-hidden="true" />
            </a>
          </div>
            <p>{{ category.pretty_name }}</p>
            <p class="card__description text--small">{{ category.description }}</p>
            <div class="card__link">
              <a class="link--arrow link--dark-blue" href="{{ "/applications/"  | prepend: site.baseurl | append: category.short_name}}" role="button">Learn more</a>
              </div>
          </div>
        </div>
      {% endfor %}
    </div>
  </div>
</div>
