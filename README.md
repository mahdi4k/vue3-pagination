# Vue 3 Pagination

A Vue 3 component for pagination.

## Table of Contents

* [Demo](#demo)
* [Installation](#installation)
* [Getting Started](#getting-started)
  * [Import Component](#import-component)
  * [How to use](#how-to-use)
* [License](#license)
* [Contact](#contact)

## Demo
![Demo](https://raw.githubusercontent.com//julian-printemps/vue3-pagination/master/demo-1.gif)


## Installation

Package is available on NPM: https://www.npmjs.com/package/vue3-pagination

```sh
// with npm
npm install vue3-pagination
```

```sh
// with yarn
yarn add vue3-pagination
```

The component is packaged mainly for use with bundlers, if you require a browser build - post an issue.


## Getting Started

### Import component
```js
import VPagination from "vue3-pagination";
import "vue3-pagination/dist/vue3-pagination.css";

export default {
  ...
  components: {
    VPagination
  }
  ...
}
```

### How to use
```vue
<template>
  <v-pagination
    v-model="page"
    :pages="10"
    :range-size="1"
    active-color="#DCEDFF"
  />
</template>
```

## Props and attributes
Main interaction with the pagination is done via `v-model` with `Number` as expected type of the value passed.

|ID|Type|Default|Description
|---|---|---|---|
|`pages`|`Number`||Total number of pages|
|`rangeSize`|`Number`|1|Number of page around the current page|
|`activeColor`| `String` |#DCEDFF|Background color of the current page|


## License

[MIT](https://opensource.org/licenses/MIT)

Copyright © 2020 - Present, Julian Springaux

## Contact

* [Send me an email 📧](mailto:julian.printemps@gmail.com)
* [Contact me through my website](https://julian-printemps.web.app/)
