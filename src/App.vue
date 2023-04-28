<script>
import AppHeader from './components/AppHeader.vue';
import AppEvents from './components/AppEvents.vue';
import AppSpecials from './components/AppSpecials.vue'
import AppImages from './components/AppImages.vue';
import AppAssociates from './components/AppAssociates.vue'
import AppMenu from './components/AppMenu.vue'
import AppDeals from './components/AppDeals.vue';
import AppBookTable from './components/AppBookTable.vue';
import AppFooter from './components/AppFooter.vue'

import { getImagePath } from './utils/helpers';

export default {
    components: {
    AppHeader,
    AppEvents,
    AppSpecials,
    AppImages,
    AppAssociates,
    AppMenu,
    AppDeals,
    AppBookTable,
    AppFooter
    
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
<AppImages />
<AppAssociates />
<AppMenu />
<AppDeals />
<AppBookTable />
<AppFooter />

</template>

<style lang="scss">
@use "./style/general.scss";
</style>
