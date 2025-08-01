# @hono/auth-js

## 1.1.0

### Minor Changes

- [#1324](https://github.com/honojs/middleware/pull/1324) [`d89fed7eecfa151c18b0a8cf95dae1dfe83dfec2`](https://github.com/honojs/middleware/commit/d89fed7eecfa151c18b0a8cf95dae1dfe83dfec2) Thanks [@jamestalmage](https://github.com/jamestalmage)! - Allow async authjs Config

## 1.0.17

### Patch Changes

- [#1210](https://github.com/honojs/middleware/pull/1210) [`0758fd0af1f213131d0894299e5bec716d284580`](https://github.com/honojs/middleware/commit/0758fd0af1f213131d0894299e5bec716d284580) Thanks [@BarryThePenguin](https://github.com/BarryThePenguin)! - Add explicit return types

## 1.0.16

### Patch Changes

- [#1170](https://github.com/honojs/middleware/pull/1170) [`7585969171ad4876e7620c7369eb9b638849d0eb`](https://github.com/honojs/middleware/commit/7585969171ad4876e7620c7369eb9b638849d0eb) Thanks [@hambergerpls](https://github.com/hambergerpls)! - fix(auth-js): use HonoRequest.blob() instead of HonoRequest.raw.body()

## 1.0.15

### Patch Changes

- [#813](https://github.com/honojs/middleware/pull/813) [`b1c812e50c9388cf7cda893e7c554cedeb24d803`](https://github.com/honojs/middleware/commit/b1c812e50c9388cf7cda893e7c554cedeb24d803) Thanks [@divyam234](https://github.com/divyam234)! - add react 19 in peer dependencies

## 1.0.14

### Patch Changes

- [#806](https://github.com/honojs/middleware/pull/806) [`9a2cf452c7000aee4193502da755b2c4352b077d`](https://github.com/honojs/middleware/commit/9a2cf452c7000aee4193502da755b2c4352b077d) Thanks [@985563349](https://github.com/985563349)! - fix cloned request causing request body to be unavailable in middleware

## 1.0.13

### Patch Changes

- [#790](https://github.com/honojs/middleware/pull/790) [`ed31c680f7cb4d08985c820e8e1bf051ddc57acd`](https://github.com/honojs/middleware/commit/ed31c680f7cb4d08985c820e8e1bf051ddc57acd) Thanks [@divyam234](https://github.com/divyam234)! - clone request directly for bun

## 1.0.12

### Patch Changes

- [#775](https://github.com/honojs/middleware/pull/775) [`c19b51baaf396647f2d6b021e38f083768328b74`](https://github.com/honojs/middleware/commit/c19b51baaf396647f2d6b021e38f083768328b74) Thanks [@divyam234](https://github.com/divyam234)! - refactor session provider

## 1.0.11

### Patch Changes

- [#769](https://github.com/honojs/middleware/pull/769) [`c2d661aa697bc3800a1b4b6c10ed3589d6d85cf2`](https://github.com/honojs/middleware/commit/c2d661aa697bc3800a1b4b6c10ed3589d6d85cf2) Thanks [@yusukebe](https://github.com/yusukebe)! - fix: remove config.basePath

## 1.0.10

### Patch Changes

- [#614](https://github.com/honojs/middleware/pull/614) [`19f3beae1ab33bb3257694c742d1b3e5487a187d`](https://github.com/honojs/middleware/commit/19f3beae1ab33bb3257694c742d1b3e5487a187d) Thanks [@divyam234](https://github.com/divyam234)! - fix immutable headers error in x-forwarded req

## 1.0.9

### Patch Changes

- [#598](https://github.com/honojs/middleware/pull/598) [`eb7e597aaabce2b2ac6e7809579c44f440c2b8b0`](https://github.com/honojs/middleware/commit/eb7e597aaabce2b2ac6e7809579c44f440c2b8b0) Thanks [@divyam234](https://github.com/divyam234)! - fix bun req cloning

## 1.0.8

### Patch Changes

- [#549](https://github.com/honojs/middleware/pull/549) [`d5ebee9c70b5c6e9ecdcadd39805a6a7c481c0ee`](https://github.com/honojs/middleware/commit/d5ebee9c70b5c6e9ecdcadd39805a6a7c481c0ee) Thanks [@divyam234](https://github.com/divyam234)! - handle x-forwarded headers to detect auth url

## 1.0.7

### Patch Changes

- [#494](https://github.com/honojs/middleware/pull/494) [`300ef2f8bf4761b7b005e0c4ee7cb6ccf3ef810b`](https://github.com/honojs/middleware/commit/300ef2f8bf4761b7b005e0c4ee7cb6ccf3ef810b) Thanks [@divyam234](https://github.com/divyam234)! - fix for ssr

## 1.0.6

### Patch Changes

- [#486](https://github.com/honojs/middleware/pull/486) [`18959557f45851a0109a63de3e865329c30d4fcc`](https://github.com/honojs/middleware/commit/18959557f45851a0109a63de3e865329c30d4fcc) Thanks [@yusukebe](https://github.com/yusukebe)! - fix: use `env` in `hono/adapter` and add tests

## 1.0.5

### Patch Changes

- [#481](https://github.com/honojs/middleware/pull/481) [`b8fb9a06c13c3d5988b21e1b286c2a0b5ba99d80`](https://github.com/honojs/middleware/commit/b8fb9a06c13c3d5988b21e1b286c2a0b5ba99d80) Thanks [@DIYgod](https://github.com/DIYgod)! - fix AUTH_URL not working in getAuthUser

## 1.0.4

### Patch Changes

- [#478](https://github.com/honojs/middleware/pull/478) [`5004ca9c5b6f75c1fca001c26fc70b927c154589`](https://github.com/honojs/middleware/commit/5004ca9c5b6f75c1fca001c26fc70b927c154589) Thanks [@DIYgod](https://github.com/DIYgod)! - fix env AUTH_URL not working

## 1.0.3

### Patch Changes

- [#380](https://github.com/honojs/middleware/pull/380) [`ea19f6bdeb14216da0880baf5dd5885395c0f008`](https://github.com/honojs/middleware/commit/ea19f6bdeb14216da0880baf5dd5885395c0f008) Thanks [@CarlosZiegler](https://github.com/CarlosZiegler)! - fix: change peer dependency to support v4.0.0

## 1.0.2

### Patch Changes

- [#359](https://github.com/honojs/middleware/pull/359) [`4ccda19d3176d9148310bcdb33baf48986433342`](https://github.com/honojs/middleware/commit/4ccda19d3176d9148310bcdb33baf48986433342) Thanks [@divyam234](https://github.com/divyam234)! - Update @auth/core version and set default basePath

## 1.0.1

### Patch Changes

- [#330](https://github.com/honojs/middleware/pull/330) [`766738e0ea8f5e45739e0ffc4248f132f6313957`](https://github.com/honojs/middleware/commit/766738e0ea8f5e45739e0ffc4248f132f6313957) Thanks [@divyam234](https://github.com/divyam234)! - added react as peer dependency

## 1.0.0

### Major Changes

- [#326](https://github.com/honojs/middleware/pull/326) [`f9859e8fa7e79e1111b8d335d927e7de0309dd7d`](https://github.com/honojs/middleware/commit/f9859e8fa7e79e1111b8d335d927e7de0309dd7d) Thanks [@divyam234](https://github.com/divyam234)! - initial support auth.js with hono
