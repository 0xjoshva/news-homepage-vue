<template>
    <section>
    <nav>
        <img src="../assets/logo.svg" alt="">

        <div class="links">
            <router-link to="/" class="router-link">Home</router-link>
            <router-link to="/lol" class="router-link">New</router-link>
            <router-link to="/lol" class="router-link">Popular</router-link>
            <router-link to="/trending" class="router-link">Trending</router-link>
            <router-link to="/lol" class="router-link">Categories</router-link> 
        </div>
    </nav>
    </section>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    section{
        width: 100%;
        height: fit-content;
        display: flex;
        align-items: center;
        justify-content: center;
        background: var(--bg);
    }
    nav{
        width: 60%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding-top: 5rem;
        padding-bottom: 3rem;
    }
    .links{
        display: flex;
        column-gap: 3rem;
        color: white;
    }
    .router-link{
    color: var(--darkgrayblue);
    font-family: 'Inter', sans-serif;
    font-weight: 400;
    text-decoration: none;
    }
   
    .router-link-active{
        color: var(--softred);
    }
    .router-link-exact-active{
        color: var(--softred);
    }
</style>