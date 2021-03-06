---
title: "古い Proxy API が削除されました"
date: "2016-03-12T18:44:00-05:00"
categories: ["javascript"]
tags: []
versions: ["48"]
references:
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=892903"
      title: "Bug 892903 - Remove Proxy.create and Proxy.createFunction"
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1244442"
      title: "Bug 1244442 - Warn about Proxy.create and Proxy.createFunction"
aliases:
    - "/docs/2015/legacy-proxy-api-will-be-removed/"
---
[Firefox 18 以降廃止予定となっている](https://www.fxsitecompat.com/ja/docs/2012/proxy-api-has-been-updated-for-the-new-spec/)、`Proxy.create`、`Proxy.createFunction` メソッドを含む非標準の [古い Proxy API](https://developer.mozilla.org/ja/docs/Archive/Web/Old_Proxy_API) は、Firefox 48 で削除されました。Firefox 47 では Web コンソールに廃止予定の警告が表示されます。[標準化された Proxy API](https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference/Global_Objects/Proxy) を代わりに使用してください。
