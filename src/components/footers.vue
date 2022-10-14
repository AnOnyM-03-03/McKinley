<template>

<footer class="footer">
    <div class="container">
        <div class="content">
            <div class="address">
                <div class="address-logo">
                    <img src="../images/logo-footer.svg" alt="" class="logo">
                </div>
                <p class="address-text">
                    2972 Westheimer Road
                </p>
                <p>
                    Denver, CO 80021
                </p>
                <p>
                    <a class="address-tel" href="tel:(720) 555-0123">(720) 555-0123</a>
                </p>
                <p>
                    <a class="address-email" href="mailto:info.denver@mckinley.com">info.denver@mckinley.com</a>
                </p>
            </div>
            <div class="forms">
                <p class="forms-text">
                    Get legal news, advice, and best practices delivered to your inbox.
                </p>
                <form action="" class="form">
                    <input class="form-email" type="email" placeholder="Email Address">
                    <button class="form-button">
                        <div class="form-button__arrow"></div>
                    </button>
                </form>
                    
            </div>
        </div>
        <div class="social">
            <div class="social-link">
                <img src="../images/facebook.svg" alt="" class="link">
                <p class="social-link__name">Facebook</p>
            </div>

            <div class="social-link">
                <img src="../images/linkedin.svg" alt="" class="link">
                <p class="social-link__name">LinkedIn</p>
            </div>

            <div class="social-link">
                <img src="../images/twitter.svg" alt="" class="link">
                <p class="social-link__name">Twitter</p>
            </div>
        </div>
    </div>
    <div class="copyright">
        <div class="copyright-left">
            <ul class="copyright-left__copy">
                <li>© 2020 McKinley Legal Template •</li>
                <li>Powered by Webflow</li>
            </ul>
        </div>
        <div class="copyright-right">
            <ul class="copyright-right__link">
                <a href="">Style Guide</a>
                <a href="">Licensing</a>
        </ul>
        </div>
    </div>
</footer>

</template>

<script>

export default{

data(){

return{ }

},

}

</script>

<style lang="scss" scoped>

.footer{
    background-color: #00486D;
    color: white;

    .content{
        display: flex;
        padding-top: 123px;
        .address {
            display: flex;
            flex-direction: column;
            margin-right: 190px;
            font-size: 19px;
            line-height: 35px;
            color: #99B6C5;

            &-logo{
                margin-bottom: 40px;
            }
            &-email{
                text-decoration: underline;
            }

        }

        .forms{

            &-text{
                max-width: 389px;
                margin-bottom: 23px;
                font-family: 'DM Serif Text';
                font-size: 28px;
                line-height: 36px;
            }
            .form{
                position: relative;
                

                input[type='email']{
                padding: 11px 45px 10px 10px;
                background-color: #99B6C5;
                color: #00486D;
                border-radius: 2px;
                min-width: 397px;

                ::placeholder{
                    font-size: 19px;
                    line-height: 35px;
                }

                
            }
            &-button{
                width: 35px;
                height: 35px;
                background-color: #00486D;
                position: absolute;
                right: 3px;
                top: 5px;
                
               &__arrow{
                width: 30px;
                height: 2px;
                background-color: #fff;
                margin: 0 auto;
                position: relative;

                &::before{
                    content: '';
                    width: 15px;
                    height: 2px;
                    position: absolute;
                    background-color: #fff;
                    top: -6px;
                    right: -2px;
                    transform: rotate(45deg);

                }

                &::after{
                    content: '';
                    width: 15px;
                    height: 2px;
                    position: absolute;
                    background-color: #fff;
                    top: 6px;
                    right: -2px;
                    transform: rotate(-45deg);

                }

               }
            }

            }

            
            
        }

    }

    .social{
        margin-top: 64px;
        margin-bottom: 134px;

        &-link{
            margin-bottom: 15px;
            display: flex;
            align-items: center;

            &__name{
                margin-left: 8px;
            }
        }
    }

}


.copyright{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 7px 40px 9px 24px;
    font-size: 14px;
    line-height: 35px;
    color: #99B6C5;
    background-color: #002B41;


    &-left{

        &__copy{
            display: flex;

            :last-child{
                margin-left: 5px;
            }
        }

    }
    &-right{

        &__link{

            :last-child{
                margin-left: 16px;
            }
        }

    }
}

</style>