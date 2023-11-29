---
group: 'top'
icon: 'carbon:bookmark'
---

<img src="https://raw.githubusercontent.com/woolimi/wool-components/master/assets/sheep.svg" alt="Wool Components" class="mx-auto w-[300px] h-[300px]" />

<h1 class="text-center text-5xl">Wool Components</h1>
<p class="text-2xl text-center">
	<span class="font-extrabold">FUCKING NOISY BUT CUTE<span><br/> Vue UI components library
</p>

<br/>
<br/>

<h2 class="text-4xl">🐑 Getting Started</h2>

## 1. Download

```bash
yarn add wool-components@latest
```

## 2. Import `index.css` file in `main.ts`

```js
import { createApp } from 'vue';
import App from './App.vue';
import 'wool-components/dist/index.css';

createApp(App).mount('#app');
```

## 3. Import component

```vue
<script setup>
import { WButton } from 'wool-components';
</script>
```