<template>
    <div>
        <h1>Hello World</h1>
    </div>
</template>

<script>
// Import component
import IconifyIcon from '@iconify/vue';
import homeIcon from '@iconify-icons/mdi-light/home';
// const homeIcon = require('@iconify-icons/mdi-light/home')
export default {
    name: "TestTest",
    props: {},
    components: {
        IconifyIcon,
    },
    data() {
       return {
           // Returns icons data that can be used in template
           icons: {
               // Assign homeIcon to icons.home
               //home: homeIcon,
           },
       };
   },
}
</script>
