<template>
    <div class="root">
        {{text}}
        <p>
        <button v-if="productValue>0" v-on:click="productValue -= 1">-</button>
        <button v-else>-</button>
<template>{{productValue}}</template>
        <button v-if="productValue<10" v-on:click="productValue += 1">+</button>
        <button v-else>+</button>
        </p>
    </div>
</template>
<script>
export default {
    name:'MyComponent',
    data(){
        return{
            productValue:0,
            text:'Выбирите кол-во продуктов'
        }
    }
    
     
}
</script>