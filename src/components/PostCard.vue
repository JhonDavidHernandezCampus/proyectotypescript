<template>
    <div class="post-card">
        <h3>Titulo</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure laudantium quasi eaque rem repellendus ipsa eos pariatur laborum assumenda dolore eius quibusdam, repudiandae deserunt cum sed esse debitis, culpa modi.</p>
        <PostButton/>
    </div>
</template>

<script lang="ts" setup>
    import PostButton from './PostButton.vue' 


</script>

<style scoped>
    .post-card{
        border-radius: 15px;
        padding: 10px;
        margin: 5px;
        border: 1px solid #ccc;
    }
</style>