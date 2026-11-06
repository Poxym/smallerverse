# Smallerverse

Sonidos de los heropacks del servidor (Fisk Superheroes 2.4.0 + Superhero Utils).

Fisk baja `https://raw.githubusercontent.com/Poxym/smallerverse/master/sounds/<version>.zip` por cada dominio que lo pide en
`heropack.json` (`"download": {"repository": "Poxym/smallerverse", "version": N}`) y lo guarda en cache por numero.

**Para cambiar los sonidos de un dominio, sube un zip con un numero NUEVO y cambia ese numero en el heropack.** Si reemplazas
un zip con el mismo numero, quien ya lo tenia no lo vuelve a bajar. `tools/sonidos_repo.py` (fuente de SHU) arma esta carpeta.

`sounds/0.zip` es el de AdvancedLegends suelto (para quien use ese pack sin el unificado).

| Zip | Dominio | De donde salio | Contenido | Sonidos sin archivo (ya faltaban en el original) |
|---|---|---|---|---|
| `sounds/1.zip` | `smallerverse` | Poxym/smallerverse:sounds/sounds/0.zip, Poxym/smallerverse:sounds/0.zip | 110 sonidos, 13.3 MB | - |
| `sounds/2.zip` | `tgheroes` | Tagged-Imp/TGheroes:0 | 277 sonidos, 16.9 MB | giant_land -> suits/giant_land |
| `sounds/2.zip` | `loriatpack` | Tagged-Imp/TGheroes:0 | (mismo zip) | - |
| `sounds/3.zip` | `sind` | Ergoslab/SindSounds:18 | 55 sonidos, 5.5 MB | - |
| `sounds/4.zip` | `jmctheroes` | JMCT13/jmctheroes:0 | 45 sonidos, 1.6 MB | - |
| `sounds/5.zip` | `secretheroes` | ShueShue/SecretHeroes:4 | 96 sonidos, 40.2 MB | - |
| `sounds/6.zip` | `pwt` | izil0n/Superheroes:0 | 141 sonidos, 17.2 MB | - |
| `sounds/7.zip` | `sabri` | Sqbri/Sabri-Enhanced-Heropack:0 | 105 sonidos, 4.7 MB | - |
| `sounds/8.zip` | `stellar` | TheTammy/StellarSounds:0 | 105 sonidos, 9.2 MB | main.black_adam_lightning_beam_1 -> black_adam_lightning_beam_1 |
| `sounds/9.zip` | `runnyhero` | runnyhero/heroes:2 | 18 sonidos, 0.8 MB | - |
| `sounds/10.zip` | `dhhp` | DERPZ774/Sounds:1 | 22 sonidos, 0.4 MB | shock.start.escrima -> suit/escrima_shock_start |
| `sounds/11.zip` | `hell` | shadow00dev/commisionSounds:2 | 9 sonidos, 0.9 MB | - |
| `sounds/12.zip` | `ahhp` | SymbioteSpidey/AdvancedFiskHeroes:2 | 51 sonidos, 14.8 MB | - |
| `sounds/13.zip` | `dinkle` | Sqbri/Commissions:0 | 20 sonidos, 0.5 MB | - |
| `sounds/14.zip` | `kryp` | Corpsexe/kryptonian:0, Corpsexe/kombat:0 | 32 sonidos, 14.9 MB | ssjon -> ssjon1 |
| `sounds/15.zip` | `swhp` | SymbioteSpidey/StarWarsHeroPack:0 | 44 sonidos, 5.0 MB | - |
| `sounds/16.zip` | `xeno` | Corpsexe/xenoheroes:0 | 89 sonidos, 10.2 MB | blackpantheroff -> blackpantheroff; brolyblock -> brolyblock1; brolyblock -> brolyblock2; brolyblock -> brolyblock3; brolyblock -> brolyblock4; brolyblock -> brolyblock5 ... |
| `sounds/17.zip` | `db` | kaynerz/dragonball:0 | 34 sonidos, 4.2 MB | injusticeon -> suit1; injusticeon -> suit10; injusticeon -> suit11; injusticeon -> suit12; injusticeon -> suit13; injusticeon -> suit14 ... |
