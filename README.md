# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └── astro.svg
│   ├── components
│   │   └── Welcome.astro
│   ├── content/           # 📚 Markdown документация
│   │   ├── config.ts      # Content Collections конфигурация
│   │   └── docs/          # Вашите .md файлове тук
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       ├── docs/
│       │   ├── index.astro      # Списък с документи
│       │   └── [...slug].astro  # Dynamic routing за документи
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 📚 Документация

Този проект е настроен като docs сайт с Astro Content Collections.

### Добавяне на нов документ

1. Създайте нов `.md` файл в `src/content/docs/`
2. Добавете frontmatter в началото:

```markdown
---
title: "Заглавие на документа"
description: "Кратко описание"
date: 2025-10-14
author: "Вашето име"
tags: ["tag1", "tag2"]
---

# Вашето съдържание тук

Пишете Markdown както обикновено...
```

3. Документът автоматично ще се появи на `/docs`
4. Ще бъде достъпен на `/docs/име-на-файла`

### Преглед на документацията

- Всички документи: http://localhost:4321/docs
- Конкретен документ: http://localhost:4321/docs/example

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
