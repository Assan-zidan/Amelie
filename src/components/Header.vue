<template>
<!-- header -->
    <header class="header">
        <router-link to="/" class="brand">
            <i class='bx bx-book-open'></i>
            <span class="logo-name">BOOKWORM</span>
        </router-link>
        <div class="search">
            <input type="text" placeholder="Search a book" class="search-input">
            <i class='bx bx-search'></i>
        </div>
        <div class="category">
            <router-link to="/category" class="category-link">browse categories</router-link>
            <i class='bx bx-caret-down'></i>
        </div>
        <div class="login">Sign in</div>
        <div class="cart">
            <i class='bx bxs-cart'></i>
            <span class="cart-number">4</span>
        </div>
        
    </header>
</template>

<script>
export default {
  name: "Header",
};
</script>