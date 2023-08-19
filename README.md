[Read the documentation at the original repo](https://github.com/louischatriot/nedb)

### Built for use with Next.js and electron

> This repo does one very specific thing, in the Persistence module, it prefers using `path` from a `global.path` then falls back to `require("path")` if `global.path` is undefined.
> This behavior is to allow next.js developers to get `path` from `contextBridge` in electron then set `global.path` variable for use in modules that require it.
