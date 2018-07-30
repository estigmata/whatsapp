<template>
  <div class="sidebar-search">
    <div class="container">
      <div class="search">
        <div class="search-group">
          <i class="material-icons">search</i>
          <input placeholder="Buscar o empezar un nuevo chat" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'sidebarsearch'
}
</script>

<style scoped>

.search {
  padding: 6px 0;
}

.search-group {
  align-items: center;
  background-color: #fff;
  border: 1px solid rgba(75, 75, 75, 0.2);
  border-radius: 3px;
  display: flex;
}

.search-group i {
  color: #bec2c4;
  height: 34px;
  line-height: 34px;
  margin: 0 20px;
  width: 24px;
}

.search-group input {
  border: none;
  font-family: "Open Sans", sans-serif;
  margin: 0 15px;
  width: 210px;
}
</style>
