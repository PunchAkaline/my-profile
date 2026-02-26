# 個人プロフィールサイト

このリポジトリは [Astro](https://astro.build) で作成した
個人用のポートフォリオ / プロフィールサイトです。

動作確認の際はブラウザのコンソールを開き、`MyIcon loaded successfully` などのログが出ているか確認してください。

## 構成

```
/
├── public/            # 静的アセット (プロフィール画像、PDF など)
├── src
│   ├── components/    # UI コンポーネント
│   │   └── Profile.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

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
