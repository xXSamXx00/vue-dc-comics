<template>
    <main id="site_main">
        <div class="content">
            <div class="container">
                <h2>&rarr; Content goes here &larr;</h2>
            </div>
        </div>
        <SiteIcons/>
    </main>
</template>

<script>
import SiteIcons from './SiteIcons.vue'
export default {
    components: {
        SiteIcons
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#site_main {
    background-color: black;
    margin-top: 5px;
    .content {
        height: 150px;
        h2 {
            color: white;
            line-height: 150px;
        }
    }
}
</style>