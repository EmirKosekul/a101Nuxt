<template>
    <headera101/>
    <navbarButtons/>
    <ucuz/>
    <kategoriler1/>
    <kategoriler2/>
    <oneCikanlar/>
</template>

<style>


</style>


<script>
import headera101 from "./components/header.vue"
import ucuz from "./components/ucuz.vue"
import kategoriler1 from "./components/kategoriler1.vue"
import kategoriler2 from "./components/kategoriler2.vue"
import oneCikanlar from "./components/oneCikanlar.vue"
import navbarButtons from "./components/navbarButtons.vue"

export default{
 
  components:{
    headera101,
    ucuz,
    kategoriler1,
    kategoriler2,
    oneCikanlar,
    navbarButtons,
  },
}

</script>
