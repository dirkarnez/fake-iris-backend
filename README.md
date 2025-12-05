fake-iris-backend
=================
Faking (iris) restful api server so whole web application can be demoed as static pages (with hash-router, github pages does not support SPA)

### How
- Fork [kataras/iris](https://github.com/kataras/iris) and add special adaptor package thats implement a subset of API

### To tackle
- Web database adapter
- wrapped fetch
- special treatment on backend api routing (aka. do not do backend routing, use lookup table instead)
  - [Examples · millermedeiros/crossroads.js Wiki](https://github.com/millermedeiros/crossroads.js/wiki/Examples)
- Webassembly build (so it looks good)


