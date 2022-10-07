<template>

<section>
    <div class="container">
        <div class="helpers">
            <div class="helpers-card">
                <h1>
                    Personalized <br>
                    Legal Services
                </h1>   
                <p>
                    One size does not fit all when it comes to your legal needs. We craft a team and strategy specific to your desired outcome.
                </p>
                <button class="btn__white">About Our Firm</button>
            </div>
        </div>
    </div>
</section>
</template>

<script>
export default{
data(){

return{ }

},

}

</script>

<style lang="scss" scoped>

    .helpers{
        background-image: url(../images/about-background.png);
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        position: relative;
        height: 680px;
        display: flex;
        justify-content: right;
        align-items: flex-end;
        position: relative;

        &::before{
            content: '';
            width: 208px;
            height: 208px;
            z-index: 2;
            background-image: url(../images/dotts.png);
            position: absolute;
            top: 133px;
            right: -56px;
            background-repeat: no-repeat;
        }
        

        &-card{
            z-index: 3;
            background-color: #00486D;
            color: white;
            width: 423px;
            height: 491px;
            padding: 53px 58px 72px;

            >h1{
                   font-size: 35px;
                   line-height: 42px;
                   margin-bottom: 23px;
                   font-family: 'DM Serif Text';
                   
                   +p{
                    font-size: 19px;
                    line-height: 35px;
                    margin-bottom: 60px;
                   }
                   
            }
            >.btn__white{
                    background-color: white;
                    color: #00486D;
                    padding: 12px 24px;
                    font-size: 18px;
                   }
        }
    }


</style>