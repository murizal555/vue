<script>
export default{
    data(){
     return{
        count:0
     }   
    }
}
</script>

<template>
<button @click="count++">
you click me{{count}} times.
</button>
</template>