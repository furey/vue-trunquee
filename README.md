# Vue Trunquee

![Trunquee Demo](https://i.imgur.com/rggXkO7.gif)

A truncated marquee component for [Vue.js](http://vuejs.org/).

`Trunquee.vue` truncates text wider than its container, with a marquee reveal on mouse enter.

## Vue Component Source

See: [`/src/components/Trunquee.vue`](/src/components/Trunquee.vue)

## Props

| Name     | Type   | Description                                 |
| :---     | :---   | :---                                        |
| `text`   | String | Text to truncate (required)                 |
| `speed`  | Number | Marquee speed in milliseconds (default: 85) |
| `cursor` | String | CSS cursor on hover (default: 'help')       |

## Usage

See: [`/src/Demo.vue`](/src/Demo.vue)

## Demo

``` bash
npm install
npm run serve
```
