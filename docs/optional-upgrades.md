# Optional Plant-Upgrade Prediction & Reuse

<!-- Optional post-purchase evidence; NOT Recipes and NOT completion gates. -->

Do **not** edit the algorithm just because a world-owned value changed. Read the purchase panel, make a prediction, run the learner's current code, and compare what actually happens.

Purchase labels, current/next values, prices, and effects are populated from the authoritative game UI rather than duplicated here.

## U-A1 — Starter Beds expansion: reuse the same counted-repeat code

**Available:** Optional A1 production expansion after the baseline 6/6 lesson; later world-owned counts progress 6→8→10.

**Predict:** The expansion shows a larger current → next plot count. Without editing the R01 planting or watering code, predict how many helper actions the same named-reporters should request after expansion.

**Run:** Run the same current planting handler and the same current watering handler. Do not replace either reporter with a typed count.

**Observe:** Check that every newly available plot is planted and then watered. If only the old number finishes, inspect whether the handlers still use farm.plantCount(job) and farm.waterCount(job).

**What should change:** The same R01 algorithms adapt from 6 plots to 8 and later 10 because the world-owned reporters change.

**What stays the same:**

- R01 remains the only required first-repeat Recipe.
- The learner does not manually edit 6→8→10.
- The repeat structures do not change.
- A purchase does not prove the learner program is correct.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Starter Beds expansion: reuse the same counted-repeat code.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U-A1-MENU.png)

*Starter Beds expansion: reuse the same counted-repeat code purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U-A1-RUN.gif)

*Starter Beds expansion: reuse the same counted-repeat code prediction/reuse run.*

## U01 — Six-Shooter: chamber capacity

**Available:** After Six-Shooter is unlocked and its baseline power is validated; hub purchase only outside active jobs/raids.

**Predict:** Read chamber capacity current → next. Without editing code, predict how many chamber shots the same repeat should attempt.

**Run:** Run the same current Six-Shooter algorithm after purchase.

**Observe:** Count the visible chamber shots. If the old amount still fires, inspect whether the repeat bound uses defenders.chambers(job).

**What should change:** The changed chamber-capacity reporter causes the unchanged loop to service the purchased physical capacity.

**What stays the same:**

- fireChamber(job) is unchanged.
- The repeat structure is unchanged.
- No hidden damage upgrade is bundled.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Six-Shooter: chamber capacity.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U01-MENU.png)

*Six-Shooter: chamber capacity purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U01-RUN.gif)

*Six-Shooter: chamber capacity prediction/reuse run.*

## U02 — Twinbud: paired firing cycles

**Available:** After Twinbud is unlocked and its baseline power is validated.

**Predict:** Read paired firing cycles current → next. Predict how many complete left/right pairs the unchanged loop will produce.

**Run:** Run the same current Twinbud algorithm after purchase.

**Observe:** Count complete left→right pairs. If the added pair is missing, inspect defenders.twinCycles(job).

**What should change:** The unchanged loop performs the purchased number of complete paired cycles.

**What stays the same:**

- Left→right order stays the same.
- Neither head moves outside the loop.
- No unrelated strength stat changes.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Twinbud: paired firing cycles.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U02-MENU.png)

*Twinbud: paired firing cycles purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U02-RUN.gif)

*Twinbud: paired firing cycles prediction/reuse run.*

## U03 — Mineberry: prepared trap patches

**Available:** After Mineberry is unlocked and its baseline power is validated.

**Predict:** Read prepared trap patches current → next. Predict how many move→drop work units the unchanged loop will perform.

**Run:** Run the same current Mineberry algorithm after purchase.

**Observe:** Check every prepared patch. If the added patch remains empty, inspect defenders.trapCount(job).

**What should change:** The unchanged loop services every purchased authored trap patch.

**What stays the same:**

- Move remains before drop.
- The world still owns which patches exist.
- No damage increase is bundled.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Mineberry: prepared trap patches.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U03-MENU.png)

*Mineberry: prepared trap patches purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U03-RUN.gif)

*Mineberry: prepared trap patches prediction/reuse run.*

## U04 — Rage Orchid: starting strike damage

**Available:** After Rage Orchid is unlocked and its baseline power is validated.

**Predict:** Read starting strike damage current → next. Predict the first several visible damage values if your unchanged loop still adds 1 after each strike.

**Run:** Run the same current Rage Orchid algorithm after purchase.

**Observe:** Compare the first strike and the increasing sequence. If the first value does not change, inspect defenders.startingDamage(job).

**What should change:** Only the learner variable's starting value changes; the +1-per-strike pattern continues.

**What stays the same:**

- enemyNearby(job) still controls duration.
- The learner still performs the +1 change.
- No hidden bundled combat stats change.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Rage Orchid: starting strike damage.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U04-MENU.png)

*Rage Orchid: starting strike damage purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U04-RUN.gif)

*Rage Orchid: starting strike damage prediction/reuse run.*

## U05 — Prism Bloom: number of marked targets

**Available:** After Prism Bloom is unlocked and its baseline power is validated.

**Predict:** Read number of marked targets current → next. Predict how many inspect-and-branch decisions the same loop will make.

**Run:** Run the same current Prism algorithm after purchase.

**Observe:** Check that every purchased target slot is inspected and receives the appropriate armor-aware branch.

**What should change:** The unchanged repeat processes the purchased number of marked targets.

**What stays the same:**

- Inspect still precedes armored(job).
- Pierce/splash meanings do not change.
- No new attack type is purchased.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Prism Bloom: number of marked targets.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U05-MENU.png)

*Prism Bloom: number of marked targets purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U05-RUN.gif)

*Prism Bloom: number of marked targets prediction/reuse run.*

## U06 — Sunbeam Lily: stored sunlight capacity

**Available:** After Sunbeam Lily is unlocked and its baseline power is validated.

**Predict:** Read the sunlight property current → next. For a fully charged preview, predict the maximum beam/decrement iterations the unchanged while loop can perform.

**Run:** Run the same current Sunbeam algorithm in a fully charged upgraded preview; then compare a depleted start if available.

**Observe:** The full-charge sequence can be longer, while a depleted invocation still follows the actual value returned by defenders.sunlightSupply(job).

**What should change:** Purchased capacity raises possible starting supply; the reporter still gives actual invocation-start availability.

**What stays the same:**

- The learner still copies the reporter once.
- The learner still decrements sunlight by 1.
- Spent energy is not recreated by the purchase.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Sunbeam Lily: stored sunlight capacity.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U06-MENU.png)

*Sunbeam Lily: stored sunlight capacity purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U06-RUN.gif)

*Sunbeam Lily: stored sunlight capacity prediction/reuse run.*

## U07 — Echo Mushroom: pulse levels

**Available:** After Echo Mushroom is unlocked and its baseline power is validated.

**Predict:** Read pulse levels current → next. Predict the new largest visible radius if the same native index loop still passes index + 1.

**Run:** Run the same current Echo algorithm after purchase.

**Observe:** Watch the expanding rings. If the added largest ring never appears, inspect defenders.pulseCount(job); if the first ring is radius 0, inspect index + 1.

**What should change:** The purchased pulse count extends the same indexed sequence.

**What stays the same:**

- The native index remains zero-based.
- index + 1 remains the visible radius.
- No second learner counter is introduced.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Echo Mushroom: pulse levels.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U07-MENU.png)

*Echo Mushroom: pulse levels purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U07-RUN.gif)

*Echo Mushroom: pulse levels prediction/reuse run.*

## U08 — Healroot: allies to inspect

**Available:** After Healroot is unlocked and its baseline power is validated.

**Predict:** Read allies to inspect current → next. Predict how many candidate allies the same repeat will inspect.

**Run:** Run the same current Healroot algorithm after purchase.

**Observe:** Check that the added candidate is inspected and that only damaged allies receive healing.

**What should change:** The unchanged repeat/inspect/if structure adapts to the purchased candidate count.

**What stays the same:**

- Inspect still precedes damagedAlly(job).
- Healthy allies remain a no-action case.
- Heal strength is unchanged.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Healroot: allies to inspect.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U08-MENU.png)

*Healroot: allies to inspect purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U08-RUN.gif)

*Healroot: allies to inspect prediction/reuse run.*

## U09 — Sporecap Colony: spore caps

**Available:** After Sporecap Colony is unlocked and its baseline power is validated.

**Predict:** Read spore caps current → next while spores in each cap stays fixed. Predict how the outer grouping changes; optional arithmetic can compare full-output totals.

**Run:** Run the same current nested Sporecap algorithm after purchasing only spore caps.

**Observe:** There should be more outer cap groups while the number of releases inside each cap remains unchanged.

**What should change:** Only the outer nested-loop dimension changes.

**What stays the same:**

- sporesPerCap(job) stays independently authoritative.
- Each cap is opened once.
- The algorithm remains nested.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Sporecap Colony: spore caps.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U09-MENU.png)

*Sporecap Colony: spore caps purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U09-RUN.gif)

*Sporecap Colony: spore caps prediction/reuse run.*

## U10 — Sporecap Colony: spores in each cap

**Available:** After Sporecap Colony is unlocked and its baseline power is validated.

**Predict:** Read spores in each cap current → next while spore caps stays fixed. Predict how the inner grouping changes; optional arithmetic can compare full-output totals.

**Run:** Run the same current nested Sporecap algorithm after purchasing only spores-per-cap.

**Observe:** The number of cap groups stays fixed while every cap performs more inner releases.

**What should change:** Only the inner nested-loop dimension changes.

**What stays the same:**

- capCount(job) stays independently authoritative.
- Each cap is still opened once.
- The algorithm remains nested.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Sporecap Colony: spores in each cap.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U10-MENU.png)

*Sporecap Colony: spores in each cap purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U10-RUN.gif)

*Sporecap Colony: spores in each cap prediction/reuse run.*

## U11 — Lanternleaf: stored magic charge

**Available:** After Lanternleaf is unlocked and its baseline power is validated.

**Predict:** Read the magic-charge property current → next. For a fully charged preview, predict the maximum number of one-unit transfers the unchanged while loop can attempt.

**Run:** Run the same current Lanternleaf algorithm fully charged; then compare a partially depleted start if available.

**Observe:** The full-charge transfer sequence can be longer, while depleted starts still follow defenders.chargeSupply(job).

**What should change:** Purchased capacity raises possible starting charge; the reporter still returns actual invocation-start availability.

**What stays the same:**

- The learner still copies charge once.
- The learner still decrements before transfer.
- Only compatible energy recipients can receive energy.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Lanternleaf: stored magic charge.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U11-MENU.png)

*Lanternleaf: stored magic charge purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U11-RUN.gif)

*Lanternleaf: stored magic charge prediction/reuse run.*

## U12 — Rootsnare: root patch reach

**Available:** After Rootsnare is unlocked and its baseline power is validated.

**Predict:** Read root patch reach current → next. Predict how the same live while condition will change as the same target crosses the authored patch.

**Run:** Run the same current Rootsnare algorithm after purchase against the same deterministic route target.

**Observe:** Compare where the target remains validly trapped. A wider purchased mask should keep the predicate true across more of the route; invalidation still ends it.

**What should change:** The named reach changes the live while predicate's authored spatial mask.

**What stays the same:**

- No coordinate arithmetic is added.
- No repeat counter is added.
- Tighten/slow strengths remain unchanged.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Rootsnare: root patch reach.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U12-MENU.png)

*Rootsnare: root patch reach purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U12-RUN.gif)

*Rootsnare: root patch reach prediction/reuse run.*

## U13 — Stormbloom: spark bulbs

**Available:** Postgame only: the final raid must unlock Stormbloom before this optional purchase exists.

**Predict:** Read spark bulbs current → next while sparks in each bulb stays fixed. Predict how the outer bulb grouping changes.

**Run:** Run the same current Stormbloom algorithm after purchasing only the bulb-count property.

**Observe:** More bulb groups should awaken while each bulb's inner spark count stays fixed.

**What should change:** Only the outer nested-loop dimension changes.

**What stays the same:**

- sparksPerBulb(job) remains independently authoritative.
- Focus-before-conductive stays unchanged.
- Zap/gust meanings stay unchanged.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Stormbloom: spark bulbs.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U13-MENU.png)

*Stormbloom: spark bulbs purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U13-RUN.gif)

*Stormbloom: spark bulbs prediction/reuse run.*

## U14 — Stormbloom: sparks in each bulb

**Available:** Postgame only: the final raid must unlock Stormbloom before this optional purchase exists.

**Predict:** Read sparks in each bulb current → next while spark bulbs stays fixed. Predict how the inner target-decision count changes inside each bulb.

**Run:** Run the same current Stormbloom algorithm after purchasing only sparks-per-bulb.

**Observe:** The bulb-group count stays fixed while every bulb performs more focus-and-branch decisions.

**What should change:** Only the inner nested-loop dimension changes.

**What stays the same:**

- bulbCount(job) remains independently authoritative.
- Focus-before-conductive stays unchanged.
- Zap/gust meanings stay unchanged.

![At 640 by 480, the purchase panel shows the named current and next value, price, and concise effect for Stormbloom: sparks in each bulb.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U14-MENU.png)

*Stormbloom: sparks in each bulb purchase-panel evidence.*
![At 640 by 480, the learner's unchanged current algorithm runs after purchase so the changed named value can be compared with the prediction.](https://raw.githubusercontent.com/mrbrackebusch-code/magical-farm/main/assets/instructions/v0.3.0/M-U14-RUN.gif)

*Stormbloom: sparks in each bulb prediction/reuse run.*
