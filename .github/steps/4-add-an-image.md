## Step 4　画像を追加する

Markdown では `![代替テキスト](画像URL)` と書きます。サイズや位置を指定する場合は HTML の `img` 要素も使えます。

1. `start-blog` ブランチで `day-1.md` を開き、レベル2の見出し `## Morning Planning` の下に Markdown 形式の画像を追加し、**Preview** で確認します。
2. 同じ画像を、幅と配置を指定する教材の HTML 例に置き換えます。
3. `start-blog` に直接コミットします。

### 原文のコマンド・入力例

```md
![Cloudy morning](https://octodex.github.com/images/cloud.jpg)
```

```md
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
```

### 画面での確認

- ファイル右上の鉛筆アイコンを選びます。編集欄の上の **Preview** に切り替え、Markdown 形式で画像が表示されることを確認してから HTML 例に置き換えます。
- 置き換え後も画像が表示されることを確かめ、右上の **Commit changes…** から `start-blog` に保存します。

[原文](https://github.com/skills/communicate-using-markdown/blob/main/.github/steps/4-add-an-image.md)
