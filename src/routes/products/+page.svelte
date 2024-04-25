<script>
    export let productId = 100;
</script>

<a href="/">Home</a>

<h1><a href="/products">Product List</a></h1>
<h2><a href="/products/1">Product 1</a></h2>
<h2><a href="/products/2">Product 2</a></h2>
<h2><a href={`/products/${productId}`}>Product {productId}</a></h2>
