<template>
    <div class="root">
        {{text}}
        <p>
        <button v-on:click="productValue -= 1">-</button>
<template>{{productValue}}</template>
        <button v-on:click="productValue += 1">+</button>
        </p>
    </div>
</template>
<script>
export default {
    name:'MyComponent',
    data(){
        return{
            
            text:'Выбирите кол-во продуктов'
        }
    }
    
     
}
</script>