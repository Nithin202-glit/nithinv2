# nithinv2
My cod
{% for product in productss %}
<div class="card" style="width: 18rem;">
  <img class="card-img-top" src="{{ product.image }}" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">{{ product.productname }}</h5>
    <p class="card-text">{{ product.description }}</p>
    <p class="card-text">Price - {{ product.price }}</p>
    <a href="#" class="btn btn-primary">Buy Now</a>
  </div>
</div>
{% endfor %}
