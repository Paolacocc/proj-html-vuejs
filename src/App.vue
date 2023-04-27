<script>
import AppHeader from './components/AppHeader.vue';
import AppEvents from './components/AppEvents.vue';
import { getImagePath } from './utils/helpers';
export default {
    components: {
        AppHeader,
        AppEvents
    },
    data() {
        return {
        
        }
    },
    methods: {
        getImagePath
    }
}

</script>

<template>
<AppHeader />
<AppEvents />

</template>

<style lang="scss">
@use "./style/general.scss"
</style>
