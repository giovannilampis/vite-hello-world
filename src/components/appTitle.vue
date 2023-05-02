<template>
    
    <h1>
        Buona giornata 🤩
    </h1>

    <h2>
        {{ message }}
    </h2>

</template>

<script>

    export default{
        name: "AppTitle",
        data() {
            return {
                message: "La mia prima app con Vite!"

            }
        },
       
    }

</script>

<style scoped>

    h2{
        color: gold;
    }

</style>