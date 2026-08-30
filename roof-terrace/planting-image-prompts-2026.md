# Roof Terrace — AI image prompts for artist's impressions

**Flat 6, 22 Sussex Square, Brighton** · 30 August 2026 · companion to [`planting-plan.md`](planting-plan.md)

These regenerate the artist's impressions against the **current** planting. One prompt per planter and per
pot group, plus whole-terrace views and a set of winter tests.

---

## 1. What changed from the first set, and why

| Change | Reason |
|---|---|
| **Describe what a plant *looks like*, not its Latin name** | No image model reliably knows *Pittosporum tenuifolium* 'Tom Thumb' from *Myrtus communis* subsp. *tarentina*. Ask for "a rounded evergreen dome of deep purple-bronze small leaves" and you get it. Ask for the cultivar name and you get a guess. This is the single biggest improvement |
| **Correct materials** | The old prompts said "sandstone-coloured large-format porcelain". It is now **buff granite-aggregate, 600×400 rectangular flags**, and the planters are **silver-grey salvaged deck boards with visible bolt heads** |
| **Gravel mulch specified** | It changes the whole read of the image — pale gravel under silver planting is the look we are actually after |
| **One bed per image** | Asking for the whole terrace produces mush. Compose the wide views separately, from the three scene prompts in §6 |
| **A fixed camera line** | Same lens and light in every prompt, so the set looks like one photographer rather than twelve |
| **A February version of every bed** | The winter structure is the thing this scheme is really being judged on. If a bed looks empty in the February render, that is worth knowing now rather than in year two |
| **A proper negative prompt** | Generators default to lush, tropical, over-flowered gardens. Most of the work is telling them not to |
| **Wind-combed, lean, low** | Added to every prompt. Roof planting that looks like a border in Surrey is wrong |

---

## 2. Which tool

You used DALL·E 3 for the originals. Honest answer: **it is still perfectly usable, and it is free if you
already pay for ChatGPT** — but it is no longer the best at this particular job.

| Tool | For this job |
|---|---|
| **Google Gemini / Imagen** | **My first suggestion.** Strongest prompt adherence of the current crop, which is what matters when you are asking for eighteen specific plant forms in one frame. Photorealistic, and cheap or included |
| **Flux** (Black Forest Labs — via fal.ai, Freepik, Replicate) | Excellent photorealism and good adherence, pay-per-image and inexpensive. Best if you want to generate a lot of variants cheaply |
| **Midjourney** | Still makes the most *beautiful* garden images — light and atmosphere nothing else matches. But it takes liberties: it will invent plants and prettify. Best for the wide scene-setting views in §6, less good for accurate bed studies |
| **DALL·E 3** (ChatGPT) | Follows long prose well, which suits these prompts, but is behind on photorealism and fine botanical texture. Fine if you don't want another subscription |

**Practical advice regardless of tool:** generate the **bed studies** in whichever tool has the best prompt
adherence, and the **wide views** in Midjourney. And accept that **no generator will render twenty named
species accurately** — these images are for conveying character, atmosphere and massing, not for
identification. Nobody should plant from them.

*(This area moves fast — worth a five-minute check on what's current before you commit to a subscription.)*

---

## 3. The style anchor

Paste this into **every** prompt, after the bed-specific text.


> **Setting (use verbatim, every prompt):** A private roof terrace three storeys above the seafront at
> Kemp Town, Brighton, on a Grade I listed Regency building. Floor is large-format buff/sand granite-aggregate
> paving, 600×400mm rectangular flags laid on pedestals with fine open joints. Planters are freestanding
> boxes clad in **salvaged hardwood decking weathered to silver-grey**, random staggered board lengths, with
> visible round bolt-heads at regular intervals and a chunky flat timber cap board on top. Soil surface is
> **pale gravel mulch**. Beyond the terrace, sea haze and rooftops. Real English coastal light.

> 35mm lens, f/5.6, eye level, natural light, shallow-but-honest depth of field, editorial garden-magazine photography, photorealistic, not illustrated.


---

## 4. The negative prompt

> **Negative / avoid (append or use as negative prompt):** no tropical or subtropical planting, no
> palms, no banana plants, no hostas or ferns, no lawn or turf, no bedding annuals, no red orange or hot-pink
> flowers, no plastic pots, no black or charcoal planters, no decking, no pergola, no fairy lights, no
> oversized flowers, no symmetrical formal parterre, no people, no text or watermark, not over-saturated,
> not HDR.

---

## 5. The beds

### N1(E) — Narrow terrace — **east** side

*7.2m long × 600mm deep · 500mm high · **open steel railings, 1,100mm above FFL — no parapet***

**Summer (late June, mid-afternoon):**

> Photo-realistic garden photography of a single planted bed on a Brighton seafront roof terrace. The planter: 7.2m long × 600mm deep , 500mm high , **open steel railings, 1,100mm above FFL — no parapet**, clad in silver-grey salvaged deck boards with visible bolt heads and a flat timber cap. Planting, back to front: 1 a fine-leaved evergreen shrub-tree ~2m, tiny wavy silver-green leaves on near-black twigs, furnished to the ground; 2 a dense rounded evergreen dome ~1.3m, small glossy dark leaves, white powder-puff flowers; 2 a rounded evergreen dome ~1m of deep purple-bronze small leaves; 1 a naturally spherical clipped-looking evergreen ball ~70cm, tiny mid-green leaves; 1 an architectural evergreen with blue-green whorled foliage and big domed acid-green flower heads; 1 a low silver-felted mound with grey-white leaf undersides; 3 silver felted lamb's-ear leaves in a soft mat; 2 a haze of tiny white-and-pink daisies spilling over the rim; 2 compact English lavender, deep violet spikes over grey foliage; 2 semi-prostrate rosemary arching over the edge, needle foliage, vivid blue flowers; 1 a loose mauve-blue haze of catmint; 1 a tight bright apple-green evergreen dome with short white flower spikes; 1 narrow violet flower spikes on jet-black stems; 1 a small shrubby sage with purple-and-white bicolour flowers; 1 tight grassy cushions with pink pompom flowers; 1 small spiky blue-grey grass tussocks; 1 grey-blue evergreen mats with small fringed pink clove-scented flowers; 1 slender branching stems topped with small mauve-purple flower clusters; 1 succulent blue-green rock samphire with flat greenish umbels. Everything low, lean and wind-combed — nothing lush, nothing overfed. Pale gravel mulch visible between the plants. Silver and grey-green foliage dominant; flowers only in blue, purple and white. Late June, mid-afternoon, bright but slightly hazy coastal light.

**Winter test (early February, overcast):**

> Same bed, same viewpoint, **early February, flat overcast light**. Deciduous material cut back; the evergreen domes, silver mounds and standing seed heads carrying the composition. Crocus and dwarf iris opening through the gravel. Show honestly how much structure is left — do not add summer flowers.

<sub>*Design intent: The long east flank, and the first thing you see when you step out of the study. Seven metres of silvered timber with a loose twiggy evergreen wall behind it: a single **Silver Sheen** pittosporum standing above the rest, two myrtles and two purple-bronze domes knitting together into a screen the wind can pass *through* rather than pile against. In February the rosemary is already blue and there are crocus at your feet. By June it is lavender, catmint and the small pink-white daisies of *Erigeron*, which will have seeded itself into the paving joints by year three. July brings drumstick alliums up through it all on leafless stems that don't mind the gale. Autumn is stonecrop going dusky pink then rust, and the seed heads stay standing until you cut them in February.*</sub>

---

### N1(N) — Narrow terrace — **north** leg of the L

*1.8m long × 800mm deep · 500mm high · solid parapet 1,300mm above FFL*

**Summer (late June, mid-afternoon):**

> Photo-realistic garden photography of a single planted bed on a Brighton seafront roof terrace. The planter: 1.8m long × 800mm deep , 500mm high , solid parapet 1,300mm above FFL, clad in silver-grey salvaged deck boards with visible bolt heads and a flat timber cap. Planting, back to front: 1 a gnarled multi-stem olive tree, ~2m, twisted silver-grey trunks, narrow silver-green leaves; 1 a dense rounded evergreen dome ~1.3m, small glossy dark leaves, white powder-puff flowers; 1 silver felted lamb's-ear leaves in a soft mat; 1 a haze of tiny white-and-pink daisies spilling over the rim; 1 tight grassy cushions with pink pompom flowers; 1 small spiky blue-grey grass tussocks. Everything low, lean and wind-combed — nothing lush, nothing overfed. Pale gravel mulch visible between the plants. Silver and grey-green foliage dominant; flowers only in blue, purple and white. Late June, mid-afternoon, bright but slightly hazy coastal light.

**Winter test (early February, overcast):**

> Same bed, same viewpoint, **early February, flat overcast light**. Deciduous material cut back; the evergreen domes, silver mounds and standing seed heads carrying the composition. Crocus and dwarf iris opening through the gravel. Show honestly how much structure is left — do not add summer flowers.

<sub>*Design intent: The turn of the L, and the head of the steps up to the main terrace — so it works as a full stop rather than a run. One gnarled multi-stem **olive** does that job, with a myrtle beside it and sea thrift and blue fescue at its feet. The solid parapet behind gives it more shelter than anywhere else on this terrace, which is why the olive goes here rather than out on the exposed run.*</sub>

---

### N2 — Narrow terrace — mid-east square

*1.2 × 1.2m · 500mm high · built integral with N1*

**Summer (late June, mid-afternoon):**

> Photo-realistic garden photography of a single planted bed on a Brighton seafront roof terrace. The planter: 1.2 × 1.2m , 500mm high , built integral with N1, clad in silver-grey salvaged deck boards with visible bolt heads and a flat timber cap. Planting, back to front: 1 upright bronze-purple sword-shaped leaves, architectural; 4 compact English lavender, deep violet spikes over grey foliage; 2 small spiky blue-grey grass tussocks; 1 fleshy blue-grey rosettes topped with flat dusky-pink flower heads on purple stems. Everything low, lean and wind-combed — nothing lush, nothing overfed. Pale gravel mulch visible between the plants. Silver and grey-green foliage dominant; flowers only in blue, purple and white. Late June, mid-afternoon, bright but slightly hazy coastal light.

**Winter test (early February, overcast):**

> Same bed, same viewpoint, **early February, flat overcast light**. Deciduous material cut back; the evergreen domes, silver mounds and standing seed heads carrying the composition. Crocus and dwarf iris opening through the gravel. Show honestly how much structure is left — do not add summer flowers.

<sub>*Design intent: A punctuation mark in the middle of the east run: one bronze **Phormium** throwing hard vertical sword-leaves out of a soft cushion of lavender and blue fescue. It exists to stop seven metres of planting reading as a hedge. In autumn the stonecrop and a few *Nerine* keep it going after the lavender is over.*</sub>

---

### N3 — Narrow terrace — mid-west square, beside the outdoor kitchen

*1.2 × 1.2m · 500mm high*

**Summer (late June, mid-afternoon):**

> Photo-realistic garden photography of a single planted bed on a Brighton seafront roof terrace. The planter: 1.2 × 1.2m , 500mm high, clad in silver-grey salvaged deck boards with visible bolt heads and a flat timber cap. Planting, back to front: 2 upright rosemary, dark needle foliage; 4 low creeping thyme mats, some silver-variegated; 2 marjoram with purple-flushed bracts, covered in bees; 2 purple-leaved culinary sage. Everything low, lean and wind-combed — nothing lush, nothing overfed. Pale gravel mulch visible between the plants. Silver and grey-green foliage dominant; flowers only in blue, purple and white. Late June, mid-afternoon, bright but slightly hazy coastal light.

**Winter test (early February, overcast):**

> Same bed, same viewpoint, **early February, flat overcast light**. Deciduous material cut back; the evergreen domes, silver mounds and standing seed heads carrying the composition. Crocus and dwarf iris opening through the gravel. Show honestly how much structure is left — do not add summer flowers.

<sub>*Design intent: The cook's square, one step from the outdoor kitchen worktop and planted entirely with things you would actually pick — upright rosemary, four kinds of thyme, purple sage, ornamental marjoram that the butterflies mob in August. Evergreen and usable in every month, which is the point: you want to be able to cut something for dinner in January.*</sub>

---

### N4 — Lift over-run — **the aromatic picking bed**

*2.1 × 2.1m · **400mm deep box** · planting kept under 700mm*

**Summer (late June, mid-afternoon):**

> Photo-realistic garden photography of a single planted bed on a Brighton seafront roof terrace. The planter: 2.1 × 2.1m , **400mm deep box** , planting kept under 700mm, clad in silver-grey salvaged deck boards with visible bolt heads and a flat timber cap. Planting, back to front: 1 a low glossy dark evergreen with tiny cream tassel flowers; 1 spiny architectural evergreen leaves under clusters of apple-green cups; 2 clumps of chives with mauve pompom flowers; 2 soft green marjoram in flower; 1 sorrel; 5 trailing rosemary cascading over the edge; 2 upright rosemary, dark needle foliage; 3 compact English lavender, deep violet spikes over grey foliage; 2 a tight silver-grey filigree dome; 2 a small shrubby sage with purple-and-white bicolour flowers; 6 low creeping thyme mats, some silver-variegated; 2 marjoram with purple-flushed bracts, covered in bees; 2 grey-green felted culinary sage; 2 a low wiry evergreen herb; 2 slender bright green tarragon. Everything low, lean and wind-combed — nothing lush, nothing overfed. Pale gravel mulch visible between the plants. Silver and grey-green foliage dominant; flowers only in blue, purple and white. Late June, mid-afternoon, bright but slightly hazy coastal light.

**Winter test (early February, overcast):**

> Same bed, same viewpoint, **early February, flat overcast light**. Deciduous material cut back; the evergreen domes, silver mounds and standing seed heads carrying the composition. Crocus and dwarf iris opening through the gravel. Show honestly how much structure is left — do not add summer flowers.

<sub>*Design intent: You brush past this every single time you go out, so it is built for scent above everything. A low aromatic mound on top of the lift over-run — prostrate rosemary trailing over all four edges, thyme, lavender, savory, tarragon, sage — with the sun-lovers on the north and east where the light is, and the south edge, in the permanent lee of the flat wall, given over to a different palette entirely: **Sarcococca** and a hellebore, with snowdrops and cyclamen threaded underneath. In January that shaded band is the best-smelling square metre on the terrace. In July the whole thing hums.*</sub>

---

### M1(W) — Main terrace — **west** edge of the raised dining deck (FA2)

*≈4.5m long × 600mm deep · 500mm high, on the +300mm raised deck*

**Summer (late June, mid-afternoon):**

> Photo-realistic garden photography of a single planted bed on a Brighton seafront roof terrace. The planter: ≈4.5m long × 600mm deep , 500mm high, on the +300mm raised deck, clad in silver-grey salvaged deck boards with visible bolt heads and a flat timber cap. Planting, back to front: 1 a fine-leaved evergreen shrub-tree ~2m, tiny wavy silver-green leaves on near-black twigs, furnished to the ground; 1 a dense rounded evergreen dome ~1.3m, small glossy dark leaves, white powder-puff flowers; 1 a rounded evergreen dome ~1m of deep purple-bronze small leaves; 1 an architectural evergreen with blue-green whorled foliage and big domed acid-green flower heads; 1 a low silver-felted mound with grey-white leaf undersides; 1 compact English lavender, deep violet spikes over grey foliage; 1 compact English lavender, soft lavender-blue spikes; 2 a loose mauve-blue haze of catmint; 1 narrow violet flower spikes on jet-black stems; 2 silver felted lamb's-ear leaves in a soft mat; 1 a haze of tiny white-and-pink daisies spilling over the rim; 1 a tight bright apple-green evergreen dome with short white flower spikes; 1 fleshy blue-grey rosettes topped with flat dusky-pink flower heads on purple stems; 1 a compact metallic-silver evergreen mound with white trumpet flowers. Everything low, lean and wind-combed — nothing lush, nothing overfed. Pale gravel mulch visible between the plants. Silver and grey-green foliage dominant; flowers only in blue, purple and white. Late June, mid-afternoon, bright but slightly hazy coastal light.

**Winter test (early February, overcast):**

> Same bed, same viewpoint, **early February, flat overcast light**. Deciduous material cut back; the evergreen domes, silver mounds and standing seed heads carrying the composition. Crocus and dwarf iris opening through the gravel. Show honestly how much structure is left — do not add summer flowers.

<sub>*Design intent: The wall behind the dining table, and the south-westerly gale flank — the hardest-working planting on the terrace. A **Silver Sheen** pittosporum furnished to the ground, a myrtle, a purple 'Tom Thumb' dome and a *Brachyglottis*, with *Euphorbia wulfenii* throwing acid-green heads up through them from February. In front, at table height: lavender, catmint, dark-stemmed **'Caradonna'** salvia, silver lamb's ears and a *Convolvulus*. It sits behind you when you look north-east, so it can be as tall as it likes without touching the view. Alliums and white 'Thalia' daffodils come through it in spring; *Hylotelephium* holds the autumn.*</sub>

---

### M1(N) — Main terrace — **north** edge of the raised dining deck

*≈1.1m long × 600mm deep · 500mm high*

**Summer (late June, mid-afternoon):**

> Photo-realistic garden photography of a single planted bed on a Brighton seafront roof terrace. The planter: ≈1.1m long × 600mm deep , 500mm high, clad in silver-grey salvaged deck boards with visible bolt heads and a flat timber cap. Planting, back to front: 1 a naturally spherical clipped-looking evergreen ball ~70cm, tiny mid-green leaves; 1 a haze of tiny white-and-pink daisies spilling over the rim; 1 silver felted lamb's-ear leaves in a soft mat; 1 a loose mauve-blue haze of catmint. Everything low, lean and wind-combed — nothing lush, nothing overfed. Pale gravel mulch visible between the plants. Silver and grey-green foliage dominant; flowers only in blue, purple and white. Late June, mid-afternoon, bright but slightly hazy coastal light.

**Winter test (early February, overcast):**

> Same bed, same viewpoint, **early February, flat overcast light**. Deciduous material cut back; the evergreen domes, silver mounds and standing seed heads carrying the composition. Crocus and dwarf iris opening through the gravel. Show honestly how much structure is left — do not add summer flowers.

<sub>*Design intent: Deliberately the quietest planter on the terrace. It sits beside the three steps down to the lounge and directly in the north-east view corridor, so it is one clipped **'Golf Ball'** dome and a low skirt of catmint, lamb's ears and *Erigeron* — enough to soften the step edge, not enough to interrupt anything. Crocus and dwarf daffodils in spring, and then it gets out of the way.*</sub>

---

### M2(E) — north half — Main terrace, east parapet — **north half (≈2.5m)**

*1,000mm deep · 700mm high planter · raised level, parapet 1,000mm above FFL*

**Summer (late June, mid-afternoon):**

> Photo-realistic garden photography of a single planted bed on a Brighton seafront roof terrace. The planter: 1,000mm deep , 700mm high planter , raised level, parapet 1,000mm above FFL, clad in silver-grey salvaged deck boards with visible bolt heads and a flat timber cap. Planting, back to front: 2 a multi-stem evergreen small tree with peeling cinnamon-red bark, clear trunks to head height, glossy dark leaves, white bell flowers and red strawberry-like fruit together; 2 trailing rosemary cascading over the edge; 2 tight grassy cushions with pink pompom flowers; 2 grey-blue evergreen mats with small fringed pink clove-scented flowers; 2 small spiky blue-grey grass tussocks; 2 a dense evergreen mat smothered in white flower heads; 2 trailing blue-grey succulent whorls draped over the rim; 1 a haze of tiny white-and-pink daisies spilling over the rim. Everything low, lean and wind-combed — nothing lush, nothing overfed. Pale gravel mulch visible between the plants. Silver and grey-green foliage dominant; flowers only in blue, purple and white. Late June, mid-afternoon, bright but slightly hazy coastal light.

**Winter test (early February, overcast):**

> Same bed, same viewpoint, **early February, flat overcast light**. Deciduous material cut back; the evergreen domes, silver mounds and standing seed heads carrying the composition. Crocus and dwarf iris opening through the gravel. Show honestly how much structure is left — do not add summer flowers.

<sub>*Design intent: The cleverest bit of the scheme, and the only place it screens at high level while staying open at low. Two multi-stem **strawberry trees**, crown-lifted so their canopies start well above head height, intercept the diagonal sightline from the neighbours' upper windows down into the hot tub — while underneath them there is nothing but mats: prostrate rosemary, sea thrift, cheddar pinks, blue fescue, candytuft, the blue-grey trailing whorls of *Euphorbia myrsinites*. You look straight out over them to the Downs. In late October the two trees flower white and fruit red at the same time, which almost nothing else does, and the birds take the fruit.*</sub>

---

### M2(E) — south half — Main terrace, east parapet — **south half (≈2.6m)**

*1,000mm deep · 700mm high planter · raised level, parapet 1,000mm above FFL*

**Summer (late June, mid-afternoon):**

> Photo-realistic garden photography of a single planted bed on a Brighton seafront roof terrace. The planter: 1,000mm deep , 700mm high planter , raised level, parapet 1,000mm above FFL, clad in silver-grey salvaged deck boards with visible bolt heads and a flat timber cap. Planting, back to front: 2 a glossy dark-green evergreen shrub ~1.6m carrying small shell-pink flowers; 1 a very bright silver-white loose shrub, small mealy leaves; 1 a dense rounded evergreen dome ~1.3m, small glossy dark leaves, white powder-puff flowers; 1 an architectural evergreen with blue-green whorled foliage and big domed acid-green flower heads; 1 a rock rose with tissue-paper white flowers each blotched maroon at the base; 1 a silver-blue evergreen with small blue two-lipped flowers; 1 a blue-grey shrub with clusters of pale lemon pea-flowers; 1 an arching semi-evergreen with small white-and-blush trumpet flowers; 2 silver felted lamb's-ear leaves in a soft mat; 1 a haze of tiny white-and-pink daisies spilling over the rim; 1 compact English lavender, deep violet spikes over grey foliage; 1 a small shrubby sage with purple-and-white bicolour flowers; 1 steel-blue thistle heads over silver-veined leaves; 1 fleshy blue-grey rosettes topped with flat dusky-pink flower heads on purple stems; 1 lavender-blue daisies with yellow centres; 1 an airy lilac haze of sea lavender; 3 low grassy foliage with large lilac-blue iris flowers at ground level. Everything low, lean and wind-combed — nothing lush, nothing overfed. Pale gravel mulch visible between the plants. Silver and grey-green foliage dominant; flowers only in blue, purple and white. Late June, mid-afternoon, bright but slightly hazy coastal light.

**Winter test (early February, overcast):**

> Same bed, same viewpoint, **early February, flat overcast light**. Deciduous material cut back; the evergreen domes, silver mounds and standing seed heads carrying the composition. Crocus and dwarf iris opening through the gravel. Show honestly how much structure is left — do not add summer flowers.

<sub>*Design intent: All the height on the east run is gathered here, away from the view corridor: a 1.5–2m informal evergreen block that shelters both the lounge and the dining deck from the east. Escallonia for pink flower from June to September, myrtle for white and scented in August, *Abelia* to carry it into October, *Coronilla* for the depths of winter. The front ribbon is where the autumn lives — *Hylotelephium*, *Aster* 'Mönch' in lavender-blue, sea lavender drying on the plant — and three *Iris unguicularis* tucked at the sunny foot of it, flowering lilac in November when nothing else is.*</sub>

---

### M2(S) — Main terrace — **south** return of the SE L

*3.5m external / 2.5m internal × **1,000mm deep** · 700mm high · raised level, parapet 1,000mm above FFL*

**Summer (late June, mid-afternoon):**

> Photo-realistic garden photography of a single planted bed on a Brighton seafront roof terrace. The planter: 3.5m external / 2.5m internal × **1,000mm deep** , 700mm high , raised level, parapet 1,000mm above FFL, clad in silver-grey salvaged deck boards with visible bolt heads and a flat timber cap. Planting, back to front: 1 a gnarled multi-stem olive tree, ~2m, twisted silver-grey trunks, narrow silver-green leaves; 1 a very bright silver-white loose shrub, small mealy leaves; 1 an architectural evergreen with blue-green whorled foliage and big domed acid-green flower heads; 1 a rock rose with tissue-paper white flowers each blotched maroon at the base; 1 a silver-blue evergreen with small blue two-lipped flowers; 1 a blue-grey shrub with clusters of pale lemon pea-flowers; 1 a low silver-felted mound with grey-white leaf undersides; 1 a woolly grey-green shrub with whorled soft-yellow flowers stacked up the stems; 1 silver felted lamb's-ear leaves in a soft mat; 1 a haze of tiny white-and-pink daisies spilling over the rim; 1 narrow violet flower spikes on jet-black stems; 1 an airy blue haze on white silver stems; 1 slender branching stems topped with small mauve-purple flower clusters; 1 steel-blue thistle heads over silver-veined leaves; 1 a mound of grey-green foliage with continuous mauve-purple wallflower spikes; 1 succulent blue-green rock samphire with flat greenish umbels; 2 low grassy foliage with large lilac-blue iris flowers at ground level. Everything low, lean and wind-combed — nothing lush, nothing overfed. Pale gravel mulch visible between the plants. Silver and grey-green foliage dominant; flowers only in blue, purple and white. Late June, mid-afternoon, bright but slightly hazy coastal light.

**Winter test (early February, overcast):**

> Same bed, same viewpoint, **early February, flat overcast light**. Deciduous material cut back; the evergreen domes, silver mounds and standing seed heads carrying the composition. Crocus and dwarf iris opening through the gravel. Show honestly how much structure is left — do not add summer flowers.

<sub>*Design intent: The heritage picture, and the one you look straight at from the dining table: a gnarled multi-stem **olive** rising out of a silver thicket, in the deepest planter on the terrace and outside every protected sightline, so it is allowed real height. Around it, tree purslane at its brightest silver, *Euphorbia*, a *Cistus* opening white-with-a-maroon-blotch in June, silver-blue *Teucrium*, and *Coronilla* flowering pale lemon through the middle of winter. At the front, sea holly, Russian sage and *Verbena* carry it from midsummer into October, and rock samphire — a Sussex shingle native — sits on the edge as a quiet argument that this planting belongs to this coast.*</sub>

---

### M4 — Main terrace — **north** of the lounge seating

*2.70m long × 600mm deep · 700mm high planter · parapet here is 1,300mm above FFL*

**Summer (late June, mid-afternoon):**

> Photo-realistic garden photography of a single planted bed on a Brighton seafront roof terrace. The planter: 2.70m long × 600mm deep , 700mm high planter , parapet here is 1,300mm above FFL, clad in silver-grey salvaged deck boards with visible bolt heads and a flat timber cap. Planting, back to front: 1 a rounded evergreen dome ~1m of deep purple-bronze small leaves; 2 a tight bright apple-green evergreen dome with short white flower spikes; 1 a tight silver-grey filigree dome; 2 fleshy blue-grey rosettes topped with flat dusky-pink flower heads on purple stems; 2 trailing rosemary cascading over the edge; 2 tight grassy cushions with pink pompom flowers; 2 grey-blue evergreen mats with small fringed pink clove-scented flowers; 2 trailing blue-grey succulent whorls draped over the rim. Everything low, lean and wind-combed — nothing lush, nothing overfed. Pale gravel mulch visible between the plants. Silver and grey-green foliage dominant; flowers only in blue, purple and white. Late June, mid-afternoon, bright but slightly hazy coastal light.

**Winter test (early February, overcast):**

> Same bed, same viewpoint, **early February, flat overcast light**. Deciduous material cut back; the evergreen domes, silver mounds and standing seed heads carrying the composition. Crocus and dwarf iris opening through the gravel. Show honestly how much structure is left — do not add summer flowers.

<sub>*Design intent: A low green fringe on the north side of the lounge, capped at a metre so the Downs stay visible from the sauna. It grades along its length: a purple 'Tom Thumb' dome and two bright green *Hebe* at the west end where there is room, dropping to prostrate rosemary, sea thrift, cheddar pinks and trailing *Euphorbia myrsinites* at the east end where the sightline is tightest. Two *Hylotelephium* give it an autumn, and *Nerine* comes up pink out of it in October.*</sub>

---

### M7 — Main terrace — **west** of the hot tub, between tub and building

*2.0m long × 600mm deep · finishes 150mm above the tub rim*

**Summer (late June, mid-afternoon):**

> Photo-realistic garden photography of a single planted bed on a Brighton seafront roof terrace. The planter: 2.0m long × 600mm deep , finishes 150mm above the tub rim, clad in silver-grey salvaged deck boards with visible bolt heads and a flat timber cap. Planting, back to front: 1 a small multi-stem olive, ~1.4m, silver-grey foliage; 1 a dense rounded evergreen dome ~1.3m, small glossy dark leaves, white powder-puff flowers; 2 a tight bright apple-green evergreen dome with short white flower spikes; 1 semi-prostrate rosemary arching over the edge, needle foliage, vivid blue flowers; 1 a compact metallic-silver evergreen mound with white trumpet flowers; 1 low creeping thyme mats, some silver-variegated. Everything low, lean and wind-combed — nothing lush, nothing overfed. Pale gravel mulch visible between the plants. Silver and grey-green foliage dominant; flowers only in blue, purple and white. Late June, mid-afternoon, bright but slightly hazy coastal light.

**Winter test (early February, overcast):**

> Same bed, same viewpoint, **early February, flat overcast light**. Deciduous material cut back; the evergreen domes, silver mounds and standing seed heads carrying the composition. Crocus and dwarf iris opening through the gravel. Show honestly how much structure is left — do not add summer flowers.

<sub>*Design intent: Between the tub and the sauna wall, so everything in it gets brushed, steamed and looked at from inside the water. A small **olive** and a **myrtle** for the Mediterranean picture, two bright-green *Hebe* domes, rosemary arching over the edge, and a silver *Convolvulus*. Every one of them is glossy or tight and holds its leaves — chosen specifically so nothing sheds into the water.*</sub>

---

## 6. The pot groups

### Group A — narrow terrace, south end

> Photo-realistic. A group of **frost-proof terracotta pots** — mixed classic forms, pots, long toms and bowls, in warm weathered orange-buff clay with lime bloom and age — on buff granite-aggregate paving. Planted with: 1 a gnarled multi-stem olive tree, ~2m, twisted silver-grey trunks, narrow silver-green leaves; 1 upright bronze-purple sword-shaped leaves, architectural; 1 a low glossy dark evergreen with tiny cream tassel flowers; 1 a compact evergreen with cream-edged leaves and pink-flushed flower clusters; 1 a compact metallic-silver evergreen mound with white trumpet flowers; 1 compact English lavender, soft lavender-blue spikes. Aged, collected-over-time, not matching or styled. Soft coastal light.

<sub>*Design intent: The five pots by the study door do the winter work. An olive and a bronze *Phormium* for structure, then **Sarcococca** and **Daphne odora** — the two best winter scents in cultivation — placed exactly where you pass them in the dark in January, with sixty snowdrops and thirty cyclamen underneath. This is the shadiest, most sheltered corner on the terrace, which is the only reason any of it works.*</sub>

---

### Group B — narrow terrace, alongside the outdoor kitchen

> Photo-realistic. A group of **frost-proof terracotta pots** — mixed classic forms, pots, long toms and bowls, in warm weathered orange-buff clay with lime bloom and age — on buff granite-aggregate paving. Planted with: 3 lush green mint in its own pot; 1 a clipped bay in a terracotta pot; 3 flat-leaf parsley; 3 basil; 1 clumps of chives with mauve pompom flowers; 1 sorrel. Aged, collected-over-time, not matching or styled. Soft coastal light.

<sub>*Design intent: Seven working pots along the kitchen run: three mints in separate pots because they would eat any bed they were put in, a clipped bay, parsley, basil renewed each May, and chives and sorrel together. Crocus and dwarf daffodils come up through them before the herbs get going, and autumn cyclamen follow when they die back.*</sub>

---

### Group C — main terrace, **east of the hot tub**

> Photo-realistic. A group of **frost-proof terracotta pots** — mixed classic forms, pots, long toms and bowls, in warm weathered orange-buff clay with lime bloom and age — on buff granite-aggregate paving. Planted with: 1 trailing rosemary cascading over the edge; 1 low creeping thyme mats, some silver-variegated; 1 grey-blue evergreen mats with small fringed pink clove-scented flowers; 1 a tight bright apple-green evergreen dome with short white flower spikes; 1 a tight silver-grey filigree dome. Aged, collected-over-time, not matching or styled. Soft coastal light.

<sub>*Design intent: Five low pots east of the tub — evergreen, aromatic, and chosen for what they *don't* do: none of them sheds petals or leaves into the water. Prostrate rosemary, thyme, cheddar pinks, a *Hebe* dome and a silver santolina, with dwarf iris and crocus in February and *Nerine* in October.*</sub>

---

### Group D — main terrace, **south and west of the lounge sofas**

> Photo-realistic. A group of **frost-proof terracotta pots** — mixed classic forms, pots, long toms and bowls, in warm weathered orange-buff clay with lime bloom and age — on buff granite-aggregate paving. Planted with: 2 a rounded evergreen dome ~1m of deep purple-bronze small leaves; 1 a tight bright apple-green evergreen dome with short white flower spikes; 1 a compact metallic-silver evergreen mound with white trumpet flowers; 1 a small shrubby sage with purple-and-white bicolour flowers. Aged, collected-over-time, not matching or styled. Soft coastal light.

<sub>*Design intent: Five pots framing the lounge, low enough not to catch the north-east view: two purple 'Tom Thumb' domes, a *Hebe*, a silver *Convolvulus* and an 'Amethyst Lips' salvia that flowers from May to November. Being movable is the point — set them out and look from the dining table before you commit.*</sub>

---

### Group E — the cat's corner, by the study door

> Photo-realistic. A group of **frost-proof terracotta pots** — mixed classic forms, pots, long toms and bowls, in warm weathered orange-buff clay with lime bloom and age — on buff granite-aggregate paving. Planted with: 1 a soft grey-green catnip plant in a pot; 1 a pot of fresh green grass; 1 low creeping thyme mats, some silver-variegated. Aged, collected-over-time, not matching or styled. Soft coastal light.

<sub>*Design intent: Three pots for the cat, beside the litter store where she already goes. Real catnip in its own pot because she will flatten it, a tray of cat grass so the ornamental grasses survive, and a thyme, which cats also like to lie on. Crocus and cyclamen for us.*</sub>

---

## 7. Whole-terrace views

Use these for the wide shots — Midjourney is the best bet for these three.

### View 1 — from the dining table, looking north-east to the Downs

> Photo-realistic wide view from a teak dining table on a raised deck of a Brighton seafront roof terrace,
> looking north-east. **The view to the South Downs is completely open and unobstructed** — this is the
> point of the image. Low silver planting in silver-grey timber planters frames the foreground and the
> right-hand edge; a pair of small multi-stem evergreen trees with clear trunks stands at the far edge,
> their canopies well above eye level so you see straight underneath them. Anthracite standing-seam clad
> sauna building to the left. Late afternoon, early summer.

### View 2 — the lounge and hot tub, looking east

> Photo-realistic. A sunken lounge area with pale upholstered outdoor sofas and a hot tub on a Brighton
> roof terrace. Low evergreen planting in silver-grey timber planters — tight domes, silver mounds,
> trailing rosemary — kept deliberately low so the eastward view stays open. Terracotta pots of rosemary,
> thyme and santolina beside the tub. Early evening, warm low light, the sea haze going pink.

### View 3 — the narrow terrace from the study door

> Photo-realistic. Looking along a narrow roof terrace from a doorway. Immediately in the foreground, a low
> square bed of aromatic herbs on a raised plinth — trailing rosemary over all four edges, thyme, lavender,
> sage — that you brush past. Beyond it, an outdoor kitchen run in stainless steel and silvered timber to
> the left, and a long planted run to the right against open steel railings, with a fine-leaved silver-green
> evergreen tree standing above it. Terracotta pots of mint and bay by the door. Sea beyond the railings.
> Morning light.

---

## 8. Tips

- **Generate one bed at a time**, then pick. Four variants per bed is usually enough.
- **If a plant comes out wrong**, describe it harder rather than naming it: not "*Phlomis fruticosa*" but
  "a woolly grey-green shrub with whorled soft-yellow flowers stacked in tiers up the stems".
- **If it comes out too lush**, add: *sparse, lean, gritty, wind-pruned, gaps of gravel showing between
  plants, nothing overfed*.
- **If the planters come out wrong**, add: *the planter is a simple box of horizontal weathered grey deck
  boards, random lengths, staggered joints, round bolt heads, flat timber cap*.
- **Keep the seed for the summer/winter pair** if your tool supports it, so the two images match.
