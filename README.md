# 領収書メーカー（iPhone用PWA）

## 公開（GitHub Pages）
1. GitHubで新しいリポジトリ `receipt` を作る（Public）
2. 「Add file → Upload files」でこのフォルダの中身を全部アップ（vendor フォルダごと）
3. Settings → Pages → Branch を `main` / `(root)` にして Save
4. 1〜2分後に `https://mishizu0615.github.io/receipt/` で開ける

## iPhoneに入れる
1. Safariで上のURLを開く
2. 共有ボタン →「ホーム画面に追加」

## 更新するとき
ファイルを差し替えたら `sw.js` の `VERSION` を `receipt-v2` のように上げる（上げないと古い版が残る）。
