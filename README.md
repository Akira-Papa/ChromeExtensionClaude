

# Claude Send Chrome拡張機能

Claude Sendは、選択したテキストを様々なLLMサービスへ右クリックで簡易的に送信し、様々な処理を行うことができるChrome拡張機能です。

## 機能
- 選択したテキストをClaudeやChatGPTへ送信
- カスタムメニュー項目の追加と編集
- コンテキストメニューから直接LLMサービスへの送信サポート

## インストール方法

### 1. リポジトリのクローン
まず、以下のコマンドを使用してGitHubからプロジェクトをクローンします。

```
git clone https://github.com/Akira-Papa/ChromeExtensionLLM.git
```


### 2. Chromeに拡張機能を追加
1. Chromeを開き、右上のメニューから「その他のツール」>「拡張機能」を選択します。
2. 右上の「デベロッパーモード」を有効にします。
3. 「パッケージ化されていない拡張機能を読み込む」をクリックします。
4. クローンしたリポジトリ内の拡張機能のディレクトリを選択します。

これで、Chromeの拡張機能バーに新しいアイコンが表示され、拡張機能が使用可能になります。

## 使用方法
- テキストを選択し、右クリックメニューから「Claudeへ送信」または「ChatGPTへ送信」を選択します。
- ポップアップから新しいメニュー項目を追加、編集、削除できます。

## 開発者向け情報
- 主要なスクリプト: `scripts/background.js`
- ポップアップUI: `popup.html` と `styles.css`
- 拡張機能の設定: `manifest.json`

## ライセンス
このプロジェクトはMITライセンスの下で公開されています。
