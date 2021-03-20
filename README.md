# vue-2.x-typescript-eslint-prettier
Vueの初期環境構築済みファイル
ESlint, prettireもよしなに設定しました。

## Project setup
git clone後、プロジェクトのルートディレクトリに、.vscodeフォルダを追加し、
settings.jsonに以下を追加してください。

```
{
    "editor.formatOnPaste": true,
    "git.ignoreLimitWarning": true,
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "editor.formatOnSave": true,
}
```

```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
