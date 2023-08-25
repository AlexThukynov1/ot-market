<template>
    <div class="ot-catalog">
        <h1>Catalog</h1>
        <div class="ot-catalog__list">
            <ot-catalog-item
                v-for="item in productData"
                :key="item.article"
                :v-bind/>
        </div>
    </div>
</template>

<script>
import otCatalogItem from '@/components/ot-catalog-item'

export default {
   name: 'ot-catalog',
   components: {
    otCatalogItem
   },
   data() {
    return {
        productData: []
    }
   },
   methods: {
    
   },
   mounted() {
    
   },
}
</script>

<style lang="scss">

.ot-catalog {
    &__list {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
    }

}

</style>