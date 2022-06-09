# Laravel 7 + Vue.js + Tailwind CSS Starter

![Laravel + Vue + Tailwind Logo](https://github.com/d3vkk/laravel-vue-tailwind-starter/blob/master/laravel-vue-tailwind-logo.png)

What is [Laravel,](https://laravel.com/) [Vue.js](https://vuejs.org/) or [Tailwind CSS?](https://tailwindcss.com/)

## Prerequisites

You should have the following installed
 - [PHP 7.3 or higher](https://php.net/)
 - [Laravel 7](https://laravel.com/)
 - [npm](https://npm.com/) or [yarn](https://yarnpkg.com/)

## Set up

Fork or clone this repo
```
git clone https://github.com/d3vkk/laravel-vue-tailwind-starter.git
```

Install dependencies with npm or yarn
```bash
npm install
#or
yarn install
```

Compile vue.js & css file and also watch for changes
```
npm run watch
```

Link the css file to a blade file e.g. `./resources/views/welcome.blade.php`
```html
<link href = {{ asset('css/main.css') }} rel = "stylesheet" />
```

Start up server
```
php artisan serve
```

## Contribution

To contribute, [use this guide](https://github.com/d3vkk/open-source/blob/master/CONTRIBUTING.md)

## Usage

Star this repo for future reference

[Open in browser-based Visual Studio Code](https://vscode.dev//github/d3vkk/laravel-vue-tailwind-starter)

Fork or clone this repo
```
git clone https://github.com/d3vkk/laravel-vue-tailwind-starter.git
```

© 2020-present Donald K • Under MIT License
