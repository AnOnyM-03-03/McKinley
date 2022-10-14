<template>

    <div class="up">
        <p class="text">We have moved into our brand new downtown office at the corner of Broadway and Bellview</p>
    </div>

    <div class="container">
        <nav class="nav">
            <div class="nav-links">
                <img src="../images/logo-header.svg" alt="McKinley" class="logo">
                <ul class="links">
                    <li class="link">Services</li>   
                    <li class="link">About</li>   
                    <li class="link">Articles</li>   
                    <li class="link">Contact</li>   
                </ul>
            </div>
            <div class="nav-connection">
                <a href="tel:(123) 456-7890">(123) 456-7890</a>
                <buttons></buttons>
            </div>
        </nav>
    </div>

</template>
<script>
import buttons from './buttons.vue'
export default{
    components:{buttons}
}

</script>

<style lang="scss" scoped>
    .up{
        background-color:#00486D ;
        color: white;
        text-align: center;
        padding: 8px 0;
    }

    .nav{
        display: flex;
        justify-content: space-between;
        margin-top: 24px;
        margin-bottom: 25px;    

        &-links{
            display: flex;
            align-items: center;
            gap: 40px;
            font-size: 19px;
        }
            .links{
                display: flex;
                gap: 32px;
            }
        &-connection{
            display: flex;
            align-items: center;
            gap: 32px;
            font-size: 17px;
        }
    }

</style>