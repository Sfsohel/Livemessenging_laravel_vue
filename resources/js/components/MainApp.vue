<template>
    <div id="main-app">
        <chatComponent/>
    </div>
</template>

<script>
    import chatComponent from "./ChatApp";
    export default {
        components:{
          chatComponent
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
