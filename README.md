# ai-use-case-canvas

Šablony a scoring model pro rozhodování, které LLM use cases má smysl implementovat jako první.

## O repozitáři

Když přemýšlím o nové LLM integraci, potřebuju rychle odhadnout: jaký má dopad, jak složitá je implementace, jaká data jsou k dispozici a co se stane když se to pokazí. Tyhle šablony jsem si vytvořil proto, abych to hodnocení měl konzistentní a nezapomněl na nic důležitého.

Nejde o rigidní framework — spíš o checklist který mi pomůže nevybrat si use case jen proto, že zní zajímavě.

## Obsah

- `templates/use-case-canvas.md` — šablona pro popis a hodnocení jednoho use case
- `templates/scoring-sheet.md` — scoring model pro porovnání více kandidátů

## Jak to používám

1. Sepíšu 5–10 kandidátních use casů.
2. Pro každý vyplním canvas (dopad, data, složitost, riziko).
3. Porovnám skóre a vyberu 1–2 pro první experiment.
4. Výsledky poslouží jako základ pro rozhodnutí co implementovat.

## Co to není

- Produkční systém ani implementace AI pipeline.
- Náhrada za právní nebo bezpečnostní review.

## License

MIT — viz LICENSE
