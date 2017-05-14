## Visual Studio Code 導入メモ

Microsoft社製のVisual Studio Code(以下、VS Cocde)

フリー

#### インストール

https://code.visualstudio.com/

よりDLし普通にインストール


#### 初期設定

VS Codeを起動し、
ファイルメニュー → 基本設定 → 設定

左側ペインはカスタマイズ可能な項目とデフォルト値が表示されている。(編集不可)
これを参考に右側ペインに設定を定義(上書き)していく。

以下は、


```json
{
  "http.proxy": "",
  "typescript.check.tscVersion": false,
  "editor.tabSize": 2,
  "editor.detectIndentation": false,
  "editor.renderWhitespace": "all",
}
```

#### プラグインのインストール

- Angular2 TypeScript Emmet
- Angular2,4 and upcoming latest TypeScipt HTML Snippets
- Angular2 + Snippets
- Angular2 Comonent Generator
- angular2-inlne
- AngularDoc for VS Code
- Document This(customize-tags)
- TSLint
- type-doc-vscode
- TypeScript Toolbox

- Auto Close Tag
- Color Highlight
- Color Pikcker
- Indenticator
- Whitespace++
- zankaku

- Markdown Table Prettifer
- Eclipse Keymap
- Start git-bash
- Git History
- Degger for Chrome
