---
layout: default
permalink: /products/
pagination: 
  enabled: true
  collection: products
  sort_field: 'name'
  sort_reverse: false
  per_page: 2
---

<div class="wrapper light-wrapper page-title-wrapper">
    <div class="container inner text-center">
      <h1 class="page-title">Productos</h1>
      <p class="lead">Aqui encontraras los mejores productos para tu familia, hogar y actividades.</p>
    </div>
    <!-- /.container -->
  </div>

  {% include components/products-list.html %}
  