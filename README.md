# 世田谷静坐会 ホームページ

世田谷静坐会のホームページのソースです。GitHub Pages で公開しています。

- 公開URL：https://setagaya-seizakai.github.io/
- 公開元：`main` ブランチの `docs/` フォルダ（`docs/` の外のファイルはサイトには出ません）

## フォルダ構成

```
├── README.md      ← このファイル（サイトには出ない）
└── docs/          ← ここだけがWebサイトになる
    ├── .nojekyll  ← GitHub Pages の Jekyll 処理を無効にする空ファイル
    ├── index.html
    ├── css/
    ├── images/
    └── pdf/
```

## 更新のしかた

1. `docs/` の中のHTMLなどを編集する
2. ローカルで表示を確認する

   ```bash
   cd docs && python3 -m http.server 8000
   ```

   ブラウザで http://localhost:8000 を開く
3. 問題なければ commit して `main` に push する（1分ほどでサイトに反映される）

## 注意

このリポジトリは誰でも閲覧できます。会員名簿や個人の連絡先など、公開してはいけない情報は、`docs/` の外も含めてどこにも置かないでください。
