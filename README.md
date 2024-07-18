# Clash-Rules
OpenClash.Meta RULE-SET

# How to apply in OpenClash
```
rule-providers:
  GameDownload:
    type: http
    url: "https://raw.githubusercontent.com/KoalaJas/Clash-Rules/main/GameDownload.yaml"
    interval: 86400
    proxy: DIRECT
    behavior: classical
    format: yaml
  Game:
    type: http
    url: "https://raw.githubusercontent.com/KoalaJas/Clash-Rules/main/Game.yaml"
    interval: 86400
    proxy: DIRECT
    behavior: classical
    format: yaml
rules:
  - RULE-SET,GameDownload,DIRECT
  - RULE-SET,Game,Proxy
```