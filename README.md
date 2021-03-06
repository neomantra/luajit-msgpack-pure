# luajit-msgpack-pure

## Presentation

This is yet another implementation of MessagePack for LuaJIT.
However, unlike [luajit-msgpack](https://github.com/catwell/luajit-msgpack),
luajit-msgpack-pure does not depend on the MessagePack C library.
Everything is re-implemented in LuaJIT code (using the FFI but only to
manipulate data structures).

## Alternatives

 - [lua-msgpack](https://github.com/kengonakajima/lua-msgpack) (pure Lua)
 - [lua-msgpack-native](https://github.com/kengonakajima/lua-msgpack-native)
   (Lua-specific C implementation)
 - [MPLua](https://github.com/nobu-k/mplua) (binding)

## TODO

- Missing datatype tests
- Comparison tests vs. luajit-msgpack

## Usage

See tests/test.lua.
