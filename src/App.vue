<script>
export default{
  data(){
    return{
      message:'WELCOME TO VUE JS',
      nama:'murizal',
      count:0
    }
  },
  methods:{
    increment(){
      this.count++
    }
  }
}
</script>
<template>
<h1>{{message}}</h1>
<p>belajar vue js {{nama}}</p>
{{nilai}}
<ul>
<li style="background:aqua">ayam</li>
<li style="background:green">ayam</li>
<li style="background:blue ">ayam</li>
</ul>
<button style="background-color:white" @click="increment">hitung mulai = {{count}}</button>
</template>