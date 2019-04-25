<template>
    <div class="credibility down-arrow">
        <div class="container">
            <ul class="d-flex flex-wrap justify-content-center align-items-center m-0 p-0">
                <li>
                    <img class="mr-2" src="https://tw-template4.netlify.com/assets/images/credibility/abn-checked.png" alt="ABN Checked">
                    <p class="m-0">ABN Checked</p>
                </li>
                <li>
                    <img class="mr-2" src="https://tw-template4.netlify.com/assets/images/credibility/licensed-insured.png" alt="Licensed and Insured">
                    <p class="m-0">Licensed and Insured</p>
                </li>
                <li>
                    <img class="mr-2" src="https://tw-template4.netlify.com/assets/images/credibility/fix4me-verified.png" alt="Fix4me Verified">
                    <p class="m-0">Fix4me Verified</p>
                </li>
                <li>
                    <img class="mr-2" src="https://tw-template4.netlify.com/assets/images/credibility/emergency-work.png" alt="Emergency Work">
                    <p class="m-0">Emergency Work</p>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .credibility.down-arrow {
        position: relative;
        background: #484a4b;
        padding: 1.25rem;

        ::after {
            background: #484a4b;
            content: '';
            position: absolute;
            width: 70px;
            height: 70px;
            display: flex;
            justify-content: center;
            -webkit-transform: rotate(45deg);
            transform: rotate(45deg);
            z-index: -1;
            left: 48.2%;
            bottom: -10px;
        }

        .container {
            width: 100%;
            padding-right: 15px;
            padding-left: 15px;
            margin-right: auto;
            margin-left: auto;

            ul {
                list-style-type: none;

                li {
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    margin: 0 1.5rem;

                    p {
                        color: #fff;
                    }
                }
            }
        }
    }
</style>
