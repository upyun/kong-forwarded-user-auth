# kong-forwarded-user-auth

Access Control with `X-Forwarded-User` header.

## Install

```
# luarocks make
```

## Enable

```
# export KONG_PLUGINS=bundled,forwarded-user-auth
# kong start -vv
```