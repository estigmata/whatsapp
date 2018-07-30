<template>
  <div class="sidebar-contacts">
    <div class="contact">
      <div class="avatar">
        <div>
          <img src="@/assets/images/avatar-1.jpg" />
        </div>
      </div>
      <div class="info">
          <div class="top-info">
            <h1>Lorem Ipsum</h1>
            <span>22:37</span>
          </div>
          <div class="last-msg">
            <span>Some One: Dolor sit amet consectetur ...</span>
          </div>
      </div>
    </div>
    <div class="contact">
      <div class="avatar">
        <div>
          <img src="@/assets/images/avatar-2.jpg" />
        </div>
      </div>
      <div class="info">
          <div class="top-info">
            <h1>Lorem Ipsum</h1>
            <span>22:37</span>
          </div>
          <div class="last-msg">
            <span>Some One: Dolor sit amet consectetur ...</span>
          </div>
      </div>
    </div>
    <div class="contact">
      <div class="avatar">
        <div>
          <img src="@/assets/images/avatar-3.jpg" />
        </div>
      </div>
      <div class="info">
          <div class="top-info">
            <h1>Lorem Ipsum</h1>
            <span>22:37</span>
          </div>
          <div class="last-msg">
            <span>Some One: Dolor sit amet consectetur ...</span>
          </div>
      </div>
    </div>
    <div class="contact">
      <div class="avatar">
        <div>
          <img src="@/assets/images/avatar-4.jpg" />
        </div>
      </div>
      <div class="info">
          <div class="top-info">
            <h1>Lorem Ipsum</h1>
            <span>22:37</span>
          </div>
          <div class="last-msg">
            <span>Some One: Dolor sit amet consectetur ...</span>
          </div>
      </div>
    </div>
    <div class="contact">
      <div class="avatar">
        <div>
          <img src="@/assets/images/avatar-5.jpg" />
        </div>
      </div>
      <div class="info">
          <div class="top-info">
            <h1>Lorem Ipsum</h1>
            <span>22:37</span>
          </div>
          <div class="last-msg">
            <span>Some One: Dolor sit amet consectetur ...</span>
          </div>
      </div>
    </div>
    <div class="contact">
      <div class="avatar">
        <div>
          <img src="@/assets/images/avatar-6.jpg" />
        </div>
      </div>
      <div class="info">
          <div class="top-info">
            <h1>Lorem Ipsum</h1>
            <span>22:37</span>
          </div>
          <div class="last-msg">
            <span>Some One: Dolor sit amet consectetur ...</span>
          </div>
      </div>
    </div>
    <div class="contact">
      <div class="avatar">
        <div>
          <img src="@/assets/images/avatar-7.jpg" />
        </div>
      </div>
      <div class="info">
          <div class="top-info">
            <h1>Lorem Ipsum</h1>
            <span>22:37</span>
          </div>
          <div class="last-msg">
            <span>Some One: Dolor sit amet consectetur ...</span>
          </div>
      </div>
    </div>
    <div class="contact">
      <div class="avatar">
        <div>
          <img src="@/assets/images/avatar-8.jpg" />
        </div>
      </div>
      <div class="info">
          <div class="top-info">
            <h1>Lorem Ipsum</h1>
            <span>22:37</span>
          </div>
          <div class="last-msg">
            <span>Some One: Dolor sit amet consectetur ...</span>
          </div>
      </div>
    </div>
    <div class="contact">
      <div class="avatar">
        <div>
          <img src="@/assets/images/avatar-9.jpg" />
        </div>
      </div>
      <div class="info">
          <div class="top-info">
            <h1>Lorem Ipsum</h1>
            <span>22:37</span>
          </div>
          <div class="last-msg">
            <span>Some One: Dolor sit amet consectetur ...</span>
          </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'sidebarcontacts'
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
