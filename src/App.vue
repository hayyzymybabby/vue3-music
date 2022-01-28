<template>
  <Header></Header>
  <Tab></Tab>
  <router-view></router-view>
</template>

<script>
import Header from '@/components/header/header'
import Tab from '@/components/tab/tab'
export default {
  components: {
    Header,
    Tab
  }
}
</script>
