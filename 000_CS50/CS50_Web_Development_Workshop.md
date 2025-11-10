# CS50 Web開発ワークショップ - HTML/CSS/JavaScript入門

## 概要
- **対象**: 高校生
- **時間**: 2時間（120分）
- **目的**: HTML/CSS/JavaScriptの基本的な構造を理解し、それぞれ何ができるのかを理解する

---

## タイムテーブル

| 時間 | 内容 | 所要時間 |
|------|------|---------|
| 0:00 - 0:10 | 事前準備 | 10分 |
| 0:10 - 0:50 | HTML入門 | 40分 |
| 0:50 - 1:00 | **休憩** | **10分** |
| 1:00 - 1:50 | CSS/JavaScript入門 | 50分 |
| 1:50 - 2:00 | まとめ・質疑応答 | 10分 |
| (余裕があれば) | Geolocationデモ | - |

---

## アジェンダ

### 1. 事前準備（10分）

#### 必要なもの
- パソコン（Windows/Mac）
- Visual Studio Code
- インターネット接続

#### 準備手順

**方法1: VS Code を使う方法（推奨）**

1. **教材ファイルのダウンロード**
   - 以下のリンクからzipファイルをダウンロード
   - 📥 [https://cdn.cs50.net/2024/fall/lectures/8/src8.zip](https://cdn.cs50.net/2024/fall/lectures/8/src8.zip)
   - ダウンロードしたzipファイルを解凍

2. **VS Codeで開く**
   - Visual Studio Codeを起動
   - 解凍したフォルダを開く
   - ファイル → フォルダーを開く → `src8`フォルダを選択

**方法2: VS Codeの操作が難しい場合**

- ブラウザで直接アクセス
- 🌐 [https://cdn.cs50.net/2024/fall/lectures/8/src8/](https://cdn.cs50.net/2024/fall/lectures/8/src8/)
- ファイルをクリックして内容を確認できます
- HTMLファイルをブラウザで開いて動作確認が可能

---

### 2. HTML入門（40分）

#### 目標
- HTMLの基本構造を理解する
- よく使うHTMLタグを学ぶ
- 簡単なWebページを作成する

#### 進行方法
- **参考資料**: [CS50 Lecture 8 - HTML](https://cs50.harvard.edu/x/notes/8/#html)
- この資料に沿って進めていきます

#### 学習内容
- HTMLとは何か
- 基本的なHTML文書の構造（`<!DOCTYPE>`, `<html>`, `<head>`, `<body>`）
- よく使うタグ
  - 見出し（`<h1>`〜`<h6>`）
  - 段落（`<p>`）
  - リンク（`<a>`）
  - 画像（`<img>`）
  - リスト（`<ul>`, `<ol>`, `<li>`）
  - テーブル（`<table>`, `<tr>`, `<td>`）
  - フォーム（`<form>`, `<input>`, `<button>`）

#### 実習例
- シンプルなWebページの作成
- リンクと画像の追加
- フォームの作成

---

### 3. 休憩（10分）

💡 **休憩時のポイント**
- 軽くストレッチ
- 質問がある方は講師に声をかけてください
- 進捗が遅れている方はサポートします

---

### 4. CSS/JavaScript入門（50分）

#### 目標
- CSSでWebページをデザインする方法を学ぶ
- JavaScriptでWebページに動きをつける方法を学ぶ

#### 進行方法
- **参考資料**: [CS50 Lecture 8 - CSS](https://cs50.harvard.edu/x/notes/8/#css)
- この資料に沿って進めていきます

#### CSS学習内容（20分）
- CSSとは何か
- CSSの適用方法
  - インラインスタイル
  - `<style>`タグ
  - 外部CSSファイル
- 基本的なスタイリング
  - 色（`color`, `background-color`）
  - フォント（`font-size`, `font-family`）
  - レイアウト（`margin`, `padding`, `border`）
  - セレクタ（タグ、クラス、ID）

#### JavaScript学習内容（30分）
- JavaScriptとは何か
- 変数と関数
- DOMの操作
- イベント処理（クリック、入力など）
- 簡単なインタラクティブな機能の実装

#### 実習例
- HTMLページにCSSでスタイルを追加
- ボタンをクリックすると動作するJavaScriptの実装
- フォームの入力検証

---

### 5. まとめ・質疑応答（10分）

#### 振り返り
- HTMLはWebページの**構造**を作る
- CSSはWebページの**見た目**を作る
- JavaScriptはWebページに**動き**をつける

#### 次のステップ
- CS50の他の講義を視聴
- 自分でWebページを作ってみる
- より高度なフレームワーク（React, Vue.jsなど）の学習

---

## 【時間が余った場合】Geolocationデモ

#### 概要

JavaScriptのGeolocation APIを使って、現在地を取得するデモ

#### 使用するファイル

- **注意:** src8フォルダにはgeolocation.htmlは含まれていません
- 代わりに、以下のオンラインデモを使用してください
- 📍 [Geolocation Demo](https://cdn.cs50.net/2023/fall/lectures/8/src8/geolocation.html)

#### デモの進め方

1. **ブラウザでリンクを開く**
   - 上記のリンクをブラウザで開く
   - 位置情報の許可を求められる

2. **位置情報の許可**
   - 「許可」をクリック
   - 現在地の緯度・経度が表示される

3. **説明のポイント**
   - ブラウザのAPIを使った実用的な機能
   - スマートフォンアプリでよく使われる技術
   - プライバシーとパーミッションの重要性
   - ユーザーの許可なしには使えない

#### トーキングポイント

- 「今までに地図アプリ使ったことある人？」
- 「あれもJavaScriptで作られています」
- 「navigator.geolocationというブラウザの機能を使います」
- 「必ずユーザーの許可が必要です（プライバシー保護）」

#### 発展的な使い方の紹介

- Google Maps APIと組み合わせて地図表示
- 近くのお店を探す機能
- 天気情報の取得
- 位置情報ゲーム（ポケモンGOなど）

---

## 参考リンク

### CS50公式リソース
- [CS50x 2024 - Lecture 8](https://cs50.harvard.edu/x/2024/weeks/8/)
- [CS50 Lecture 8 Notes](https://cs50.harvard.edu/x/notes/8/)
- [CS50 Source Code (2024)](https://cdn.cs50.net/2024/fall/lectures/8/src8.zip)

### 追加学習リソース
- [MDN Web Docs - HTML](https://developer.mozilla.org/ja/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/ja/docs/Web/CSS)
- [MDN Web Docs - JavaScript](https://developer.mozilla.org/ja/docs/Web/JavaScript)

### 参考アプリ
- [カウンターアプリ（デモ）](https://ylearning86.github.io/counter-app/counter.html)
  - HTML、CSS、JavaScriptを使ったシンプルなカウンターアプリ
  - +1/-1ボタンでカウントを変更、リセットボタンで0に戻す
  - DOM操作とイベント処理の実例
  - ソースコード: [GitHub](https://github.com/ylearning86/counter-app)

---

## 講師向け詳細ガイド

### 事前準備チェックリスト

#### 環境準備
- [ ] プロジェクター/画面共有の確認（解像度調整）
- [ ] サンプルファイルのダウンロード確認（`src8.zip`）
- [ ] 参加者全員がVS Codeをインストール済みか確認
- [ ] ブラウザの準備（Chrome推奨）
- [ ] インターネット接続の確認（Wi-Fi情報の共有）
- [ ] VS Code拡張機能「Live Server」のインストール確認

#### 配布資料
- [ ] タイムテーブルの印刷・共有
- [ ] ダウンロードリンクの短縮URL準備
- [ ] 代替サイトURL（https://cdn.cs50.net/2024/fall/lectures/8/src8/）の共有
- [ ] 参考リソース一覧の準備

---

### セクション別トーキングポイント

#### 【導入】事前準備（10分）

**トーキングポイント:**
1. **アイスブレイク（2分）**
   - 「Webサイトを見たことがある人？」→全員挙手
   - 「Webサイトを作ったことがある人？」→少数挙手
   - 「今日は皆さんもWeb開発者になります！」

2. **今日の目標説明（3分）**
   - HTML = 家の骨組み（構造）
   - CSS = 家の内装（デザイン）
   - JavaScript = 家の家電（動き）
   - 「この3つでWebサイトは作られています」

3. **環境セットアップ（5分）**
   - 画面共有でダウンロード手順を見せる
   - VS Codeが難しい人は代替サイトを案内
   - 全員が準備できるまで待つ（TAがサポート）

**デモの進め方:**
- ゆっくり画面を共有しながら操作
- 「皆さん、ついてきていますか？」と定期的に確認
- 進捗が遅い人には個別サポート

---

#### 【メインパート1】HTML入門（40分）

**使用するファイル:**
- `src8/hello0.html` - 最初のHTMLファイル
- `src8/headings.html` - 見出しのデモ
- `src8/paragraphs.html` - 段落のデモ
- `src8/link0.html`, `src8/link1.html` - リンクのデモ
- `src8/image.html` - 画像のデモ
- `src8/list0.html`, `src8/list1.html` - リストのデモ
- `src8/table.html` - テーブルのデモ

**トーキングポイント:**

1. **HTMLとは？（5分）**
   - 「HyperText Markup Language」
   - マークアップ = 「印をつける」
   - 例：新聞記事の見出し、本文、画像のように構造化
   - 「ブラウザはHTMLを読んで表示します」

2. **最初のHTMLファイル（10分）**
   - **ファイル:** `src8/hello0.html` を開く
   - [オンライン版](https://cdn.cs50.net/2024/fall/lectures/8/src8/hello0.html)
   ```html
   <!DOCTYPE html>
   <html lang="ja">
   <head>
       <title>Hello, World!</title>
   </head>
   <body>
       Hello, World!
   </body>
   </html>
   ```
   
   **説明のポイント:**
   - `<!DOCTYPE html>` = 「これはHTML文書ですよ」という宣言
   - `<html>` = すべてを包む大きな箱
   - `<head>` = 裏側の情報（タイトル、設定など）
   - `<body>` = 実際に表示される部分
   - タグは必ず開始と終了がセット（`<tag>...</tag>`）

3. **見出しと段落（5分）**
   - **ファイル:** `src8/headings.html` と `src8/paragraphs.html` を開く
   - [見出しのデモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/headings.html)
   - [段落のデモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/paragraphs.html)
   
   ```html
   <h1>大見出し</h1>
   <h2>中見出し</h2>
   <h3>小見出し</h3>
   <p>これは段落です。</p>
   ```
   
   **説明のポイント:**
   - h1が一番大きい（重要）、h6が一番小さい
   - SEO的にh1は1つだけが推奨
   - pタグで段落を作る

4. **リンクと画像（10分）**
   - **ファイル:** `src8/link0.html`, `src8/link1.html`, `src8/image.html` を開く
   - [リンクのデモ1](https://cdn.cs50.net/2024/fall/lectures/8/src8/link0.html)
   - [リンクのデモ2](https://cdn.cs50.net/2024/fall/lectures/8/src8/link1.html)
   - [画像のデモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/image.html)
   
   ```html
   <a href="https://cs50.harvard.edu">CS50のサイト</a>
   <img src="cat.jpg" alt="かわいい猫">
   ```
   
   **説明のポイント:**
   - `<a>` = anchor（錨）、リンクを作る
   - `href` = どこに飛ぶか
   - `<img>` = 画像、閉じタグ不要
   - `alt` = 画像が表示されない時の代替テキスト（アクセシビリティ重要）

5. **リストとテーブル（10分）**
   - **ファイル:** `src8/list0.html`, `src8/list1.html`, `src8/table.html` を開く
   - [リストのデモ1](https://cdn.cs50.net/2024/fall/lectures/8/src8/list0.html)
   - [リストのデモ2](https://cdn.cs50.net/2024/fall/lectures/8/src8/list1.html)
   - [テーブルのデモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/table.html)
   
   ```html
   <ul>
       <li>項目1</li>
       <li>項目2</li>
   </ul>
   
   <table>
       <tr>
           <td>セル1</td>
           <td>セル2</td>
       </tr>
   </table>
   ```
   
   **説明のポイント:**
   - `<ul>` = 順序なしリスト（箇条書き）
   - `<ol>` = 順序付きリスト（番号付き）
   - テーブルは行（`<tr>`）とセル（`<td>`）で構成

**デモの進め方:**
- Live Serverで実際の表示を見せながら進める
- コードを書く → 保存 → ブラウザで確認、のサイクルを繰り返す
- 「今から書くコードを一緒に書いてみましょう」
- 参加者に2-3分の実習時間を与える
- 「できた人？」と挙手確認

**トラブルシューティング:**
- タグの閉じ忘れ → 「開いたら必ず閉じる！」
- スペルミス → 「英語のスペルに注意」
- ファイルが開かない → ブラウザにドラッグ＆ドロップ

---

#### 【休憩】（10分）

**休憩前のアナウンス:**
- 「前半お疲れ様でした！」
- 「10分休憩します。〇〇時に再開します」
- 「質問がある人は休憩中に声をかけてください」
- 「遅れている人はサポートします」

**休憩中の対応:**
- 進捗が遅い参加者のサポート
- エラーが出ている人の確認
- 次のセクションの準備

---

#### 【メインパート2】CSS/JavaScript入門（50分）

**使用するファイル:**
- `src8/home0.html` ~ `src8/home7.html` - CSSの段階的なデモ
- `src8/home7.css` - 外部CSSファイルの例
- `src8/hello4.html`, `src8/hello5.html`, `src8/hello6.html` - JavaScriptのデモ
- `src8/hello4.js` - 外部JavaScriptファイルの例
- `src8/background.html` - 背景色の変更デモ

**CSS学習（20分）**

1. **CSSとは？（3分）**
   - 「Cascading Style Sheets」
   - HTMLは構造、CSSは見た目
   - 例：白黒の設計図に色を塗る感じ

2. **CSSの3つの書き方と段階的な改善（17分）**
   - **ファイル:** `src8/home0.html` ~ `src8/home7.html` を順番に見ていく
   - [CSSデモシリーズ（home0〜home7）](https://cdn.cs50.net/2024/fall/lectures/8/src8/)
   
   **📄 home0.html - インラインCSS（Pタグ）**
   - [デモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/home0.html)
   - 各`<p>`タグに直接`style`属性を書く
   - 問題点：同じスタイルを何度も書く必要がある（重複）
   ```html
   <p style="font-size: large; text-align: center;">John Harvard</p>
   <p style="font-size: medium; text-align: center;">Welcome!</p>
   <p style="font-size: small; text-align: center;">Copyright</p>
   ```
   
   **📄 home1.html - インラインCSS（DIVタグ）**
   - [デモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/home1.html)
   - `<p>`タグを`<div>`タグに変更
   - 見た目は同じだが、DIVの方が汎用的
   - 問題点：まだ重複がある
   ```html
   <div style="font-size: large; text-align: center;">John Harvard</div>
   <div style="font-size: medium; text-align: center;">Welcome!</div>
   <div style="font-size: small; text-align: center;">Copyright</div>
   ```
   
   **📄 home2.html - カスケーディング（親要素の活用）**
   - [デモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/home2.html)
   - 外側のDIVに`text-align: center`を配置
   - 内側のDIVは`font-size`だけ指定
   - **カスケーディング**：子要素は親のスタイルを継承
   - 改善点：`text-align: center`の重複を削減
   ```html
   <div style="text-align: center">
       <div style="font-size: large">John Harvard</div>
       <div style="font-size: medium">Welcome!</div>
       <div style="font-size: small">Copyright</div>
   </div>
   ```
   
   **📄 home3.html - bodyタグへの移動**
   - [デモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/home3.html)
   - 外側のDIVを削除
   - `text-align: center`を`<body>`タグに移動
   - 改善点：余計なDIVタグが不要に
   ```html
   <body style="text-align: center">
       <div style="font-size: large">John Harvard</div>
       <div style="font-size: medium">Welcome!</div>
       <div style="font-size: small">Copyright</div>
   </body>
   ```
   
   **📄 home4.html - セマンティックタグの導入**
   - [デモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/home4.html)
   - `<div>`を意味のあるタグに変更
     - `<header>` - ヘッダー（名前）
     - `<main>` - メインコンテンツ（挨拶）
     - `<footer>` - フッター（著作権）
   - 改善点：HTMLがより意味的に（SEO向上、アクセシビリティ向上）
   ```html
   <body style="text-align: center">
       <header style="font-size: large">John Harvard</header>
       <main style="font-size: medium">Welcome!</main>
       <footer style="font-size: small">Copyright</footer>
   </body>
   ```
   
   **📄 home5.html - styleタグの使用**
   - [デモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/home5.html)
   - インラインスタイルを`<head>`内の`<style>`タグに移動
   - **CSSセレクタ**を使用（body, header, main, footer）
   - 改善点：HTMLとCSSを分離、コードがすっきり
   ```html
   <head>
       <style>
           body { text-align: center; }
           header { font-size: large; }
           main { font-size: medium; }
           footer { font-size: small; }
       </style>
   </head>
   <body>
       <header>John Harvard</header>
       <main>Welcome!</main>
       <footer>Copyright</footer>
   </body>
   ```
   
   **📄 home6.html - クラスセレクタの使用**
   - [デモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/home6.html)
   - タグセレクタからクラスセレクタ（`.centered`, `.large`など）に変更
   - 改善点：同じスタイルを他の要素でも再利用可能
   ```html
   <head>
       <style>
           .centered { text-align: center; }
           .large { font-size: large; }
           .medium { font-size: medium; }
           .small { font-size: small; }
       </style>
   </head>
   <body class="centered">
       <header class="large">John Harvard</header>
       <main class="medium">Welcome!</main>
       <footer class="small">Copyright</footer>
   </body>
   ```
   
   **📄 home7.html - 外部CSSファイル（ベストプラクティス）**
   - [デモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/home7.html)
   - CSSを別ファイル（`home7.css`）に分離
   - `<link>`タグで外部ファイルを読み込む
   - 改善点：
     - HTMLがさらにすっきり
     - 複数のHTMLファイルで同じCSSを共有可能
     - CSSファイルだけ変更すれば全ページのデザインが変わる
   ```html
   <head>
       <link href="home7.css" rel="stylesheet">
   </head>
   <body class="centered">
       <header class="large">John Harvard</header>
       <main class="medium">Welcome!</main>
       <footer class="small">Copyright</footer>
   </body>
   ```
   
   **進化のまとめ（重要なポイント）:**
   1. **home0→home1**: PタグからDIVタグへ
   2. **home1→home2**: カスケーディングで重複削減
   3. **home2→home3**: bodyタグの活用
   4. **home3→home4**: セマンティックタグで意味づけ
   5. **home4→home5**: インラインからstyleタグへ
   6. **home5→home6**: タグセレクタからクラスセレクタへ
   7. **home6→home7**: 外部CSSファイルへ（ベスト！）
   
   **トーキングポイント:**
   - 「同じ見た目でも、書き方は段々良くなっていきます」
   - 「最初は動けばOK、徐々に改善していくのがプログラミング」
   - 「プロの開発者はhome7のように外部ファイルを使います」

3. **基本的なスタイリング（12分）**
   ```css
   body {
       background-color: lightblue;
       font-family: Arial, sans-serif;
   }
   
   h1 {
       color: navy;
       text-align: center;
   }
   
   .important {
       color: red;
       font-weight: bold;
   }
   
   #header {
       background-color: gray;
       padding: 20px;
   }
   ```
   
   **説明のポイント:**
   - セレクタの種類：タグ、クラス（`.`）、ID（`#`）
   - クラスは複数の要素に適用可能
   - IDは1つの要素のみ
   - プロパティと値の関係

**JavaScript学習（30分）**

1. **JavaScriptとは？（3分）**
   - Webページに動きをつける言語
   - ボタンを押す、フォーム入力、アニメーションなど
   - HTML/CSSは静的、JavaScriptは動的

2. **最初のJavaScript（5分）**
   - **ファイル:** `src8/hello4.html` と `src8/hello4.js` を開く
   - [JavaScriptデモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/hello4.html)
   
   **hello4.html - フォームの作成:**
   ```html
   <body>
       <form>
           <input id="name" placeholder="Name" type="text">
           <input type="submit">
       </form>
   </body>
   ```
   
   **hello4.js - 外部JavaScriptファイル:**
   ```javascript
   document.addEventListener('DOMContentLoaded', function() {
       document.querySelector('form').addEventListener('submit', function(e) {
           alert('hello, ' + document.querySelector('#name').value);
           e.preventDefault();
       });
   });
   ```
   
   **説明のポイント:**
   - `DOMContentLoaded` = ページの読み込みが完了したら実行
   - `querySelector('form')` = フォーム要素を取得
   - `addEventListener('submit', ...)` = 送信ボタンが押されたら実行
   - `document.querySelector('#name').value` = 入力された名前を取得
   - `e.preventDefault()` = ページのリロードを防ぐ（デフォルトの動作を無効化）
   - `<script src="hello4.js"></script>` = 外部JSファイルの読み込み
   
   **トーキングポイント:**
   - 「名前を入力してSubmitを押すと挨拶が表示されます」
   - 「CSSと同じように、JavaScriptも外部ファイルにできます」
   - 「`e.preventDefault()`がないとページが再読み込みされてしまいます」

3. **変数と関数（7分）**
   - **ファイル:** `src8/hello5.html` を開く
   - [変数と関数のデモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/hello5.html)
   
   ```javascript
   let name = 'Taro';
   console.log('Hello, ' + name);
   
   function greet() {
       alert('こんにちは！');
   }
   ```
   
   **説明のポイント:**
   - `let` = 変数の宣言
   - `console.log()` = デベロッパーツールで確認
   - 関数 = 処理をまとめたもの

4. **DOM操作とイベント（15分）**
   - **ファイル:** `src8/hello6.html`, `src8/background.html`, `src8/blink.html` を開く
   - [音声合成のデモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/hello6.html)
   - [背景色変更のデモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/background.html)
   - [点滅のデモ](https://cdn.cs50.net/2024/fall/lectures/8/src8/blink.html)
   
   **📄 hello6.html - 音声合成（Speech Synthesis API）**
   ```html
   <form>
       <input id="name" placeholder="Name" type="text">
       <input type="submit">
   </form>
   
   <script>
       document.addEventListener('DOMContentLoaded', function() {
           document.querySelector('form').addEventListener('submit', function(e) {
               let name = document.querySelector('#name').value;
               let utterance = new SpeechSynthesisUtterance(`hello, ${name}`);
               window.speechSynthesis.speak(utterance);
               e.preventDefault();
           });
       });
   </script>
   ```
   
   **説明のポイント:**
   - 名前を入力してSubmitを押すと、ブラウザが音声で読み上げる
   - `SpeechSynthesisUtterance` = ブラウザの音声合成API
   - `window.speechSynthesis.speak()` = テキストを音声で読み上げる
   - バッククォート（`` ` ``）を使ったテンプレートリテラル
   
   **📄 background.html - 背景色の変更**
   ```html
   <button id="red">R</button>
   <button id="green">G</button>
   <button id="blue">B</button>
   
   <script>
       let body = document.querySelector('body');
       
       document.querySelector('#red').addEventListener('click', function() {
           body.style.backgroundColor = 'red';
       });
       
       document.querySelector('#green').addEventListener('click', function() {
           body.style.backgroundColor = 'green';
       });
       
       document.querySelector('#blue').addEventListener('click', function() {
           body.style.backgroundColor = 'blue';
       });
   </script>
   ```
   
   **説明のポイント:**
   - R, G, Bボタンをクリックすると背景色が変わる
   - `addEventListener('click', ...)` = クリックイベントを監視
   - `body.style.backgroundColor` = CSSのスタイルを直接変更
   - 同じ処理を3つのボタンに設定
   
   **📄 blink.html - 自動点滅**
   ```html
   <body>
       hello, world
   </body>
   
   <script>
       function blink() {
           let body = document.querySelector('body');
           if (body.style.visibility == 'hidden') {
               body.style.visibility = 'visible';
           } else {
               body.style.visibility = 'hidden';
           }
       }
       
       // 500ミリ秒ごとに点滅
       window.setInterval(blink, 500);
   </script>
   ```
   
   **説明のポイント:**
   - `setInterval()` = 一定時間ごとに関数を実行
   - `visibility` = 表示/非表示の切り替え
   - 500ms = 0.5秒ごとに点滅
   - if文で条件分岐（hidden → visible → hidden ...）
   
   **DOM操作の基本概念:**
   - **DOM = Document Object Model**（HTMLをJavaScriptで操作する仕組み）
   - `querySelector()` = HTML要素を取得
   - `addEventListener()` = イベント（クリック、送信など）を監視
   - `style.プロパティ` = CSSスタイルを変更
   - イベント駆動プログラミング = ユーザーの操作に反応する
   
   **トーキングポイント:**
   - 「hello6は音声で挨拶します。すごいですね！」
   - 「backgroundは色が変わるのが面白いです」
   - 「blinkは自動で動きます。setIntervalで繰り返し処理ができます」
   - 「これらはすべてブラウザのAPIを使っています」

**デモの進め方:**
- CSSは視覚的な変化を見せる（色、サイズ、配置）
- JavaScriptは実際に動かして驚きを与える
- カウンターアプリは参加者に人気（達成感がある）
- 「すごい！自分でプログラムを動かせた！」という成功体験を

**実習課題の例:**
1. 好きな色に変更してみよう
2. ボタンを押したら文字が変わるようにしよう
3. カウンターを作ってみよう

---

#### 【まとめ】質疑応答（10分）

**トーキングポイント:**

1. **3つの役割の復習（3分）**
   - HTML → 構造（何を表示するか）
   - CSS → デザイン（どう見せるか）
   - JavaScript → 動き（どう動くか）
   - 「この3つがあればWebサイトが作れます！」

2. **今日学んだことの確認（2分）**
   - 「HTMLでページの骨組みを作りました」
   - 「CSSで色やレイアウトを変えました」
   - 「JavaScriptでボタンを動かしました」

3. **次のステップ（3分）**
   - CS50の続きを見る（無料）
   - 自分のWebサイトを作ってみる
   - freeCodeCamp、Progate、ドットインストールなどで学習
   - GitHubで公開してポートフォリオに

4. **質疑応答（2分）**
   - 「質問ある人いますか？」
   - 時間が余ったらGeolocationデモ

---

### よくある質問とトラブルシューティング

#### 技術的な質問

1. **Q: HTMLファイルはどうやって開くの？**
   - A: ブラウザにファイルをドラッグ＆ドロップ
   - A: VS Codeの拡張機能「Live Server」を使う（右クリック → Open with Live Server）
   - A: ファイルを右クリック → プログラムから開く → ブラウザを選択

2. **Q: コードが動かない / 表示されない**
   - A: タグの閉じ忘れをチェック（`<p>`には`</p>`が必要）
   - A: セミコロンの有無を確認（JavaScript）
   - A: スペルミスをチェック（大文字小文字も区別される）
   - A: ブラウザのキャッシュをクリア（Ctrl+Shift+R / Cmd+Shift+R）

3. **Q: 日本語が文字化けする**
   - A: `<head>`内に`<meta charset="UTF-8">`を追加
   - A: ファイルの保存形式をUTF-8にする

4. **Q: CSSが反映されない**
   - A: ファイルパスが正しいか確認
   - A: セレクタ名（クラス名、ID名）のスペルミス
   - A: ブラウザのデベロッパーツールで確認（F12キー）

5. **Q: JavaScriptのエラーが出る**
   - A: ブラウザのコンソール（F12 → Console）でエラーメッセージを確認
   - A: 変数名のスペルミス
   - A: 関数の括弧やクォートの閉じ忘れ

#### 学習に関する質問

6. **Q: プログラミング初心者でも大丈夫？**
   - A: もちろん！今日参加している人も初心者です
   - A: 最初は誰でも初心者、焦らず楽しみましょう

7. **Q: もっと学ぶにはどうすれば？**
   - A: CS50の他の講義を視聴（YouTubeで無料）
   - A: オンライン学習プラットフォーム
     - freeCodeCamp（無料、英語）
     - Progate（一部無料、日本語）
     - ドットインストール（日本語）
     - MDN Web Docs（公式リファレンス）

8. **Q: どのくらいで1つのサイトが作れるようになる？**
   - A: シンプルなサイトなら1-2週間の学習で可能
   - A: 毎日30分〜1時間の学習が効果的
   - A: 実際に手を動かすことが一番重要

9. **Q: 仕事にできる？**
   - A: Web開発は需要が高い職種
   - A: フロントエンド、バックエンド、フルスタックなど様々な道
   - A: まずは基礎をしっかり学ぶことが大切

10. **Q: 次は何を学べばいい？**
    - A: JavaScript をもっと深く（React、Vue.js など）
    - A: バックエンド（Python、Node.js など）
    - A: データベース（SQL）
    - A: バージョン管理（Git/GitHub）

---

### デモの進行テクニック

#### ライブコーディングのコツ
1. **タイピングは少しゆっくり**
   - 参加者がついていけるスピード
   - 「今、〇〇を書いています」と実況

2. **コードを書く前に説明**
   - 「これから〇〇を作ります」
   - 「〇〇タグを使います」
   - 何をするか予告する

3. **保存と確認を頻繁に**
   - コードを少し書いたら保存
   - ブラウザで結果を確認
   - 「ちゃんと動きましたね！」

4. **意図的なミスも有効**
   - タグを閉じ忘れる → エラーを見せる → 修正
   - 「こういうミスはよくあります」
   - デバッグの練習になる

#### 参加者のエンゲージメント
1. **定期的に質問する**
   - 「わかりますか？」
   - 「ついてこれていますか？」
   - 「質問ある人？」

2. **成功体験を共有**
   - 「できた人、手を挙げて！」
   - 「すごいですね！」
   - 拍手を促す

3. **休憩を適切に取る**
   - 集中力が切れる前に休憩
   - 水分補給を促す

4. **難易度を調整**
   - 早い人には発展課題
   - 遅い人には個別サポート

---

### 時間管理のコツ

#### 時間が押している場合
- CSS の詳細をスキップ（基本のみ）
- JavaScript の発展的な内容をカット
- デモをシンプルにする

#### 時間が余っている場合
- Geolocation デモを実施
- 自由な実習時間を増やす
- より複雑な例を追加

#### タイムキーパー
- 各セクションの終了時刻をメモ
- 5分前に「あと5分です」とアナウンス
- 柔軟に調整しながら進行

---

### 成功の秘訣

✅ **準備が9割**
- 事前に何度もリハーサル
- 全てのコードを事前にテスト
- バックアッププランを用意

✅ **参加者中心**
- 一方的な講義ではなく、一緒に作る
- 失敗を恐れない雰囲気作り
- 「できた！」の瞬間を大切に

✅ **楽しさを重視**
- Web開発は楽しい！を伝える
- 完璧でなくてOK
- 学習の入り口として最適な体験を

---

*Last Updated: 2025年11月10日*
