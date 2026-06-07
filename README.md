# academica-brave

Goggles de Brave Search per al projecte **Acadèmica** — motor de cerca educatiu per a Catalunya (primària, ESO, batxillerat i FP).

## Fitxers

| Fitxer | Categoria SearXNG | Descripció |
|--------|-------------------|------------|
| `educacio-general.goggle` | General | 39 dominis acadèmics i educatius catalans. Institucions (xtec.cat, edu.cat), divulgació (wikipedia.org, raco.cat), editorials de secundària i FP, universitats catalanes, recursos didàctics. |
| `educacio-it.goggle` | TIC | 44 dominis: tots els de General (pesos menors) + dominis especialitzats TIC al pes màxim: github.com, github.io, w3schools.com, freecodecamp.org, stackoverflow.com. |

## URLs raw

```
https://raw.githubusercontent.com/pluralcamp/academica-brave/refs/heads/main/educacio-general.goggle
https://raw.githubusercontent.com/pluralcamp/academica-brave/refs/heads/main/educacio-it.goggle
```

## Estructura dels Goggles

Cada fitxer boosting els dominis educatius per pes (1–3) i descarta xarxes socials i comerç electrònic.

Els fitxers es generen automàticament des de `goggle_config.py` (repositori privat del projecte) amb `python generate_goggles.py`.
