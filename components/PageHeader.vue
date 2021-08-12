<template>
  <div class="page-header" data-parallax="true" style="background-image: url('https://images.unsplash.com/photo-1505373877841-8d25f7d46678?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2500&q=80'); transform: translate3d(0px, 0px, 0px);">
    <div class="filter"></div>
    <div class="content-center">
      <div class="container">
        <div class="motto">
          <h1 class="title">{{title}}</h1>
          <h3 class="description">{{date}}</h3>
          <br>
          <!-- <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" class="btn btn-neutral btn-round"><i class="fa fa-play"></i>Watch video</a> -->

          <button type="button" class="btn btn-outline-neutral btn-round">Info Below</button>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  export default {
    props: {
      title: {type: String, default: 'Landing page'},
      date: {type: String, default: 'Date'},
      urlLink: {type: String, required: true}
      },
  }
</script>
