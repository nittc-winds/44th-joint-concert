# 44th-joint-concert

第44回 高専音楽祭のための[Webページ](https://nittc-winds.github.io/44th-joint-concert/)を作成するためのリポジトリです。

<br>


# Features
とりあえず[部長たちのデザイン](https://github.com/nittc-winds/44th-joint-concert/tree/main/src)を起こした後色々やる感じ

<br>

# Requirement

 <br>
 
# Usage
## 手元で色々試す場合(`clone`後)


例えばPython環境が入ってるマシンで以下を実行した後、[9000番ポート](http://localhost:9000/)にアクセスしてください。


```
> cd プロジェクトのルートディレクトリ    # ex. C:\Users\tyama\Desktop\src\44th-joint-concert

> python -m http.server 9000          # Webサーバ起動
```

<br>

## もし Visual Studio Code を使っているなら？
`F5`キーで実行してください

<br>

# Note ディレクトリ構成

- HTMLファイルはルートディレクトリの直下に置く
- 画像とCSSは `static/` 内に起きます

<br>

```bash
44th-joint-concert     # ルートディレクトリ
│
├── .vscode
│   └── settings.json  # VSCode用
├── LICENSE
├── README.md
├── index.html         # プロジェクトルート直下に置いちゃう
├── src                # 部長たちのデザイン or 画像
└── static             # 画像とCSS
    ├── css
    └── img


4 directories, 20 files
```

<br>

# Author
 
 
* 徳山高専吹奏楽部関係者
* NITTC
 
