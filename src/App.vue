<template>

    <div>
        <navigation/>
        <mainScreen/>
    </div>

</template>

<script>

import buttons from './components/buttons.vue'
import navigation from './components/nav.vue'
import mainScreen from './components/main-screen.vue'

export default{
    components: {
        buttons,
        navigation,
        mainScreen,
    },

data(){

return{ }

},

}

</script>

<style lang="scss" scoped>


</style>