<template>
    <div>
        <header>
            <nav>
                <ul>
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/products">Products</NuxtLink></li>
                </ul>
            </nav>
        </header>
    </div>

    <div>
        <slot />
    </div>
</template>

<style scoped>
    .router-link-exact-active {
        color: aquamarine;
    }
</style>