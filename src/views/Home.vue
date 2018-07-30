<template>
  <div class="home">
    <sidebar-nav></sidebar-nav>
    <chat-room></chat-room>
  </div>
</template>

<script>
import SideBarNav from '@/components/SideBarNav.vue'
import ChatRoom from '@/components/ChatRoom.vue'

export default {
  name: 'home',
  components: {
    'sidebar-nav':  SideBarNav,
    'chat-room': ChatRoom
  }
}
</script>
