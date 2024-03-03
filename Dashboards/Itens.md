---
cssclasses:
  - dashboard
  - tableitens
tags: MoC
---

# Armaduras

```dataview
table without id file.link as Item, Tipo,  PreçoVisivel as Preço, Espaço
from #Item
where contains(Tipo, "Armadura") or contains(Tipo, "Escudo")
sort file.name asc
sort Preço asc
sort Tipo asc
```

# Armas Simples

```dataview
table without id file.link as Item, Tipo,  PreçoVisivel as Preço, Espaço
from #Item/Arma/Simples
sort file.name asc
sort Tipo asc
```

# Armas Marciais

```dataview
table without id file.link as Item, Tipo, PreçoVisivel as Preço, Espaço
from #Item/Arma/Marcial
sort file.name asc
sort Tipo asc
```

# Equipamentos

```dataview
table without id file.link as Item, Tipo, PreçoVisivel as Preço, Espaço
from #Item/Equipamento
sort file.name asc
sort Tipo asc
```

# Ferramentas

```dataview
table without id file.link as Item, Tipo, PreçoVisivel as Preço, Espaço
from #Item/Ferramenta
sort file.name asc
sort Tipo asc
```

# Bens de Comércio

```dataview
table without id file.link as Item, Tipo, PreçoVisivel as Preço, Espaço
from #Item/Bens-de-Comércio
sort file.name asc
sort Preço asc
```
