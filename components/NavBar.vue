<template>
<div class="nav-holder">
      <div class="nav">
        <nuxt-link to="/" class="brand">Ellis Dev</nuxt-link>
        <nav>
          <nuxt-link to="/">home</nuxt-link>&nbsp;|
          <nuxt-link to="/about">about</nuxt-link>
        </nav>
      </div>
</div>

    </template>
    
    <style scoped>
    .brand {
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
      font-size: 1.5em;
      color: #fff;
      text-decoration: none;
    }
    .nav-holder {
      position: fixed;
      width: 100%;
      padding: 0 30px;
    }
    .nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      height: 60px;
    }
    .nav .nav-item {
      box-sizing: border-box;
      margin: 0 5px;
      color: rgba(0, 0, 0, 0.5);
      text-decoration: none;
    }
    .nav .nav-item.router-link-exact-active {
      color: #fff;
      border-bottom: solid 2px #39b982;
    }
    .nav a {
      display: inline-block;
      color: #fff;
    }

    nav {
      color: #fff;
    }
    </style>