// components/Navbar.vue
<template>
    <header>
        <div class="container">
            <div class="branding">
                <h1>Farr</h1>
            </div>
            <nav>
                <ul>
                    <li><NuxtLink to="#hero">Home</NuxtLink></li>
                    <li><NuxtLink to="#about">About Me</NuxtLink></li>
                    <li><NuxtLink to="#projects">Projects</NuxtLink></li>
                    <li><NuxtLink to="#contact">Contact</NuxtLink></li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style>
header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    border-bottom: #77a1d3 3px solid;
}
header .branding {
    display: inline-block;
}
header nav {
    float: right;
}
header ul {
    padding: 0;
    list-style: none;
}
header li {
    display: inline;
    padding: 0 20px;
}
header a {
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 16px;
}
</style>
