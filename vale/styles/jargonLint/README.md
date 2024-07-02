# jargonList rules

## Tooling

To sort rules that extend substitution

```shell
yq '.swap |= ((to_entries | sort_by(.value | downcase)) | from_entries) '
```