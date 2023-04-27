<script>
import AppHeader from './components/AppHeader.vue';
import AppEvents from './components/AppEvents.vue';
import AppSpecials from './components/AppSpecials.vue'
import { getImagePath } from './utils/helpers';
export default {
    components: {
        AppHeader,
        AppEvents,
        AppSpecials
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
<AppSpecials />

</template>

<style lang="scss">
@use "./style/general.scss"
</style>
