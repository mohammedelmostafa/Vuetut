<template>
    <div class="about">
        <h1>{{ PageName }}</h1>
        <p>{{ Desc }}</p>
    </div>
</template>

<script>
// @ is an alias to /src
export default {
    data: function() {
        return {
            PageName: "About Us",
            Desc: "This is About Us page"
        };
    },
    name: "about",
    components: {}
};
</script>
