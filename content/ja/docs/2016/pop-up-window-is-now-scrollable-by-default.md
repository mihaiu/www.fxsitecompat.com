---
title: "ポップアップウィンドウが初期設定でスクロール可能となりました"
date: "2016-05-25T13:52:00-04:00"
categories: ["dom"]
tags: []
versions: ["49"]
references:
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1257887"
      title: "Bug 1257887 - Consider changing the default for whether a window opened through window.open() to be scrollable"
    - url: "https://groups.google.com/d/topic/mozilla.dev.platform/BAmbAhZiR7o/discussion"
      title: "Intent to enable scrollbars by default for windows opened by window.open()"
---
これまで、[`window.open`](https://developer.mozilla.org/ja/docs/Web/API/Window/open) の `scrollbars` オプションは初期設定で `no` でした。アクセシビリティ上の理由から、Firefox 49 でこれが `yes` に変更され、元ページの作者が同メソッドの第 3 引数で `scrollbars=no` を指定していない限り、ユーザは新たに開かれたウィンドウ上でスクロールできるようになりました。Chrome と Safari はいずれにしてもこのオプションに対応してないため、互換性への影響は軽微なはずです。
