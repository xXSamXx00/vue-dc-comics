<template>
    <div>
        <div class="card">
            <img :src="img" alt>
            <h3>{{ title }}</h3>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        img: String,
        title: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.card {
    color: white;
    text-transform: uppercase;
    font-size: 11px;
    img {
        height: 180px;
        width: 180px;
        object-fit: cover;
        object-position: top;
    }
    h3 {
        margin: 10px 0 20px;
    }
}
</style>