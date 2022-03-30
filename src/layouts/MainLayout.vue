<template>
  <q-layout view="hHh lpR fFf">
    <q-header elevated class="bg-primary text-white" height-hint="98">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg" />
          </q-avatar>
          Nizo web Solutions
        </q-toolbar-title>
        <div class="q-mx-xs">
          <q-icon size="xl" name="call" />
        </div>
        <h6 class="q-my-none">Call Now +25575336698</h6>
      </q-toolbar>

      <q-tabs align="center" class="bg-secondary">
        <q-route-tab to="/" label="Home" class="q-px-lg q-mx-lg" />
        <q-route-tab to="/about" label="About" class="q-px-lg q-mx-lg" />
        <div class="dropdown">
          <q-btn-dropdown
            auto-close
            stretch
            flat
            label="More..."
            class="dropbtn"
          >
            <q-list class="dropdown-content">
              <q-item clickable @click="tab = 'movies'">
                <q-item-section>Movies</q-item-section>
              </q-item>

              <q-item clickable @click="tab = 'photos'">
                <q-item-section>Photos</q-item-section>
              </q-item>
            </q-list>
          </q-btn-dropdown>
        </div>
      </q-tabs>
    </q-header>

    <q-page-container>
      <!--
      <q-carousel
        animated
        v-model="slide"
        navigation
        infinite
        :autoplay="autoplay"
        arrows
        transition-prev="slide-right"
        transition-next="slide-left"
        @mouseenter="autoplay = false"
        @mouseleave="autoplay = true"
      >
        <q-carousel-slide :name="1" img-src="~assets/mountains.jpg" />
        <q-carousel-slide :name="2" img-src="~assets/parallax1.jpg" />
        <q-carousel-slide :name="3" img-src="~assets/parallax2.jpg" />
        <q-carousel-slide :name="4" img-src="~assets/quasar.jpg" />
      </q-carousel>
-->
      <router-view />
    </q-page-container>
  </q-layout>
</template>
<style>
</style>