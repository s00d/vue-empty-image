# vue-empty-image

> A reusable focus directive for reusable [Vue.js](https://github.com/vuejs/vue) components

## Overview

Test images for vue

## Requirements

- vue: ^2.0.0

## Install

From npm:

``` sh
$ npm install vue-empty-image --save
```

## API

### `empty-image`

A directive that binds focus to the expression in a one-way manner,

``` js
import { emptyImage } from 'vue-empty-image';

export default {
  directives: { 'empty-image': emptyImage },
  template: '<img type="text" v-empty-image="200x200">',
};
```

### `mixin`

A mixin that makes the `v-empty-image` directive available to the component under the default name.

``` js
import { mixin as emptyImage }  from 'vue-empty-image';

export default {
  mixins: [ emptyImage ],
  template: '<img type="text" v-empty-image="200x200">',
};
```


## License

[MIT](https://opensource.org/licenses/MIT)