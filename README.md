# git-branches


Vi lägger till första raden och committar


## Lägger till Instructions branch

Nu skapar vi en branch som heter instructions Detta gör vi med hjälp av kommandot.

```md
git checkout -b instructions
```

För att pusha upp ändringar till denna branch behöver vi först
stage, commit och pusha. För push till denna branch gör vi

```md
git push origin instructions
```

För att checka branches som vi har:


```md
git branch
```

---
## Pull requests

För att få mergea in ändringar från denna branch in till main
så öppnar vi en pull request. Detta gör vi i fliken pull request.

<img src="assets/pull_request.png" width = 400>