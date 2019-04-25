<template>
    <div class="hero w-100">
        <div class="container d-flex flex-wrap justify-content-between">
        <h1>Sunny Coast Handyman</h1>
            <div class="hero-details">
                <p class="hd-address">987 The Entrance Road Erina, NSW 2250</p>
                <p class="hd-contact m-0">0413 666 888</p>
                <p class="hd-abn">ABN: 37 123 870 260</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .hero {
        background: #4f5051;

        .container {
            background: url('https://tw-template4.netlify.com/assets/images/hero-bg.png') no-repeat center right;
            padding: 3rem 1rem;
            color: #fff;

            h1 {
                display: flex;
                align-items: center;
                width: 300px;
                font-size: 3rem;
            }

            .hero-details {
                text-align: right;
                font-size: 1.05rem;
            }
        }   
    }
</style>
