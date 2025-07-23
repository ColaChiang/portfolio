---
title: Bash 變數
weight: 210
menu:
  notes:
    name: 變數
    identifier: notes-bash-variables
    parent: notes-bash
    weight: 10
---

<!-- Variable -->
{{< note title="Variable" >}}

```bash
NAME="Kaylen"
echo $NAME
echo "$NAME"
echo "${NAME}
```
{{< /note >}}

<!-- Condition -->
{{< note title="Condition" >}}

```bash
if [[ -z "$string" ]]; then
  echo "String is empty"
elif [[ -n "$string" ]]; then
  echo "String is not empty"
fi
```
{{< /note >}}