---
title: "`SmsRequest` が `DOMRequest` に置き換えられました"
date: "2012-10-09T06:00:00-04:00"
categories: ["dom"]
tags: []
versions: ["16"]
cclicense: "BY-SA 3.0"
references:
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=760011"
      title: "Bug 760011 – Make nsIMozSmsRequest inherit from nsIDOMDOMRequest"
---
`SmsRequest` オブジェクトは、より一般的で同じ属性とイベントハンドラを提供する [`DOMRequest`](https://developer.mozilla.org/ja/docs/Web/API/DOMRequest) に置き換えられました。
