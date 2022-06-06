<template>
<div class="card">
    <img :src="image" alt="title">
    <h3>{{title}}</h3>
</div>
</template>

<script>
export default {
    name: "componentsThumb",
    props: {
        title: String,
        image: String,
    }
}
</script>

<style lang="scss" scoped>
h3 {
    text-align: left;
}
</style>