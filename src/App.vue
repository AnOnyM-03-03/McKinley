<template>

    <div>
        <navigation/>
        <mainScreen/>
        <information/>
    </div>

</template>

<script>

import buttons from './components/buttons.vue'
import navigation from './components/nav.vue'
import mainScreen from './components/main-screen.vue'
import information from './components/information.vue'

export default{
    components: {
        buttons,
        navigation,
        mainScreen,
        information,
    },

data(){

return{ }

},

}

</script>

<style lang="scss" scoped>


</style>