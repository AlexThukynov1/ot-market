<template>
    <div class="ot-main-wrapper">
        <ot-catalog></ot-catalog>
        <ot-card></ot-card>
    </div>
</template>

<script>
import otCard from '@/components/ot-card'
import otCatalog from '@/components/ot-catalog'

export default {
   name: 'ot-main-wrapper',
   components: {
    otCard,
    otCatalog
   },
   data() {
    return {}
   }
}
</script>

<style lang="scss">

.ot-main-wrapper {
    max-width:900px;
    margin: 0 auto;
}

</style>