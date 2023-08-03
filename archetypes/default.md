---
title: "{{ replace .Name "-" " " | title }}"
date: "{{ dateFormat "2006-01-02" .Date}}"
toc: true
# thumbnail: "images/2019/08/XXXX/XXXX.jpeg"
tags: ["",""]
url: /xxx/
archives: ["{{ dateFormat "2006/01" .Date }}"]
draft: false

# lastmod: "{{ dateFormat "2006-01-02" .Date}}"
# categories: []

---

## サンプル
はてなブログカード

{{< blogcard url="https" >}}
