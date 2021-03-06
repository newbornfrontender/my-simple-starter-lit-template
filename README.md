<h1 align="center">Минималистичный стартовый шаблон для проектов на LitElement</h1>

Это простой стартовый шаблон для LitElement (и lit-html), включающий в себя линтер и форматтер кода

> В качестве менеджера пакетов советую использовать [Yarn](https://yarnpkg.com)

> [Как мигрировать с NPM на Yarn](https://yarnpkg.com/docs/migrating-from-npm)

<h2 align="center">Описание</h2>

Проект построен на Rollup с минимумом настроек. Babel используется как CLI инструмент и имеет поддержку декораторов. В качестве лентера используется ESLint с базовой конфигурацией (airbnb конфигурация вынесена в [отдельную ветку](/)). Для форматирования был выбран Prettier. Во избежание попадания в репозиторий непроверенного кода используются husky и lint-staged. Тесты (Karma) присутствуют в [отдельной ветке](/)

<h2 align="center">Список доступных команд</h2>

Ниже представлены команды и способ их запуска

```
$ yarn <название команды>
```

> Описиние в процессе

<table>
  <thead>
    <tr>
      <th>Команда</th>
      <th width="100%">Описание</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>...</code>
      </td>
      <td>...</td>
    </tr>
  </tbody>
</table>

<h2 align="center">ToDo список</h2>

- [ ] Создать базовую конфигурацию шаблона
- [ ] Создать отдельную ветку для [eslint-config-airbnb-base](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb). Исправить ссылку на ветку в описании
- [ ] Создать отдельную ветку для [Karma](https://github.com/karma-runner/karma). Исправить ссылку на ветку в описании

<h2 align="center">Лицензия</h2>

[MIT](/LICENSE)
