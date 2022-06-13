<template>
  <div>
      <!-- section categories -->
    <section class="categories">
        <h1>categories</h1>
        <div class="list-category">
            <div class="categoty-link"><a href="#" class="best-seller">Best sellers</a></div>
            <div class="categoty-link"><a href="#">Fiction</a></div>
            <div class="categoty-link"><a href="#">Sci-Fi</a></div>
            <div class="categoty-link"><a href="#">Relationships</a></div>
            <div class="categoty-link"><a href="#">Self-Help</a></div>
            <div class="categoty-link"><a href="#">Romance</a></div>
        </div>
    </section>

    <!-- section book  -->
    <section class="books">
        <div class="list-book">
            <div class="book">
                <div class="book-img">
                    <img src="../assets/images/fatal.png" alt="Fatal Forensic Investigation">
                </div>
                <h1>Fatal Forensic Investigation</h1>
                <h3>DARLENE L. TURNER</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. In quas ex molestiae a et nam sit enim quasi <span class="read-more">Read more</span></p>
                <h6 class="price">$55.25</h6>
                <button class="add-cart">Add to cart</button>
            </div>
            <div class="book">
                <div class="book-img">
                    <img src="../assets/images/susan-mallery.png" alt="THE BOARDWALK BOOKSHOP">
                </div>
                <h1>THE BOARDWALK BOOKSHOP</h1>
                <h3>SUSAN MALLERY`</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. In quas ex molestiae a et nam sit enim quasi <span class="read-more">Read more</span></p>
                <h6 class="price">$55.25</h6>
                <button class="add-cart">Add to cart</button>
            </div>
            <div class="book">
                <div class="book-img">
                    <img src="../assets/images/how-to-fake.png" alt="How to Fake a Wedding Date">
                </div>
                <h1>How to Fake a Wedding Date</h1>
                <h3>KAREN BOOTH</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. In quas ex molestiae a et nam sit enim quasi <span class="read-more">Read more</span></p>
                <h6 class="price">$55.25</h6>
                <button class="add-cart">Add to cart</button>
            </div>
            <div class="book">
                <div class="book-img">
                    <img src="../assets/images/matched-by-masala.png" alt="Matched by Masala">
                </div>
                <h1>Matched by Masala</h1>
                <h3>MONA SHROFF</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. In quas ex molestiae a et nam sit enim quasi <span class="read-more">Read more</span></p>
                <h6 class="price">$55.25</h6>
                <button class="add-cart">Add to cart</button>
            </div>
            <div class="book">
                <div class="book-img">
                    <img src="../assets/images/by-masala.png" alt="Bahamas Escape with the Best Man">
                </div>
                <h1>Bahamas Escape with the Best Man</h1>
                <h3>CARA COLTER</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. In quas ex molestiae a et nam sit enim quasi <span class="read-more">Read more</span></p>
                <h6 class="price">$11.99</h6>
                <button class="add-cart">Add to cart</button>
            </div>
            <div class="book">
                <div class="book-img">
                    <img src="../assets/images/trusted.png" alt="TRUSTED & TRUE">
                </div>
                <h1>TRUSTED & TRUE</h1>
                <h3>RHENNA MORGAN</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. In quas ex molestiae a et nam sit enim quasi <span class="read-more">Read more</span></p>
                <h6 class="price">$9.99</h6>
                <button class="add-cart">Add to cart</button>
            </div>
        </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "CategoryView",
};
</script>