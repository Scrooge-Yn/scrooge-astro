- [Structure](#Structure)
- [Commands](#Commands)

## 🚀 Structure
```
/
├── public/           //资源文件
│   └── favicon.svg
├── src/
│   ├── components/   //组件
│   │   └── Card.astro
│   ├── layouts/      //布局组件
│   │   └── Layout.astro
│   └── pages/        //页面文件
│       └── index.astro
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                             |
| :--------------------- | :------------------------------------------------- |
| `npm install`          | Installs dependencies                              |
| `npm run dev`          | Starts local dev server at `localhost:3000`        |
| `npm run build`        | Build your production site to `./dist/`            |
| `npm run preview`      | Preview your build locally, before deploying       |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro preview` |
| `npm run astro --help` | Get help using the Astro CLI                       |
