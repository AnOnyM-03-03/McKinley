<template>
<div class="container">
    <div class="slider">
        <div class="slider-arrow">
            <img src="../images/arrow.svg" alt="left-arrow" class="slider-arrow">
        </div>
        <div class="slider-comments">
            <h2 class="comment">
                The team at McKinley always delivers thoughtful and professional legal services in a timely manner.
            </h2>
            <p class="author">
                John Smith, Tax Law Client
            </p>
        </div>
        <div class="slider-arrow__right">
            <img src="../images/arrow.svg" alt="right-arrow" class="slider-arrow">
        </div>
    </div>

</div>

</template>

<script>

export default{

data(){

return{ }

},

}

</script>

<style lang="scss" scoped>

    .slider{
        display: flex;
        align-items: center;
        justify-content: space-between;
        margin: 134px 0;


        &-comments{
            max-width: 723px;
            text-align: center;

            .comment{
                font-family:'DM Serif Text';
                font-size: 32px;
                line-height: 51.2px;
            }
            .author{
                margin-top: 16px;
                font-size: 15px;
            }
        }
        &-arrow{
            cursor: pointer;
        }
        &-arrow__right{
            transform: rotate(180deg) scale(13.8);
            margin: 134px 0;
        }
    }

</style>