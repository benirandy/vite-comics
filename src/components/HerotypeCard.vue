<template>
    <div class="herotype-card">
        <img :src="image" :alt="title" />
        <h3>{{ title }}</h3>
    </div>
</template>

<script>
export default {
    name: "HerotypeCard",
    props: {
        image: String,
        title: String
    }
}
</script>


<style lang="scss" scoped>
.herotype-card {
    & img {
        width: 100%;
    }
}
</style>