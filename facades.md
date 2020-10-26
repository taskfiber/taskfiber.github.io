---
title: Facades
date: 2020-10-26 16:32:00 Z
---

Facades are simple classes where you can call static functions on a [Service](services.html).

By default only the Fiber facade is loaded.
Enable more facades in your app/config.php
`Fiber::enable('facades');`

Or call them directly, e.g:
`Fiber\Facade\Config::get('site-title')`



Currently we support the following facades:
* Authenticate
* Config
* Database
* Resolve
* Router
* Service
