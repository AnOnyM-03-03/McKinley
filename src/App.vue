<template>

    <div>
        <navigation/>
        <mainScreen/>
        <information/>
        <helpers/>
        <slider/>
    </div>

</template>

<script>

import buttons from './components/buttons.vue'
import navigation from './components/nav.vue'
import mainScreen from './components/main-screen.vue'
import information from './components/information.vue'
import helpers from './components/helpers.vue'
import slider from './components/slider.vue'

export default{
    components: {
        buttons,
        navigation,
        mainScreen,
        information,
        helpers,
        slider,
    },

data(){

return{ }

},

}

</script>

<style lang="scss" scoped>


</style>