<template>
  <main>
    <div class="container-fluid">
        <Thecompany />
        <Excellence />
        <Process />
        <Team />   
        <News />
        <KnowFirst />
    </div>
  </main>
</template>

<script>
import Thecompany from '../components/mainComponents/Thecompany.vue'
import Excellence from '../components/mainComponents/Excellence.vue'
import Process from '../components/mainComponents/Process.vue'
import Team from '../components/mainComponents/Team.vue'
import News from '../components/mainComponents/News.vue'
import KnowFirst from '../components/mainComponents/KnowFirst.vue'
export default {
    name:'Main',
    components: {
        Thecompany,
        Excellence,
        Process,
        Team,
        News,
        KnowFirst,
    }
}
</script>

<style lang="scss" scoped>


</style>