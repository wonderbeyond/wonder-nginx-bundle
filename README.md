# A Nginx Bundle

My Nginx bundle: Nginx + useful 3rd-party modules + Lua + Lua libs

Inspired by [OpenResty](http://openresty.org/).

## Materials

Refer to: https://github.com/openresty/lua-nginx-module#installation

- [nginx](http://nginx.org/download/nginx-1.7.12.tar.gz)

- [LuaJIT](https://github.com/openresty/luajit2/releases/tag/v2.1-20150223)

- Nginx modules:

    - [ngx_devel_kit](https://github.com/simpl/ngx_devel_kit/releases/tag/v0.2.19)

    - [ngx_lua](https://github.com/openresty/lua-nginx-module/releases/tag/v0.9.16rc1)

- ngx_lua libs

    - [lua-resty-redis](https://github.com/openresty/lua-resty-redis)

    - [cjson](https://github.com/mpx/lua-cjson/)

## Build

Refer to the install script, however it still to be improved.

## Nginx configuration sample

[nginx.conf.sample](./nginx.conf.sample)
