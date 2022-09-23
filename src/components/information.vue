<template>

    <section>
        <div class="container">
            <div class="information">
                <h2 class="information-title">Areas of Practice</h2>
                <p class="information-text">
                    Our disciplined approach to resolving your legal issues will produce the best-possible outcome.
                </p>
                <div class="cards">
                    <div class="card">
                        <div class="card-logo">
                            <img src="../images/information-web.png" alt="website logo">
                        </div>
                        <p class="card-text">
                            <span>
                                Intellectual Property
                            </span> 
                            Intellectual Property law deals with laws to protect creators and owners of inventions, writing, music, designs and other works.
                        </p>
                        <a class="card-link">Learn More
                            <div class="arrow"></div>
                        </a>
                    </div>

                    <div class="card">
                        <div class="card-logo">
                            <img src="../images/information-house.png" alt="website logo">
                        </div>
                        <p class="card-text">
                            <span>
                                Real Estate
                            </span> 
                            Real estate law is a branch of civil law that covers the right to possess, use, and enjoy land.
                        </p>
                        <a class="card-link">Learn More
                            <div class="arrow"></div>
                        </a>
                    </div>

                    <div class="card">
                        <div class="card-logo">
                            <img src="../images/information-book.png" alt="website logo">
                        </div>
                        <p class="card-text">
                            <span>
                                Tax Law
                            </span> 
                            Tax law cover income, corporate, excise, luxury, estate and property taxes, to name a few.
                        </p>
                        <a class="card-link">Learn More
                            <div class="arrow"></div>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

</template>


<style lang="scss" scoped>


    .information{
        display: flex;
        flex-direction: column;
        margin-bottom: 160px;

        &-title{
            font-family: 'DM Serif Text';
            font-size: 44px;
            margin-bottom: 25px;
        }
        &-text{
            font-size: 24px;
            margin-bottom: 51px;
            width: 605px;
            line-height: 42px;
        }
    }
    .cards{
        display: flex;
        justify-content: space-around;


        .card{
            padding: 44px 30px;
            border: 1px solid #E4ECF0;
            box-shadow: 0px 24px 24px rgba(0, 72, 109, 0.2);
            border-radius: 2px;

            &-text{
                margin-top: 40px;
                margin-bottom: 36px;
                max-width: 328px;
                font-size: 20px;
                line-height: 35px;

                span{
                    margin-bottom: 12px;
                    display: block;
                    font-size: 22px;
                    
                }

            }
            &-link{
                display: flex;
                align-items: center;

                

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

        }

    }


</style>