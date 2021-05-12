<template>
    <div class="container">
        <br>
        <div class="row justify-content-center">
            <div class="col-md-8">
                <carousel :items="1" :loop="true" :autoplay="true" :autoHeight="true">
                    <img class="img-fluid" src="/images/oslo.jpg">
                    <img class="img-fluid" src="/images/oslo_Victoria_Terrasse.jpg">
                    <img class="img-fluid" src="/images/trondheimDyreHalses.jpg">
                    <img class="img-fluid" src="/images/trondheimFromRoof.jpg">
                    <img class="img-fluid" src="/images/trondheimSolsiden.jpg">
                </carousel>

            </div>
        </div>
    </div>

</template>

<script>
    import carousel from 'vue-owl-carousel'
    export default {
        components: { carousel }
    }
</script>



