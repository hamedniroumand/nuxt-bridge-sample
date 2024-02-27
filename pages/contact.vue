<template>
    <div>
        <h3>Contact Page</h3>
        <br>
        - You shouldn't see the red background on this page
        <br>
        - The about page chunk shouldn't fetched on this page because it has no-prefetch prop
        <nuxt-link no-prefetch to="/about">About</nuxt-link>
    </div>
</template>