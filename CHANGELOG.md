# sapper changelog

## 0.1.2

* Use `atime.getTime()` and `mtime.getTime()` instead of `atimeMs` and `mtimeMs` ([#11](https://github.com/sveltejs/sapper/issues/11))
* Make dest dir before anyone tries to write to it ([#18](https://github.com/sveltejs/sapper/pull/18))

## 0.1.1

* Expose resolved pathname to `sapper/runtime/app.js` as `__app__` inside main.js

## 0.1.0

* First public preview