<template>
    <NavbarItem/>
    <router-view/>
    <hr/>
    <FooterPage/>
</template>
<script>
import NavbarItem from '@/components/comon/NavbarItem.vue'
import FooterPage from '@/components/comon/FooterPage.vue'
// import RotationLuck from '@/veiws/HomeLink/RotationLuck.vue'
export default {
    components: { NavbarItem, FooterPage}
}
</script>

<style>
 

</style>
