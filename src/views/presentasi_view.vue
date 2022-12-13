<template>
    <div class="presentasi">
        <Navbar />
        <div class="pt-20">
        <Presentasi />
        <Footer />
    </div>
    </div>
</template>

<script>
    import Navbar from "../components/navbar.vue";
    import Presentasi from "../components/peminatan/presentasi.vue";
    import Footer from "../components/footer.vue";
    export default {
        name: 'presentasi',
        components: {Navbar,Presentasi, Footer},
    };
</script>