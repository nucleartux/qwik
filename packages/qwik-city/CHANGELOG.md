# @builder.io/qwik-city

## 1.7.2

### Patch Changes

- During dev mode, qwik-city will no longer serve files from `dist/`, which are very likely to be stale/incorrect. Furthermore, query parameters are taken into account when serving files (like production servers would do). (by [@wmertens](https://github.com/wmertens) in [#6694](https://github.com/QwikDev/qwik/pull/6694))

- strip internal search parameters in canonical URLs (by [@wmertens](https://github.com/wmertens) in [#6694](https://github.com/QwikDev/qwik/pull/6694))

- Support entry.ts routes in dev mode now that dist/ is no longer served, and special-case `repl-sw.js` in the docs. (by [@wmertens](https://github.com/wmertens) in [#6706](https://github.com/QwikDev/qwik/pull/6706))
