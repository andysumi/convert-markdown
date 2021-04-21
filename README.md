---
stylesheet: https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/2.10.0/github-markdown.min.css
body_class: markdown-body
css: |-
  .page-break { page-break-after: always; }
  .markdown-body { font-size: 11px; }
  .markdown-body pre > code { white-space: pre-wrap; }
pdf_options:
  format: A4
  margin: 25mm 20mm
---

# README

# 見出しh1

## TOC

- [README](#readme)
- [見出しh1](#見出しh1)
  - [TOC](#toc)
  - [見出しh2](#見出しh2)
    - [リスト](#リスト)
    - [番号付きリスト](#番号付きリスト)
    - [チェックボックス](#チェックボックス)
    - [インライン表示](#インライン表示)
    - [コードブロック](#コードブロック)
    - [リンク](#リンク)
    - [引用](#引用)
    - [画像](#画像)
    - [テーブル](#テーブル)
    - [文字装飾](#文字装飾)
    - [水平線](#水平線)
    - [注釈](#注釈)

## 見出しh2

### リスト

- テキスト
  - テキスト
  - テキスト

### 番号付きリスト

1. テキスト
2. テキスト
   1. テキスト
      1. テキスト
3. テキスト

### チェックボックス

- [ ] タスク1
- [x] タスク2
- [ ] タスク3

### インライン表示

このように `int i = 0` がインライン表示されます

### コードブロック

```js:main.js
function hoge() {
  console.log('hello world');
}
```

### リンク

例：[Google](https://www.google.co.jp/)

### 引用

> テキスト
>> テキスト

### 画像

例： ![qiita-square.png](https://qiita-image-store.s3.amazonaws.com/0/126861/90386757-fd96-8ba6-3477-485669713c55.png "qiita-square")

例： <img width="200" alt="qiita-square" src="https://qiita-image-store.s3.amazonaws.com/0/126861/90386757-fd96-8ba6-3477-485669713c55.png">

### テーブル

| テキスト | テキスト | テキスト |
| :--- | :---: | ---:|
| テキスト | テキスト | テキスト |
| テキスト | テキスト | テキスト |
| テキスト | テキスト | テキスト |

### 文字装飾

<font color="Red">文字色</font>

**ボールド**

*イタリック*

~~打ち消し~~

\:kissing_closed_eyes: chu☆

### 水平線

---

### 注釈

テキスト[^1]
[^1]: 注釈内容

hoge
