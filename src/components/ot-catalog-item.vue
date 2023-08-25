<template>
    <div class="ot-catalog-item">
        <img class="ot-catalog-item__image" src="" alt=""/>
        <p class="ot-catalog-item__title">Item 1</p>
        <p class="ot-catalog-item__price">Price : 100</p>
        <button class="ot-catalog-item__button">Add to card</button>
    </div>
</template>

<script>
export default {
   name: 'ot-catalog-item',
   props: {
    productData: {
        type:Object,
        default() {
            return {}
        }
    }
   },
   components: {},
   data() {
    return {}
   }
}
</script>

<style lang="scss">
@import "../assets/styles/index.scss";

.ot-catalog-item {
    flex-basis: 25%;
    box-shadow: 0 0 8px 0 #e0e0e0;
    padding:$padding*2;
    margin-bottom: $margin+2;
}
</style>