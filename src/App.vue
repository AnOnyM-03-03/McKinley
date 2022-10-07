<template>

    <div>
        <navigation/>
        <mainScreen/>
        <information/>
        <helpers/>
    </div>

</template>

<script>

import buttons from './components/buttons.vue'
import navigation from './components/nav.vue'
import mainScreen from './components/main-screen.vue'
import information from './components/information.vue'
import helpers from './components/helpers.vue'

export default{
    components: {
        buttons,
        navigation,
        mainScreen,
        information,
        helpers,
    },

data(){

return{ }

},

}

</script>

<style lang="scss" scoped>


</style>