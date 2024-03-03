---
cssclasses:
  - dashboard
  - tableitens
tags: MoC
---

# Terrestres

```dataview
table without id file.link as Item, Velocidade, Passageiros, Tripulantes, Carga,  PreçoVisivel as Preço, Manutenção as "Manutenção (30d)"
from #Veículo
where contains(Tipo, "Terrestre")
sort file.name asc
sort Preço asc
```

# Aquáticos

```dataview
table without id file.link as Item, Velocidade, Passageiros, Tripulantes, Carga,  PreçoVisivel as Preço, Manutenção as "Manutenção (30d)"
from #Veículo
where contains(Tipo, "Aquáticos")
sort file.name asc
sort Preço asc
```

# Aéreos

```dataview
table without id file.link as Item, Velocidade, Passageiros, Tripulantes, Carga,  PreçoVisivel as Preço, Manutenção as "Manutenção (30d)"
from #Veículo
where contains(Tipo, "Aéreos")
sort file.name asc
sort Preço asc
```
