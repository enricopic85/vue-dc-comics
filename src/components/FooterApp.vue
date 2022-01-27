<template>
   <footer>
       <top-footer/>
       <central-footer/>
       <bottom-footer/>
   </footer>
</template>

<script>
import BottomFooter from './BottomFooter.vue'
import CentralFooter from './CentralFooter.vue'
import TopFooter from './TopFooter.vue'
export default {
  components: { TopFooter, CentralFooter, BottomFooter },
    
}
</script>

<style lang="scss" scoped>
    
</style>