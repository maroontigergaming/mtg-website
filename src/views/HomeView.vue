<template>
  <div class="page">
    <MenuBar class="menuBar">    </MenuBar>
    <TitleCard title="Welcome to the Future MTG App"/>
    <MainBody contentTitle="Big things are on the way...." showContainer="true"/>
  </div>
</template>

<script>
// @ is an alias to /src
import MainBody from '@/components/MainBody.vue';
import TitleCard from '@/components/TitleCard.vue';
import MenuBar from '@/components/MenuBar.vue';


export default {
  name: 'HomeView',
  components: {
    TitleCard,
    MainBody, 
    MenuBar
  }
}
</script>
