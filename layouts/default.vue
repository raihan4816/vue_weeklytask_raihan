<template>
  <v-app light>
    <v-navigation-drawer
      v-model="drawer"
      :mini-variant="miniVariant"
      :clipped="clipped"
      fixed
      app
    >
      <v-list>
        <v-list-item
          v-for="(item, i) in items"
          :key="i"
          :to="item.to"
          router
          exact
        >
          <v-list-item-action>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title v-text="item.title" />
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-app-bar :clipped-left="clipped" fixed app>
      <v-app-bar-nav-icon @click.stop="drawer = !drawer" />
      <v-toolbar-title>Vue JS Kelas A</v-toolbar-title>
      <v-spacer />
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <v-navigation-drawer v-model="rightDrawer" :right="right" temporary fixed>
      <v-list>
        <v-list-item @click.native="right = !right">
          <v-list-item-action>
            <v-icon light> mdi-repeat </v-icon>
          </v-list-item-action>
          <v-list-item-title>Switch drawer (click me)</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-footer :absolute="!fixed" app>
      <span><span>Altera Academy Batch 2 - Understanding Everything About Vue JS - Frontend Engineer </span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: true,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Homepage',
          to: '/',
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Section 2',
          to: '/section2',
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Section 3',
          to: '/section3',
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Section 4',
          to: '/section4',
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Section 5',
          to: '/section5',
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Section 6',
          to: '/section6',
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Section 7',
          to: '/section7',
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Section 8',
          to: '/section8',
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Section 9',
          to: '/section9',
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Section 10',
          to: '/section10',
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Section 11',
          to: '/section11',
        },
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js',
    }
  },
}
</script>
