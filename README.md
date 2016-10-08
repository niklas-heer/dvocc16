DevOps Camp Compact 2016
========================

# Session Caddy

This repo contains the session notes for the session "Caddy" at the [#dvocc16](https://twitter.com/search?q=%23dvocc16)

## Links

- Caddy: https://caddyserver.com/
- Let's Encrypt: https://letsencrypt.org/
- Caddy Docs: https://caddyserver.com/docs
- Caddy Build service: https://caddyserver.com/download
- Caddy Download Script: https://getcaddy.com/ (`curl https://getcaddy.com | bash`)
- Complete Install Script: https://github.com/sayem314/Caddy-Web-Server-Installer (`wget https://git.io/vra5C -O - -o /dev/null|bash`)
- Caddy & QUIC: https://github.com/mholt/caddy/wiki/QUIC
- Caddy Syntax Support for Sublimetext: https://github.com/caddyserver/sublimetext

## More Stuff


Fix conflicts with systemd:

```
setcap cap_net_bind_service=+ep /opt/caddyserver/caddy &>/dev/null
```
