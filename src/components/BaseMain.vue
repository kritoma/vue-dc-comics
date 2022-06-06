<template>
<main>
    <sectionHero/>
    <sectionThumbs/>
</main>
</template>

<script>
import sectionHero from './section/sectionHero.vue';
import sectionThumbs from './section/sectionThumbs.vue';

export default {
    name: "BaseMain",
    components: {
        sectionHero,
        sectionThumbs
    }
}
</script>

<style lang="scss" scoped>  

</style>