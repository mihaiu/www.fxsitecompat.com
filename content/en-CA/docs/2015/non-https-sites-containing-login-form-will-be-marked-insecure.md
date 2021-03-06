---
title: "Non-HTTPS sites containing login form will be marked insecure (currently only on Nightly and Developer Edition)"
date: "2015-10-21T14:38:00-07:00"
categories: ["privacy-security"]
tags: []
versions: ["46"]
statuses: "affected"
references:
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1188121"
      title: "Bug 1188121 - [userstory] CC: Warning for password on non-secure connection"
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1179961"
      title: "Bug 1179961 - Use a lock with a strikethrough for HTTP pages that have Password Fields in the Control Center"
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1221206"
      title: "Bug 1221206 - Turn on Insecure Password Warning for Firefox Dev Edition"
---
Firefox now shows a [broken padlock icon](https://bug1179961.bmoattachments.org/attachment.cgi?id=8662392) on the location bar when the current page has `<input type="password">` while the connection is not secure. Not only the page the password will be sent but also the page the login form presents must use the HTTPS protocol to [protect user credentials from remote attackers](https://developer.mozilla.org/en-US/docs/Web/Security/Insecure_passwords).

Although this functionality is currently enabled only on Firefox Nightly and Developer Edition, webmasters may want to avoid such an embarrassing situation. No budget for a TLS certificate? Don't worry. From November 2015, [Let's Encrypt](https://letsencrypt.org/), a new certificate authority run by Mozilla and others, gives you a trusted certificate for free.

Read [Tanvi Vyas' blog post](https://blog.mozilla.org/tanvi/2016/01/28/no-more-passwords-over-http-please/) for details.
