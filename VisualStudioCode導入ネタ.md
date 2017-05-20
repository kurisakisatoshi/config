# Visual Studio Code 導入メモ

Microsoft社製のVisual Studio Code(以下、VS Cocde)

フリー

### インストール

https://code.visualstudio.com/

よりDLし普通にインストール


### 初期設定

VS Codeを起動し、
ファイルメニュー → 基本設定 → 設定

左側ペインはカスタマイズ可能な項目とデフォルト値が表示されている。(編集不可)
これを参考に右側ペインに設定を定義(上書き)していく。

以下は、


```json
{
  "http.proxy": "",
  "update.channel": "none",
  "typescript.check.tscVersion": false,
  "editor.tabSize": 2,
  "editor.detectIndentation": false,
  "editor.renderWhitespace": "all",
  "editor.formatOnSave": true,
  "editor.rulers": [
    140
  ],
  "files.encoding": "utf8",
  "files.eol": "\n",
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "[markdown]": {
    "editor.wordWrap": "on",
    "editor.quickSuggestions": false,
    "files.trimTrailingWhitespace": false
  }
}
```

### プラグインのインストール

#### TypeScript関係

- Document This(customize-tags)
- TSLint
- type-doc-vscode
- TypeScript Toolbox
- Sort Typescript imports
- jon2ts

#### Angular2関係

- Angular2,4 and upcoming latest TypeScipt HTML Snippets
- Angular2 + Snippets
- Angular2 Comonent Generator
- angular2-inlne
- Angular2 TypeScript Emmet ・・・ インストールしなくてもいいかも
- AngularDoc for VS Code

#### ユーティリティ関係

- json2ts
- stylelint
- npm
- Prettify JSON

#### ユーティリティ関係その２

- Project Manager
- Auto Close Tag
- Color Highlight
- Color Pikcker
- Indenticator
- Whitespace++
- zankaku


#### 完全に好み(必須ではない)

- Markdown Table Prettifer
- Eclipse Keymap
- Start git-bash
- Git History
- Degger for Chrome


---
俺の設定

```json
{
  //"http.proxy": "",
  "update.channel": "none",
  "typescript.check.tscVersion": false,
  "editor.fontSize": 16,
  "editor.tabSize": 2,
  "editor.detectIndentation": false,
  "editor.renderWhitespace": "all",
  "editor.folding": false,
  "editor.formatOnSave": true,
  "editor.rulers": [
    140
  ],
  "files.encoding": "utf8",
  "files.eol": "\n",
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "files.autoSave": "afterDelay",
  "telemetry.enableTelemetry": false,
  "telemetry.enableCrashReporter": false,
  "window.menuBarVisibility": "default",
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "workbench.welcome.enabled": false,
  "[markdown]": {
    "editor.wordWrap": "on",
    "editor.quickSuggestions": false,
    "files.trimTrailingWhitespace": false
  }
}

```
