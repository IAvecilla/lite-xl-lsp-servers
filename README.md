# Lite-XL LSP Servers

A simple repo that contains plugins which automatically set up LSP servers with `lpm` or another
lite-xl package manager.

LSP servers can still be setup manually; this just serves to make it really easy to install, use
and depend on particular LSP servers functioning.

## Quickstart

```
lpm add https://github.com/adamharrison/lite-xl-lsp-servers.git && lpm install lsp_c lsp_lua
```

## Languages Supported

The following languages are supported, bundled with their particular language server.

| Plugin                                       | Language(s)          | Server                                                          | Platforms
| :------------------------------------------- | :------------------- | :-------------------------------------------------------------- | :--------
| [lsp_lua](/plugins/lsp_lua.lua?raw=1)        | lua                  | [sumneko_lua](https://github.com/sumneko/lua-language-server)   | Linux, Mac, Windows
| [lsp_c](/plugins/lsp_c.lua?raw=1)            | C, C++, Objective-C  | [clangd](https://github.com/clangd/clangd)                      | Linux, Mac, Windows

