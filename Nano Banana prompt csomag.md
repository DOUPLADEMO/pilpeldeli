# PILPEL Deli: Nano Banana Pro prompt csomag (hangulat- és szekcióképek)

Összesen 14 kép. Minden prompt angolul van (a modell így ad jobb eredményt), a fejlécek magyarul.

## Beállítások minden képhez
- **Modell:** Nano Banana Pro, 2K felbontás (a nyomdai exporthoz 4K).
- **Referenciaképek:** töltsd fel a felsorolt csomagolásképeket. A modell így hűen adja vissza a címkét és a formát. A fájlok a projekt `img/cut/` mappájában vannak (átlátszó háttérrel), a hivatkozott név a fájlnév.
- **Először generáld le a 0. képet (stílus-horgony).** A többinél csatold hozzá referenciának, hogy az egész sorozat egy világban maradjon (fény, felület, színek).
- **Ne kérj szöveget a képre.** A feliratok a katalógusban vannak. A csomagolás saját címkéje (Ristoris, Sélia, Spadoni stb.) a referenciából jön.
- **Arcok nélkül.** A modell emberi arcot ne rajzoljon: csak kezek, hát, sziluett. Michael arcát külön fotóból vedd be.

## Közös stílusblokk (minden prompt végére másold)

```
STYLE: editorial food photography for a chef-to-chef wholesale catalogue. Dark, moody, quiet. Single soft window light from camera-left, natural, directional, deep shadows that still hold detail. Warm near-black background (around #1b1917), charred oak, dark slate or aged zinc surfaces. Muted olive-green and terracotta as the only colour accents, no saturated colour except the food itself. 85mm lens, f/2.8, shallow depth of field, subtle film grain, real textures (flour dust, oil sheen, condensation, crumbs). Generous negative space on the right third for page layout. No text, no captions, no watermark, no invented logos or labels, no stock-photo smiles, no visible faces, no plastic-looking food, no over-saturation, no fake bokeh circles.
```

---

## 0. Stílus-horgony (nincs termék)
**Arány:** 3:2 · **Hova:** referencia a többihez
```
A bare dark slate counter in a professional Italian kitchen at late afternoon. One linen cloth, a wooden spoon, a scatter of coarse sea salt, a few olive leaves. Empty and calm. {STYLE}
```

## 1. Címlap
**Arány:** 16:9 (a címlapon sávként vágódik) · **Referencia:** `sio-oil.png`, `sku-CF82.png`, `pk-017000.png`, `col-burrata-pack.png`
**Kik szerepeljenek:** Sélia olívaolaj kanna, Spadoni PZ4 liszt, Ristoris balzsamecet (5 l), Collebianco burrata. Négy tétel, nem több.
```
A chef's prep table seen from slightly above, four supplied products arranged with air between them: the green Sélia olive oil tin (reference 1), the Spadoni PZ4 flour bag (reference 2), the 5 L Ristoris balsamic vinegar jug (reference 3) and a Collebianco burrata cup (reference 4). Keep every label exactly as in the references. Between them: loose flour, a halved burrata with a single drizzle of olive oil, a few olives, torn basil. The table is dark slate, the background falls away into near-black. Items sit in the left two thirds, the right third stays quiet. {STYLE}
```

## 2. Rólunk: Pilpel Hungary
**Arány:** 16:9 · **Referencia:** nincs · **Kik:** friss zöldség-gyümölcs, nem Deli-termék
```
Open wooden crates of just-picked produce on a dark stone floor of a cool storage room, early morning light falling through a high window: ripe San Marzano style tomatoes still on the vine, lemons with leaves, bunches of basil and flat-leaf parsley, a crate of courgettes with flowers. A pair of weathered forearms in a dark apron lifts one crate at the edge of the frame, no face. Feels like produce that arrives the same day. {STYLE}
```

## 3. Michael története
**Arány:** 16:9 · **Referencia:** `sku-CF82.png`, `pk-017000.png` (opcionális: `ste-pack.png`) · **Kik:** Spadoni liszt, Ristoris balzsamecet, Steriltom pulp
```
A chef's pass in a professional kitchen after service, stainless steel and dark tile, seen from the cook's side. Backlit by a single warm pendant. In the foreground: the supplied Spadoni flour bag (reference 1) torn open at the top, flour dusted on the steel, a hand-written order ticket without readable text, a tasting spoon resting in red tomato pulp. On the right, blurred, the Ristoris balsamic jug (reference 2). Only a pair of hands and a white sleeve are visible, no face. Quiet, working, honest. {STYLE}
```

## 4. Kiemelt termékek: szekciónyitó
**Arány:** 2:1 · **Referencia:** `sio-oil.png`, `sio-halkidiki.jpg`, `sku-CF82.png`, `ste-pack.png`
**Kik:** olívaolaj, zöld olíva, liszt, High Brix paradicsompüré: a négy kiemelt termék.
```
Four hero products in a quiet row on a dark stone shelf, like a still-life: the Sélia olive oil tin (reference 1), a small black bowl of green Halkidiki olives (reference 2 as colour reference only), the Spadoni PZ4 flour bag (reference 3) and the Il Pizzaiolo tomato pulp tin and carton (reference 4). Warm side light picks out the edges of the packaging. A thin trail of oil and a dusting of flour connect the objects. Plenty of dark space above. {STYLE}
```

## 5. Prémium konzervek: szekciónyitó
**Arány:** 2:1 · **Referencia:** `pk-001517.png`, `pk-008122.png`, `pk-011500.png`, `pk-005000.png` (vagy `sku-005000.png`)
**Kik:** Ristoris szárított paradicsom filé (800 g), articsóka tasak, kapribogyó üveg, szardella.
```
A professional pantry shelf wall in deep shadow, three tiers of dark painted wood. The supplied Ristoris preserves (dried tomato tin, artichoke pouch, capers jar, anchovy jar, references 1 to 4) stand in clean uneven rows with labels facing out. A single shaft of light crosses the middle tier. A hand-lettered paper tag without readable text hangs from one shelf edge. Orderly, abundant, kitchen-ready. {STYLE}
```

## 6. Friss bivalytejtermékek: szekciónyitó
**Arány:** 2:1 · **Referencia:** `col-burrata-pack.png`, `col-m5-pack.png`, `col-smoked-pack.png`, `col-m5.jpg`
**Kik:** burrata, mozzarella di bufala (5 × 50 g), füstölt mozzarella.
```
A dark marble slab with two fresh burrata and a scatter of small mozzarella balls, one torn open so the cream spills out slowly, a thread of green olive oil, a few basil leaves, coarse salt. Behind them, slightly out of focus, the supplied Collebianco packs (references 1 to 3) stand in a row, labels intact. The cheese is glossy and milky, cool light, condensation on the cups. Tight on texture. {STYLE}
```

## 7. Siouras: sztori (Görögország, olíva)
**Arány:** 4:3 · **Referencia:** `sio-kalamata.jpg`, `sio-halkidiki.jpg`
**Kik:** Kalamata és zöld olíva.
```
An old olive tree grove in the Peloponnese at golden hour, seen from low in the grass, silver leaves backlit. In the foreground on a rough stone wall: a wooden bowl of dark Kalamata olives and a bowl of large green olives, a small knife, a sprig of leaves. Warm Mediterranean evening light, dark foreground, deep green shadows. No people. {STYLE}
```

## 8. Douzenis: sztori (olívaolaj termelő)
**Arány:** 4:3 · **Referencia:** `sio-oil.png`
**Kik:** Sélia olívaolaj kanna.
```
Extra virgin olive oil being poured in a thin golden stream from a stainless steel jug into a dark ceramic dish, filmed from the side with a dark stone background. Next to it the supplied green Sélia 5 L tin (reference 1) with its label as in the reference, a branch of olive leaves lying across the stone. Oil sheen, rim light on the stream, calm and precise. {STYLE}
```

## 9. Molino Spadoni: sztori (lisztmalom)
**Arány:** 4:3 · **Referencia:** `sku-CF82.png`, `sku-CF133AVPN.png`, `sku-E78M05.png`
**Kik:** PZ4, Chella Llà, 7 gabonás sötét pizzaliszt.
```
Flour in motion: a cloud of white flour caught mid-air above a dark wooden bench, backlit so every particle glows. Three of the supplied Spadoni bags (references 1 to 3) stand in the background, labels intact and slightly out of focus. A hand pressing a ball of pizza dough into the flour in the foreground, no face. Ears of wheat on the bench. {STYLE}
```

## 10. Steriltom: sztori (High Brix paradicsom)
**Arány:** 4:3 · **Referencia:** `ste-pack.png`
**Kik:** Il Pizzaiolo 10 kg-os doboz és konzerv.
```
Vine-ripened plum tomatoes in a shallow dark crate, some cut open to show dense flesh and few seeds, water drops on the skin. In the background the supplied Il Pizzaiolo carton and tin (reference 1) keep their printed artwork exactly as given. A wooden spoon lifts a thick, glossy ribbon of red pulp that falls back into a steel pan. Deep red against near-black, sharp focus on the pulp. {STYLE}
```

## 11. Ristoris: sztori (prémium konzervek)
**Arány:** 4:3 · **Referencia:** `pk-015010.png`, `pk-099009.png`, `pk-009053.png`, `pk-013000.png`
**Kik:** amarena meggy, pisztáciapaszta, grillezett paprika, pesto.
```
A flat lay from directly above on dark zinc: four supplied Ristoris items (amarena cherry tin, pistachio paste bucket, grilled pepper tin, pesto tin, references 1 to 4) with their lids partly open to show the contents, plus loose amarena cherries with syrup drops, a spoon of green pistachio paste, torn basil. Careful composition, equal spacing, a little imperfection in the spills. {STYLE}
```

## 12. Collebianco: sztori (bivalyfarm)
**Arány:** 4:3 · **Referencia:** `col-m5.jpg`
**Kik:** mozzarella di bufala (opcionálisan füstölt).
```
Water buffalo grazing in a green pasture in Campania at dawn, low mist, soft morning light, a stone farmhouse far behind. Natural documentary framing, animals calm, no people, no text. The cooler blue-green of the landscape echoes the blue of the farm's ceramic plates. {STYLE: keep dark and quiet in the foreground, lighter only in the mist}
```

## 13. Desszert és sütés: kategóriakép (opcionális)
**Arány:** 3:2 · **Referencia:** `pk-099009.png`, `pk-015591.png`, `pk-015010.png`, `pk-014201.png`
**Kik:** pisztáciapaszta, mogyorókrém, amarena meggy, pisztáciagranulátum.
```
A pastry station in low light: a dark marble board with a quenelle of pistachio paste, a spoon of hazelnut spread, amarena cherries with syrup, crushed pistachio, a small half-assembled dessert. The supplied Ristoris pistachio paste bucket, hazelnut spread bucket and amarena tin (references 1 to 3) stand behind, labels intact. Warm, glossy, slightly indulgent. {STYLE}
```

## 14. Citromlé, ecetek, gabonák: kategóriakép (opcionális)
**Arány:** 3:2 · **Referencia:** `pk-017000.png`, `pk-017035.png`, `pk-017042.png`, `pk-017049.png`
**Kik:** balzsamecet, citromlé, fehér- és vörösborecet, polenta, arborio rizs.
```
A line of four supplied Ristoris bottles (balsamic jug, lemon juice, white wine vinegar, red wine vinegar, references 1 to 4) on a dark wood counter, each backlit so the liquid glows: deep brown, green, pale gold, ruby. In front, small piles of polenta and Arborio rice on slate, a halved lemon, a glass dish with a few drops of balsamic. {STYLE}
```

---

## Hova kerül melyik kép a katalógusban
- **0:** csak referencia, nem kerül a katalógusba.
- **1:** címlap hangulatkép.
- **2:** „Rólunk” oldal sávja.
- **3:** Michael története oldal sávja.
- **4, 5, 6:** a három szekciónyitó (kiemelt, konzerv, bivaly).
- **7 és 8:** Siouras és Douzenis sztori.
- **9, 10, 11, 12:** Spadoni, Steriltom, Ristoris, Collebianco sztori.
- **13, 14:** kategóriakép (jelenleg nincs hely a katalógusban, ha kell, beépítem).

## Tippek
- A 4–6 képnél a modell néha átrendezi a termékeket vagy átírja a címkét. Ilyenkor generáld újra, ne javíttasd tovább. Ha a címke romlik, a csomagolást érdemes utólag Photoshopban cserélni a valódi packshotra.
- Ugyanazt a fényt tartsd mindenhol: balról jövő ablakfény, hideg-semleges árnyék, meleg csúcsfény.
- Ha kész, töltsd fel egy mappába, és bekötöm őket kód szerint a megfelelő helyekre.
