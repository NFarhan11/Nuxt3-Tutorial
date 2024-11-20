<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/products">Nuxt Dojo Merch</NuxtLink>
            </nav>
        </header>
    </div>

    <div>
        <slot />
    </div>

    <footer>
        <ul>
            <li><NuxtLink to="/">Home</NuxtLink></li>
            <li><NuxtLink to="/about">About</NuxtLink></li>
            <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
    </footer>
</template>

<style scoped>
    .router-link-exact-active {
        color: aquamarine;
    }
</style>