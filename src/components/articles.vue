<template>

<section>
    <div class="container">
        <article class="article">
            <h1 class="article-title">
                Recent Articles
            </h1>
            <div class="cards">
                <div class="card">
                    <div class="card-images">
                        <img src="../images/articles-image1.png" alt="12 Вещей О Веб-Дизайне" class="card-img">
                    </div>
                        <div class="card-content">
                            <time class="card-time" datetime="2020-12-13">
                            December 13, 2020
                            </time>
                            <p class="card-description">
                                12 Things About Web Design Your Boss Wants To Know
                            </p>
                            <a class="card-link">
                                Learn More
                            <div class="arrow"></div>
                            </a>
                    </div>
                </div>

                <div class="card">
                    <div class="card-images">
                        <img src="../images/articles-image2.png" alt="12 Вещей О Веб-Дизайне" class="card-img">
                    </div>
                    <div class="card-content">
                            <time class="card-time" datetime="2020-12-10">
                            December 10, 2020
                            </time>
                            <p class="card-description">
                                The History Of Web Design
                            </p>
                            <a class="card-link">
                                Learn More
                            <div class="arrow"></div>
                            </a>
                    </div>
                </div>

                <div class="card">
                    <div class="card-images">
                        <img src="../images/articles-image3.png" alt="12 Вещей О Веб-Дизайне" class="card-img">
                    </div>                    
                        <div class="card-content">
                            <time class="card-time" datetime="2020-12-10">
                            December 10, 2020
                            </time>
                            <p class="card-description">
                                How to improve Web Design Process
                            </p>
                            <a class="card-link">
                                Learn More
                            <div class="arrow"></div>
                            </a>
                    </div>
                </div>
            </div>
        </article>
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


.article{
    padding: 155px 0 160px;

    &-title{
        margin-bottom: 60px;
        font-family: 'DM Serif Text';
        font-size: 44px;
        line-height: 53px;
    }
}


.cards{
        display: flex;
        justify-content: space-between;


        .card{
            border: 1px solid #E4ECF0;
            box-shadow: 0px 24px 24px rgba(0, 72, 109, 0.2);
            border-radius: 2px;

            &-content{
                padding: 40px 33px 41px;
                display: flex;
                flex-direction: column;

            }

            &-description{
                margin-top: 18px;
                margin-bottom: 29px;
                max-width: 294px;
                min-height: 66px;
                font-size: 22px;
                line-height: 35px;

            }

            &-img{
                margin-bottom: auto;
            }
            &-link{
                display: flex;
                align-items: center;
                margin-top: auto;

            }
        }

                .arrow{
                    position: relative;
                    margin-left: 9px;
                    width: 19px;
                    height: 1px;
                    background-color: #00486D;
                    animation: arrow 800ms linear infinite;

                    
                    &::before,
                    &::after
                    {
                        content: '';
                        position: absolute;
                        width: 1px;
                        height: 6px;
                        background-color: #00486D;
                        right: 2px;
                    }
                    &::before{
                        transform: rotate(45deg);
                    }
                    &::after{
                        top: -5px;
                        transform: rotate(-45deg);
                    }
                    @keyframes arrow {
                        0%{
                            left: 0;
                        }
                        50%{
                            left: 10px;
                        }
                        100%{
                            left: 0;
                        }
                    }
                    
                }

                
            }

</style>