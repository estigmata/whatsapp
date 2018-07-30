<template>
  <div class="sidebar-header">
    <div class="container">
      <div class="row">
        <div class="avatar">
          <div class="logo">
            <img src="@/assets/images/avatar.jpg" />
          </div>
        </div>
        <div class="icons">
          <i class="material-icons">filter_tilt_shift</i>
          <i class="material-icons">chat</i>
          <i class="material-icons">more_vert</i>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'sidebarheader'
}
</script>

<style scoped>
.avatar {
  float: left;
}

.avatar .logo {
  height: 57px;
  overflow: hidden;
}

.avatar .logo img {
  border-radius: 50%;
  position: relative;
  top: 50%;
  transform: translateY(-50%);
  width: 40px;
}

.icons {
  float: right;
}

.icons i {
  color: #80868a;
  cursor: pointer;
  height: 57px;
  line-height: 57px;
  margin: 0 15px;
}
</style>
