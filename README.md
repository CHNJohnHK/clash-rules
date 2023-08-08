# Clash-Rules
自用规则
为了防止忘记和找不到文档 标注一下（
### rule-providers
```yaml
rule-providers:
  JohnHK-AD:
    type: http
    behavior: domain
    url: "https://raw.githubusercontent.com/CHNJohnHK/clash-rules/main/rules/johnhk-ad.yaml"
    path: ./ruleset/johnhk-ad.yaml
    interval: 86400
```
### rule
```yaml
  - RULE-SET,JohnHK-AD,REJECT
```
