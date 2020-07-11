# Laravel 7 + Vue.js + Tailwind CSS Starter

![Laravel + Vue + Tailwind Logo](https://github.com/d3vkk/laravel-vue-tailwind-starter/blob/master/laravel-vue-tailwind-logo.png)

Laravel 7 + Vue.js + Tailwind CSS Starter. With zero bloat dependencies

What is [Laravel,](https://laravel.com/) [Vue.js](https://vuejs.org/) or [Tailwind CSS?](https://tailwindcss.com/)

## Prerequisites

You should have the following installed
 - [PHP 7.3 or higher](https://php.net/)
 - [Laravel 7](https://laravel.com/)
 - [npm](https://npm.com/) or [yarn](https://yarnpkg.com/)

## Set up

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

© 2020 Donald K • Under MIT License
