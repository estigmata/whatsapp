<template>
  <div class="sidebar-nav">
    <sidebar-header></sidebar-header>
    <sidebar-search></sidebar-search>
    <sidebar-contacts></sidebar-contacts>
  </div>
</template>

<script>
import SideBarHeader from '@/components/sidebarnav/sidebar.header.vue'
import SideBarSearch from '@/components/sidebarnav/sidebar.search.vue'
import SideBarContacts from '@/components/sidebarnav/sidebar.contacts.vue'

export default {
  name: 'SideBarNav',
  components: {
    'sidebar-header': SideBarHeader,
    'sidebar-search': SideBarSearch,
    'sidebar-contacts': SideBarContacts
  }
}
</script>
