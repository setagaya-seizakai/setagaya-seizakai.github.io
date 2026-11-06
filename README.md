# 世田谷静坐会 ホームページ

世田谷静坐会のホームページのソースです。GitHub Pages で公開しています。

- 公開URL：https://setagaya-seizakai.github.io/
- 公開元：`main` ブランチの `docs/` フォルダ（`docs/` の外のファイルはサイトには出ません）

## フォルダ構成

```
├── README.md      ← このファイル（サイトには出ない）
└── docs/          ← ここだけがWebサイトになる
    ├── .nojekyll  ← GitHub Pages の Jekyll 処理を無効にする空ファイル
    ├── index.html       ← トップ
    ├── about.html       ← 岡田式静坐法
    ├── howto.html       ← 初めての静坐
    ├── aims.html        ← 静坐の目指すもの
    ├── history.html     ← 世田谷静坐会の歩み
    ├── join.html        ← 参坐をご希望の方
    ├── join-faq.html    ← 静坐に不安をお持ちの皆様に
    ├── news.html        ← 最新情報
    ├── info.html        ← お知らせ
    ├── references.html  ← 引用文献・参考資料
    ├── goroku/          ← 深田 淳先生 語録（1.html〜4.html）
    ├── css/style.css    ← 全ページ共通のスタイル
    ├── images/
    └── pdf/
```

各ページの本文は、旧サイト（BIGLOBE・ホームページV4）の内容をそのまま移したものです。

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
