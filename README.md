# Introduction
A mixin that gives ability to have multiple active draggable dialogs

# Quick start

`npm install --save vuetify-multiple-draggable-dialogs`

Then you need to import that mixin and pass it into Vue:

```javascript
import Vue from 'vue';
import mixins from 'vuetify-multiple-draggable-dialogs';

Vue.mixin(mixins);
```

So far as I use Vuetify with Nuxt I store this code in /plugins/settings.js
Don't forget to include it in nuxt.config.js. Please see [here](https://nuxtjs.org/docs/2.x/directory-structure/plugins);

Then somewhere in your Vue layout:
```javascript
<template>

</template>

<script>
export default {
  mounted() {
    // enable using draggable dialogs
    this.activateMultipleDraggableDialogs();
  }
};
</script>

```
