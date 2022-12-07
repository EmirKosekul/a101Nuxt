<template>
    <headera101/>
    <navbarButtons/>
    <slider1/>
    <bigPicture/>
    <ucuz/>
    <slider2/>
    <kategoriler1/>
    <kategoriler2/>
    <oneCikanlar/>
    <footerr/>
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
import footerr from "./components/footer.vue"
import slider1 from "./components/slider1.vue"
import slider2 from "./components/slider2.vue"
import bigPicture from "./components/bigPicture.vue"

export default{
 
  components:{
    headera101,
    ucuz,
    kategoriler1,
    kategoriler2,
    oneCikanlar,
    navbarButtons,
    footerr,
    slider1,
    slider2,
    bigPicture,
  },
}

</script>
