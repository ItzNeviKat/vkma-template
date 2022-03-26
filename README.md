<p align="center">
  <a href="https://preactjs.com/" target="blank"><img src="https://raw.githubusercontent.com/preactjs/preact/8b0bcc927995c188eca83cba30fbc83491cc0b2f/logo.svg" width="320" alt="Preact Logo" /></a>
</p>
<p align="center">Fast 3kB alternative to React with the same modern API</p>

## Описание
📍 Шаблон для мини-приложений.

- **⚛️ Preact**. Легковесная альтернатива React.
- **⚡️ Vite**. Быстрый и оптимизированный сборщик.
- **❄️ Typescript**. Строгая типизация.
- **🎯 CSS Modules**. Удобное использование CSS.
- **🚀 ESLint & Prettier**. Форматирование кода.
- **📦 Роутер**. `@itznevikat/router` для удобной навигации.
- **🏁 Стейт менеджер**. `@mntm/precoil` в качестве глобального состояния.
- **⛓ VK Bridge**. `@mntm/painless-bridge` как улучшенную альтернативу стандартному.

## Установка
```bash
$ yarn
```

## Запуск
```bash
# development and watch mode
$ yarn dev

# production mode
$ yarn build && yarn serve
```

## Использование с **VK Tunnel**/**Ngrok**/etc.
В `vite.config.ts` в объекте `server` убираем `https`, `host` и `proxy`, добавляем:
```typescript
hmr: {
  clientPort: 443
}
```
Подробнее - https://github.com/vitejs/vite/discussions/5399.

## Лицензия
[MIT](LICENSE)
