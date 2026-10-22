# HALZ 時計ウィジェット（Notionポータル用）

Notionのポータルに埋め込む、日付・時刻・ひとことを表示するページです。

## 中身
- `index.html` … 本体（ふだんは触らない）
- `config.js` … 背景・ひとこと・秒の表示の設定（ここだけ書き換える）
- `bg.jpg` … 背景の写真（Unsplashの無料写真）

## よくある変更
- **ひとことを変える**：`config.js` の `messages` の行を書き換える。1日ごとに上から順番に切り替わる。
- **背景を変える**：新しい画像をこのフォルダに入れて、`config.js` の `background` をそのファイル名にする。
- **文字が読みにくい**：`overlay` を大きくする（例：0.45 → 0.6）。

GitHubの画面でファイルを開き、鉛筆マークで編集して「Commit changes」を押すと、数分でNotionの表示にも反映されます。

## Notionへの貼り方
Notionで `/embed` と入力し、公開されたページのURL（例：`https://<アカウント名>.github.io/halz-clock/`）を貼る。
