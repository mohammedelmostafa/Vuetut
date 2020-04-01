<template>
    <div class="our-Blog">
        <h1>{{ PageName }}</h1>
        <p>{{ Desc }}</p>
    </div>
</template>

<script>
export default {
    data: function() {
        return {
            PageName: "Blog Us",
            Desc: "This is Blog page"
        };
    },
    name: "blog"
};
</script>
