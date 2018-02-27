<template>
  <nav class="navbar-default navbar-static-side" role="navigation">
    <div class="sidebar-collapse">
      <ul class="nav metismenu" id="side-menu">
        <li class="nav-header">
          <div class="dropdown profile-element"> <span>
            <img alt="image" class="img-circle" :src="profile">
          </span>
          <a data-toggle="dropdown" class="dropdown-toggle" href="#">
            <span class="clear"> <span class="block m-t-xs"> <strong class="font-bold">{{ user_name }}</strong>
            </span> <span class="text-muted text-xs block">{{ user_role }}</span> </span> </a>
            <!-- <ul class="dropdown-menu animated fadeInRight m-t-xs">
            <li><a href="profile.html">Profile</a></li>
            <li><a href="contacts.html">Contacts</a></li>
            <li><a href="mailbox.html">Mailbox</a></li>
            <li class="divider"></li>
            <li><a href="login.html">Logout</a></li>
          </ul> -->
        </div>
        <div class="logo-element">
          IN+
        </div>
      </li>
      <!-- <li>
      <a href="#"><i class="fa fa-sitemap"></i> <span class="nav-label">Menu Levels </span><span class="fa arrow"></span></a>
      <ul class="nav nav-second-level collapse">
      <li>
      <a href="#">Third Level <span class="fa arrow"></span></a>
      <ul class="nav nav-third-level collapse">
      <li>
      <a href="#">Third Level Item</a>
    </li>
    <li>
    <a href="#">Third Level Item</a>
  </li>
  <li>
  <a href="#">Third Level Item</a>
</li>

</ul>
</li>
<li><a href="#">Second Level Item</a></li>
<li>
<a href="#">Second Level Item</a></li>
<li>
<a href="#">Second Level Item</a></li>
</ul>
</li> -->
<li>
  <router-link class="fa fa-magic" to="/login">
    <span class="nav-label">Login</span>
  </router-link>
</li>
<li>
  <router-link class="fa fa-magic" to="/">
    <span class="nav-label">Teacher</span>
    <span class="label label-info pull-right">12</span>
  </router-link>
</li>
<!-- <li class="landing_link">
<a target="_blank" href="landing.html"><i class="fa fa-star"></i> <span class="nav-label">Landing Page</span> <span class="label label-warning pull-right">NEW</span></a>
</li>
<li class="special_link">
<a href="package.html"><i class="fa fa-database"></i> <span class="nav-label">Package</span></a>
</li> -->
</ul>

</div>
</nav>
</template>

<script>

export default {
  data () {
    return {
      user_name: 'Angel Suarez',
      user_role: 'Nursury teacher',
      profile: require('../assets/logo.png')
    }
  }
}
</script>

<style scoped>
    p{
      color: white;
    }
    .profile-element img {
      width: 4em;
    }
</style>
