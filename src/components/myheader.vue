<template>
    <div>
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item>
           <router-link class="text-white px-3" to="/">home</router-link>
        </b-nav-item>
        <b-nav-item>
           <router-link class="text-white px-3" to="/test1">test1</router-link>
        </b-nav-item>
        <b-nav-item>
           <router-link class="text-white px-3" to="/test2">test2</router-link>
        </b-nav-item>
        <b-nav-item>
           <router-link class="text-white px-3" to="/test3">test3</router-link>
        </b-nav-item>
      </b-navbar-nav>
      </b-collapse>
  </b-navbar>
    </div>
</template>

