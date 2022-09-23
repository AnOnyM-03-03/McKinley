<template>
    <section class="mainScreen">
        <div class="container">
            <div class="content">
                <div class="content-left">
                    <h1 class="content-left__title">Corporate Legal Representation</h1>
                    <p class="content-left__text">
                        We understand the difficulties and stress that your legal issues bring. Our team is committed to providing you with the individual attention, communication, and dedication you deserve.
                    </p>
                    <buttons></buttons>
                </div>
                    <div class="content-right">
                        <div class="content-right__bg-image"></div>
                    <img src="../images/background.png" alt="city" class="content-right__image">
                    </div>
            </div>
        </div>
    </section>

</template>

<script>

import buttons from './buttons.vue'

export default{
    components:{buttons},

data(){

return{ }

},

}

</script>

<style lang="scss" scoped>
    .mainScreen{
        background-color: #E4ECF0;
        position: relative;
        background-image: url(../images/dotts.png);
        background-position: 20px -27%;
        background-repeat: no-repeat;
        margin-bottom: 100px;
    }
    .content{
        display: flex;

        &-left{
            margin-right: 112px;

            &__title{
                font-family: 'DM Serif Text';
                margin-top: 100px;
                font-size: 55px;
                margin-bottom: 25px;
                max-width: 394px;
            }
            &__text{
                font-size: 24px;
                margin-bottom: 35px;
                max-width: 563px;
                line-height: 42px;
            }

        }

        &-right{
            

            &__bg-image{
                background-color: #00486D;
               position: absolute;
               width: 576px;
               height: 753px;
               right: 0;

               &::before{
                content: '';
                position: relative;
                background-image: url(../images/dotts.png);
                background-repeat: no-repeat;
                background-position: 0 0;
               }

              
            }

            &__image{
                // z-index: 2;
                position: relative;
                right: -22px;
                top: 56px;
                height: 753px;

                
            }
               
        }
    }
  

</style>