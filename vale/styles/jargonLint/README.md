# jargonList rules

## Tooling

To sort rules that extend substitution

```shell
awk -FS=':' '{print $2 $1}' rule.yaml | sort | awk -FS=':' '{print $2 $1}'
```