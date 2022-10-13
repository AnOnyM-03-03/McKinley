<template>

<section class="consultation">
    <div class="container">
        <div class="content">
            <h1 class="content-title">Need professional legal advice?</h1>
            <p class="content-description">Get a free consultation with our legal experts</p>
            <buttons></buttons>
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

    .consultation{
        background-color: #E4ECF0;
        padding: 155px 0 176px;
        
    }
    .content{
        display: grid;
        justify-items: center;

        &-title{
            font-family: 'DM Serif Text';
            font-size: 44px;
            line-height: 53px;
            margin-bottom: 19px;
        }

        &-description{
            font-size: 23px;
            line-height: 42px;
            margin-bottom: 52px;
        }
    }


</style>