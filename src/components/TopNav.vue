<template>
    <q-header elevated class="bg-primary text-white" height-hint="98">
      <q-toolbar>
        <q-toolbar-title class="toolbarTitle ">
            <q-avatar>
                <img src="../assets/cj.jpg">
            </q-avatar>
          Carly & James
        </q-toolbar-title>
      </q-toolbar>

      <q-tabs align="left">
        <q-route-tab to="/page1" label="Page One" />
        <q-route-tab to="/page2" label="Page Two" />
        <q-route-tab to="/page3" label="Page Three" />
      </q-tabs>
    </q-header>

</template>
<script>
export default {
  name: 'TopNav',
  data() {
      return {
          'tab': ''
      }
  }
}

</script>

<style>
.toolbarTitle {
    text-align: center;
}

</style>
