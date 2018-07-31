<template>
  <div class="sidebar-contacts">
    <div class="contact" v-for="contact in contacts" :key="contact.id">
      <div class="avatar">
        <div>
          <img :src="getAvatar(contact.avatar)">
        </div>
      </div>
      <div class="info">
          <div class="top-info">
            <h1>{{contact.name}}</h1>
            <span>{{contact.lastTime}}</span>
          </div>
          <div class="last-msg">
            <span>{{contact.lastMsg}}</span>
          </div>
      </div>
    </div>
  </div>
</template>

<script>
import { contacts } from '@/resources/contacts.js'

export default {
  // props: ['contacts'],
  name: 'sidebarcontacts',
  data () {
    return {
      contacts
    }
  },
  methods: {
    getAvatar (avatar) {
      return { image: require('@/assets/icons/avatar-1.jpg') }//`@~/assets/images/${avatar}`
    },
    greet: function (event) {
      // `this` inside methods points to the Vue instance
      alert('Hello ' + this.name + '!')
      // `event` is the native DOM event
      if (event) {
        alert(event.target.tagName)
      }
    }
  },
  mounted () {
    this.contacts = contacts
  }
}
</script>

<style scoped>
.contact {
  display: flex;
  flex-direction: row;
  height: 72px;
}

.avatar {
  align-items: center;
  display: flex;
  flex-basis: auto;
  flex-grow: 0;
  flex-shrink: 0;
  padding: 0 15px;
}

.avatar > div {
  height: 49px;
  width: 49px;
}

.avatar img {
  border-radius: 50%;
  height: 49px;
  width: 49px;
}

.info {
  border-top: 1px solid #f2f2f2;
  display: flex;
  flex-direction: column;
  flex-grow: 1;
  justify-content: center;
  padding-right: 15px;
}

.top-info {
  align-items: center;
  display: flex;
}

.last-msg {
  align-items: normal;
  display: block;
}

.top-info h1 {
  display: flex;
  flex-grow: 1;
  font-size: 16px;
  font-stretch: 100%;
  font-weight: 400;
  margin: 0;
}

.top-info span {
  color: rgba(0, 0, 0, 0.4);
  display: block;
  flex-basis: auto;
  flex-grow: 0;
  flex-shrink: 0;
  font-size: 12px;
}

.last-msg span {
  color: rgba(0, 0, 0, 0.6);
  font-size: 13px;
}
</style>
