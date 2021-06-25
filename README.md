# Boilerplate for Vue 3 with Vite and Bootstrap 5 with Icons

## Table of Contents

1. [Enviroment](enviroment)
    1. [Pre requirements](#pre-requirements) - [Node JS and NPM](#node-js-and-npm) - [Vue JS v3, SFC and Vue CLI](#vue-js-v3-sfc-and-vue-cli)
    2. [Dependences](#dependences) - [Vite](#vite) - [Vue router](#vue-router) - [Bootstrap 5, Bootstrap Icons and Proper](#bootstrap-5-bootstrap-icons-and-proper) - [Sass](#sass)
    3. [Install and Run](#install-and-run)
2. [Boilerplate](boilerplate)
3. [Source code](source-code)
4. [License](license)

## Setup the enviroment

### Pre requirements

Ако знаете какво е [Node JS] и [NPM] преминете на [Dependences](#dependences), ако не - ще спомена на кратко за какво да направите, ако все още не сте ги инсталирали.

#### Node JS and NPM

На сайта на [Node JS] може да изтеглите инсталционния пакет. Най-добре е да гледате **LTS** (Long Term Support) версията. Следвайте стъпките на инсталатора и след приключване проверете в конзолата, дали всичко е добре.

1. Проверка на версията на Node JS

```sh
node -v
```

2. Проверка на версията на NPM

```sh
npm -v
```

#### Vue JS v3, SFC and Vue CLI

[Vue JS v3] е основния framework, който ползвам в моя темплейт и трябва да го имате инсталиран. За да го добавите ще използваме [NPM]. Заедно с Vue 3 ще добавим и **SFC** (Single File Components) инструмента, който заменя **_vue-template-compiler_** плъгина. Накрая ще добавим и \*Vue **CLI\***.

1. Инсталиране на Vue 3

```sh
npm install vue@next
```

2. Инсталиране на SFC

```sh
npm install -D @vue/compiler-sfc
```

2. Инсталиране на Vue CLI

```sh
npm install -g @vue/cli
```

### Dependences

Това са основните пакети в темплейта. Те оформят постановка, от която може да започнете да разработвате свой собствен проект.

В моите проекти използвам [Bootstrap] и в темплейта го залагам, като основен **_front-end faramework_**. Добавям и [Sass], като предпроцесор на **CSS** файловете, за да имам по-голяма свобода на управлението им.

Използвам [Vite] за настройки на средата за разработка. Може да ползвате и [Vue CLI], особено за по-малки проекти с не много бъндъли.

Добавям и [Vue Router]. Това е неделима част от всеки web проект и за мен е задължителен.

#### Vite

Започваме с инициализация на проекта ни с **Vite** темплейт. За целта в конзолата напишете:

```sh
npm init @vitejs/app
```

В следващите стъпки окажете следните данни:

```sh
Project name: vue3-bootstrap5-boilerplate
```

```sh
Select a framework: vue
```

```sh
Select a variant: vue
```

```sh
cd vue3-bootstrap5-boilerplate
```

Повече информация за **Vite** инсталацията може да видите на адрес: https://vitejs.dev/guide/#scaffolding-your-first-vite-project

Ако използвате [Visual Studio Code] в този момент може да го стартирате и да изпълните последващите команди от неговата конзола. Ако не го ползвате - може и от конзолата на операционната система. **Visual Studio Code** се стартира със следната команда:

```sh
code .
```

#### Vue router

За инсталацията можете да видите информация на адрес: https://next.router.vuejs.org/installation.html

```sh
npm install vue-router@4
```

#### Bootstrap 5, Bootstrap Icons and Proper

Следва добавянето на Bootstrap 5 (https://getbootstrap.com/docs/5.0/getting-started/download/#npm),

```sh
npm install bootstrap
```

Bootstrap Icons (https://icons.getbootstrap.com/)

```sh
npm i bootstrap-icons
```

Накрая добавяме [Proper JS] библиотеката, за да използваме възможностите на **Bootstrap** за визуализиране на **_Tooltips_**, **_Popover_** и др.

```sh
npm i @popperjs/core
```

#### Sass

Последно, но не и по значение, добавяме поддръжката на **Sass**. Използвам го само по време на разработката и затова го добавяме, като `--save-dev` към темплейта.

```sh
npm install sass --save-dev
```

### Install and Run

Приключи инициализацията на темплейта и остана да заредим всички модули и да го стартираме. В конзолата изпълняваме последователно:

```sh
npm install
```

```sh
npm run dev
```

Ще се зареди стартовия проект **Hello Vue 3 + Vite** на http://localhost:3000/

## License

MIT

[Back to top](#table-of-contents)

[//]: # "Links Reference"
[node js]: http://nodejs.org
[npm]: https://www.npmjs.com/
[vue js v3]: https://v3.vuejs.org/
[bootstrap]: https://getbootstrap.com/
[sass]: https://sass-lang.com/
[vite]: https://vitejs.dev/
[vue cli]: https://cli.vuejs.org/
[vue router]: https://next.router.vuejs.org/
[visual studio code]: https://code.visualstudio.com/
[proper js]: https://popper.js.org/
