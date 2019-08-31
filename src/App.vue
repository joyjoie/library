<template>
  <v-app>
    <v-toolbar app class="primary">
      <v-toolbar-title class="headline text-uppercase">
        <span class="font-weight-dark">Library</span>
      </v-toolbar-title>
    </v-toolbar>

    <v-content>
      <input-box></input-box>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import InputBox from '@/components/InputBox.vue';

export default {
  name: 'App',
  components: {
    InputBox,
  },
  data() {
    return {};
  },
};
</script>
