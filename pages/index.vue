<template>
    <div>
        <h3>Index Page</h3>
        <br>
        - You shouldn't see the red background on this page
        <br>
        - The contact page chunk shouldn't fetched on this page because it has no-prefetch prop
        <nuxt-link no-prefetch to="/contact">Contact</nuxt-link>
    </div>
</template>