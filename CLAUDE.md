# スズダケ竹細工レシピサイト

## サイト情報
- URL: https://24moto-sz.github.io/suzudake-craft/
- リポジトリ: https://github.com/24moto-SZ/suzudake-craft
- GitHubアカウント: 24moto-SZ
- 目的: 自分用の知識ベース（約30製品のレシピをまとめる）

## 運用ルール
- 写真は全部横向き（横長）に統一
- 完成写真は必ず1枚目に置く
- 画像加工（トリミング・回転・明るさ等）はユーザーが事前に済ませてから送る
- こちらではリサイズ（1200px幅、sips使用）のみ行う
- 元画像は /Users/favor_book/Desktop/heic_to_jpg/ にあることが多い

## レシピ追加の流れ
1. ユーザーが加工済み写真＋テキスト（手順）を送る
2. 画像を recipes/{レシピ名}/images/ にリサイズして配置
3. レシピページ（index.html）を作成
4. トップページ（index.html）のレシピ一覧に追加
5. commit & push

## 構成
```
index.html              # トップページ（レシピ一覧）
recipes/
  chikaradake/          # 力竹の入れ方
    index.html
    images/
```

## 現在のレシピ
1. １尺ざる 力竹の入れ方
