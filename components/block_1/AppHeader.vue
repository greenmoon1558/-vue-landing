<template>
  <header>
    <main-title />
    <sub-menu />
    <app-menu />
  </header>
</template>
<script>
import MainTitle from '~/components/block_1/MainTitle.vue'
import SubMenu from '~/components/block_1/SubMenu.vue'
import AppMenu from '~/components/block_1/AppMenu.vue'

export default {
  components: {
    MainTitle,
    SubMenu,
    AppMenu
  }
}
</script>