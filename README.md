# Clash-Rules
OpenClash.Meta RULE-SET

# How to apply in OpenClash
```
rule-providers:
  Game:
    type: http
    url: "https://raw.githubusercontent.com/KoalaJas/Clash-Rules/main/Game.yaml"
    interval: 600
    proxy: DIRECT
    behavior: classical
    format: yaml
rules:
  - RULE-SET,Game,Proxy
```