<template>
    <div class="ilustrasi">
        <Navbar />
        <div class="pt-20">
    <Ilustrasi />
    <Footer />
</div>
</div>
</template>

<script>
       import Navbar from "../components/navbar.vue";
       import Ilustrasi from "../components/peminatan/ilustrasi.vue";
       import Footer from "../components/footer.vue";
    export default {
        name: 'ilustrasi',
        components: {Navbar,Ilustrasi,Footer},
    };
</script>