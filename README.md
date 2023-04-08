# Count Animation Vue

## Introduction
The Animated Number Library is a JavaScript library for animating numbers in VueJS 3 applications. It provides a simple way to animate a number from one value to another with a smooth transition.

### Installation
```bash
npm install count-animation-vue
```

### Usage
To use the Animated Number Library, you need to import the **`CountAnimation`** component from the library and use it in your VueJS 3 application.

```js
import { createApp } from 'vue'
import CountAnimationVue from 'count-animation-vue'

const app = createApp(App)
app.use(CountAnimationVue)
```

Here's an example:
``` vue
<template>
  <div>
    <CountAnimation :value="100" />
  </div>
</template>
```

And you can also set the **`start`** number and animation **`duration`** in milliseconds

``` vue
<template>
  <div>
    <CountAnimation :start="10" :value="100" :duration="1000" />
  </div>
</template>
```
In this example, the AnimatedNumber component will animate the number from 10 to 100 with an animation time of 1000 milliseconds.

### Props
| Name     | Type   | Default | Description                            |
|----------|--------|---------|----------------------------------------|
| start    | Number | 0       | The initial number                     |
| value    | Number | 1000    | The final number                       |
| duration | Number | 500     | The animation duration in milliseconds |


### Contributing

If you want to contribute to the animated numbers library, you can sponsor via links in the specified GitHub repository: https://github.com/mkbek/count-animation-vue.

License The Animated Number Library is licensed under the [MIT License](./LICENSE).