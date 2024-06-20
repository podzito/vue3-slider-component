![banner](https://github.com/s-sasaki-0529/vue-slider-component/blob/master/.github/banner.jpg?raw=true)

[![license](https://img.shields.io/npm/l/express.svg)]()

> 🎚 A highly customized slider component

## Forked from [s-sasaki-0529/vue-slider-component](https://github.com/s-sasaki-0529/vue-slider-component)

This repository is forked from [s-sasaki-0529/vue-slider-component](https://github.com/s-sasaki-0529/vue-slider-component) which in turn is a fork from [NightCatSame/vue-slider-component](https://github.com/NightCatSama/vue-slider-component) (v3.2.10) and rewritten to work with Vue 3.

Please note that this fork is work in progress, so some links may still point to the work that _s-sasaki-0529_ has done.

## 🎯 install

```bash
$ yarn add @podzito/vue3-slider-component
# npm install @podzito/vue3-slider-component --save
```

## ✨ Features

- 🛠️ More customizable
- 🐳 Support for more sliders
- 📌 Add marks

## 📚 Documentation

[Storybook](https://vue3-slider-component.netlify.app/?path=/docs/vue3-slider-component--vue3-slider-component)

## 🚀 Usage

```vue
<script setup lang="ts">
import { ref } from 'vue'
import VueSlider from '@podzito/vue3-slider-component'

const value = ref(0)
</script>

<template>
  <div>
    <VueSlider v-model="value" />
    <p>Value: {{ value }}</p>
  </div>
</template>
```

Also available in the Options API

```vue
<template>
  <VueSlider v-model="value" />
</template>

<script>
import VueSlider from '@podzito/vue3-slider-component'

export default {
  components: {
    VueSlider,
  },
  data() {
    return {
      value: 0,
    }
  },
}
</script>
```

## License

Licensing is in accordance with the original.

[MIT](https://github.com/NightCatSama/vue-slider-component/blob/master/LICENSE)
