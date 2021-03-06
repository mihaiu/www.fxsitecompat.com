---
title: "`XMLHttpRequest.sendAsBinary` が廃止予定となりました"
date: "2014-04-03T19:31:02-04:00"
categories: ["dom"]
tags: []
versions: ["31"]
cclicense: "BY-SA 3.0"
references:
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=939323"
      title: "Bug 939323 – Warn about XMLHttpRequest sendAsBinary usage"
---
[`XMLHttpRequest`](https://developer.mozilla.org/ja/docs/Web/API/XMLHttpRequest) インタフェース上の非標準 `sendAsBinary` メソッドが廃止予定とされ、近々削除されることとなりました。代わりに標準の `send(Blob)` メソッドを使用してください。

**更新**: このメソッドは [Firefox 39 で削除されました](https://www.fxsitecompat.com/ja/docs/2015/xmlhttprequest-sendasbinary-has-been-removed/)。
