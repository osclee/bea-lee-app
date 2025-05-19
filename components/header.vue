<script setup>
const isActive = () => {
    return false;
};
</script>

<template>
    <div>
        <h1 class="title">Beatrice (Bea) Lee</h1>
        <div class="header">
            <nav>
                <ul>
                    <li>
                        <NuxtLink active-class="active-link" :class="{ 'inactive-link': !isActive() }" to="/">Home
                        </NuxtLink>
                    </li>
                    <li>
                        <NuxtLink active-class="active-link" :class="{ 'inactive-link': !isActive() }" to="/resume">Resume
                        </NuxtLink>
                    </li>
                    <li>
                        <NuxtLink active-class="active-link" :class="{ 'inactive-link': !isActive() }" to="/projects">Projects
                        </NuxtLink>
                    </li>
                    <li>
                        <NuxtLink active-class="active-link" :class="{ 'inactive-link': !isActive() }" to="/more">More
                        </NuxtLink>
                    </li>
                </ul>
            </nav>
        </div>

    </div>
</template>

<style scoped>
.title {
    padding-left: .3em;
    margin-top: 1em;
    text-align: center;
}

.header nav {
    display: flex;
    justify-content: center;
    margin-top: 1em;
}

.header nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: flex;
    gap: 1em;
}

.header nav li {
    display: inline-block;
    padding: 0 .6em;
}

.header nav a {
    display: inline-block;
    text-decoration: none;
    outline: none;
}
</style>