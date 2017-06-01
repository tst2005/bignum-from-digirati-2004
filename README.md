# updated fork of luabignum

Original website : http://oss.digirati.com.br/luabignum/
Original sources : http://oss.digirati.com.br/luabignum/BigNum.zip


# Changes

My fixes

* fix module/require use, mainly:
```diff
-require "BigNum.lua"
+local BigNum = require "BigNum"
```
* at the end of file, return the module table
* remove useless trailing semicolon
* some compat fix

