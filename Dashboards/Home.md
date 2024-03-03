---
cssclasses:
  - dashboardhome
banner: "![[Banner.webp]]"
banner_x: 0.5
banner_y: 0.7
---


```meta-bind-button
label: Novo NPC
hidden: true
class: "botaolargura botaobold botaogreen"
tooltip: ""
id: npc
style: primary
actions:
  - type: templaterCreateNote
    templateFile: Modelos/NPC.md
    folderPath: Npcs
    fileName: Novo NPC
    openNote: true
  - type: command
    command: workspace:edit-file-title

```

```meta-bind-button
label: Novo Item
hidden: true
class: "botaolargura botaobold botaogreen"
tooltip: ""
id: item
style: primary
actions:
  - type: templaterCreateNote
    templateFile: Modelos/Item.md
    folderPath: Itens
    fileName: Novo Item
    openNote: true
  - type: command
    command: workspace:edit-file-title

```

```meta-bind-button
label: Nova Erva
hidden: true
class: "botaolargura botaobold botaogreen"
tooltip: ""
id: erva
style: primary
actions:
  - type: templaterCreateNote
    templateFile: Modelos/Erva.md
    folderPath: Herbário
    fileName: Nova Erva
    openNote: true
  - type: command
    command: workspace:edit-file-title

```

```meta-bind-button
label: Novo Veículo
hidden: true
class: "botaolargura botaobold botaogreen"
tooltip: ""
id: veiculo
style: primary
actions:
  - type: templaterCreateNote
    templateFile: Modelos/Veículo.md
    folderPath: Veículos
    fileName: Novo Veículo
    openNote: true
  - type: command
    command: workspace:edit-file-title

```

```meta-bind-button
label: Itens
hidden: true
class: "botaolargura botaobold botaoblue"
tooltip: ""
id: moc-itens
style: primary
actions:
  - type: open
    link: "[[Itens]]"

```

```meta-bind-button
label: Veículos
hidden: true
class: "botaolargura botaobold botaoblue"
tooltip: ""
id: moc-veiculos
style: primary
actions:
  - type: open
    link: "[[Veículos]]"

```

```meta-bind-button
label: Regras da Casa
hidden: true
class: "botaolargura botaobold botaoblue"
tooltip: ""
id: moc-regrascasa
style: primary
actions:
  - type: open
    link: "[[Regras da Casa]]"

```

<h1 align="center">Comandos</h1>

- `BUTTON[npc]`
- `BUTTON[item]`
- `BUTTON[erva]`
- `BUTTON[veiculo]`

**⠀**

<h1 align="center">Menu</h1>

- `BUTTON[moc-itens]`
- `BUTTON[moc-veiculos]`
- `BUTTON[moc-regrascasa]`

