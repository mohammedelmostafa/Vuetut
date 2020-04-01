<template>
    <div class="our-help">
        <h1>{{ PageName }}</h1>
        <p>{{ Desc }}</p>
    </div>
</template>

<script>
export default {
    data: function() {
        return {
            PageName: "Help Us",
            Desc: "This is Help page"
        };
    },
    name: "help"
};
</script>
