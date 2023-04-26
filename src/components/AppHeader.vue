<script>
import AppLinks from './AppLinks.vue';

export default {
    name: "AppHeader",
    components: {
        AppLinks
    },
    data() {
        return {
            HeaderLinks: [
                {
                    title: "HOME",
                    image: ""
                },
                {
                    title:"PAGES",
                    image:""
                },
                {
                    title:"MENU",
                    image: ""
                },
                {
                    title:"",
                    image:"logo.png"
                },
                {
                    title:"EVENT",
                    image:""
                },
                {
                    title:"BLOG",
                    image:""
                },
                {
                    title:"LANDING",
                    image:""
                }
                
            ]
        }
    }
}

</script>

<template>
    <div class="header">
       <AppLinks v-for="(link, index) in HeaderLinks" :key="index" :title="link.title"/>
    </div>
    
</template>

<style scoped>
.header {
    display: flex;
    flex-direction: row;
    
}
</style>
