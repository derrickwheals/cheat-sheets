# Nikon D7500 — Scenario Cheat Cards

**For:** Derrick's kit — D7500 (DX) · 18–105mm f/3.5–5.6 · 70–300mm f/4.5–5.6 · Tamron 90mm f/2.8 Macro · **AF-S DX 35mm f/1.8G** · SmallRig tripod · ML-L3 infrared remote · **NEEWER TC-2 (MC-DC2) wired timer remote** · 67mm UV + polarising filters.

**For the designer:** Each card below uses the **same field structure** so they can be templated 1:1. Fields are: *When to use · Best lens · Mode & drive · Settings · Stability · Filters · Gotchas · Expert tip · Worth adding*. Card boundaries are marked with `=== CARD N ===` and a horizontal rule. A non-numbered **Global Setup** panel precedes Card 1 (marked `=== SETUP CARD ===`) — design it as a distinct "set once" tile, visually separate from the 13 scenario cards. A second non-numbered panel, the **TC-2 Remote** reference (marked `=== ACCESSORY CARD ===`), follows Card 13 — it does *not* use the scenario field structure; treat it as its own tool-reference tile. Manual page references are cited as `(Manual p.XXX)` and point to the D7500 Reference Manual.

> **Two things to read once, so they're not repeated on every card:**
> 1. **Your AF-S DX 35mm f/1.8G is now your low-light / indoor / street workhorse** (52mm-equiv, ~2.6 stops faster than the zoom at the same framing). It's the *primary* lens on **Card 4 (Low Light)** and **Card 13 (Street)**, and a strong second option for indoor action and environmental portraits. What it *can't* fix: the 18–105's slow aperture still limits the **wide** end (a fast 14–16mm ultra-wide remains the real astro/landscape upgrade), and you still have no fast **reach** for wildlife. Note it has **no VR** — mind your shutter floor handheld. [Ken Rockwell 35mm f/1.8G review](https://www.kenrockwell.com/nikon/35mm-f18-dx.htm)
> 2. **Your Tamron 90mm is secretly your best portrait lens** (135mm equivalent, f/2.8, very sharp) — not just a macro lens. It appears as the *primary* pick on the Portrait card for that reason.

> **Your two remotes — and which one to reach for:**
> - **ML-L3 (infrared) = the quick, no-cable one.** Its killer feature is **Remote mirror-up** *(Remote control mode (ML-L3), Manual p.175)*: one press raises the mirror, a second fires — kills mirror-slap *and* hand contact with no cable dangling off the camera. Bonus: **Bulb becomes "Time"** *(Manual p.82)* — press to start, press to stop, auto-ends at 30 min.
> - **NEEWER TC-2 (MC-DC2, wired) = the one that does what the ML-L3 can't.** It is a **cable release**, so it drives the shutter *exactly* as the camera's own button does. Two consequences: (a) it can hold Bulb open **indefinitely** and **repeat that automatically** — the ML-L3 and the in-camera interval timer both cap out at 30 min / 30 s respectively, so the TC-2 is the *only* route to astro stacking and multi-minute intervals; (b) it **can** drive **MUP + EFCS** (see the corrected Global Setup entry below). Full reference on the **TC-2 Accessory Card** at the end of the deck.
> - **Correction to earlier guidance:** an *infrared* remote can't trigger EFCS, but a *cable* release can. Now that you own the TC-2, **MUP release-dial + EFCS + TC-2 shutter button** is a genuinely available (and slightly better) alternative to ML-L3 Remote mirror-up for short tripod exposures.
> - **Two ML-L3 quirks that still apply:** it always shoots **single-frame** (no bursts via remote — use the camera shutter for CH), and **Remote control mode can't be saved to U1/U2 banks** *(Manual p.83)*, so you re-select it from the menu each session. The TC-2 has neither limitation — it needs no menu mode at all.

---

=== SETUP CARD ===
## ⚙️ Global Setup — set once, then forget

*These live in the menus, not on the mode dial. Set them once and every card below assumes they're done.*

- **Shoot RAW.** Image quality → **NEF (RAW)**, 14-bit, lossless compressed. *(Manual p.97)* Every "fix it in post" note in this deck depends on it — and it makes the JPEG-only settings (Picture Control, Active D-Lighting, High ISO NR, colour space) irrelevant to your actual files.

- **Back-button focus.** Custom Setting **a6 (AF activation) → AF-ON only** *(Manual p.261)*, then reassign the **AE-L/AF-L button → AF-ON** via **f1 (Custom control assignment)** *(Manual p.266)*. ⚠️ **Consequence:** the shutter half-press no longer focuses — you focus with your thumb on the rear button. Wherever a card says "AF," that's the button you press now. Almost nobody switches back once it clicks.

- **EFCS: On — and now actually usable.** Custom Setting **d4** *(Manual p.264)*. It only acts in the **mirror-up (MUP)** release-dial position triggered by the shutter **or a cable release**. Your ML-L3 (infrared) can't drive it — but your **NEEWER TC-2 can**. So you now have two clean no-shake routes: **MUP + EFCS + TC-2 button** (best, if you don't mind the cable) or **ML-L3 Remote mirror-up** (cable-free). ⚠️ **The TC-2's *timer* mode cannot drive MUP** — the timer sends one press, MUP needs two. Timer sequences must use **single-frame** release.

- **ML-L3 → Remote mirror-up.** Photo Shooting Menu → **Remote control mode (ML-L3) → Remote mirror-up** *(Manual p.175)*: one press lifts the mirror, a second fires — your no-touch, no-shake default for tripod work. Two quirks: the remote forces **single-frame** (use the camera shutter for bursts), and this mode **can't be saved to U1/U2** *(Manual p.83)*, so re-select it each session.

- **AF priority: a1 → Release, a2 → Release.** *(Manual p.260)* Both set to release priority: the shutter always fires, and *you* judge focus off the green in-focus dot rather than letting the camera silently veto you.
  - ✅ **Tested on your camera:** with **a6 = AF-ON only** and **AF-S + Focus priority**, thumb-focusing on a near object and then recomposing onto a distant subject → **the shutter will not fire.** The camera re-checks the in-focus indicator at the moment of release regardless of whether an AF cycle is running. **Back-button focus does not exempt you from focus priority.**
  - ⚠️ **That's why a2 is Release.** Focus priority breaks **focus-and-recompose**, which is a core BBF technique — and it fails *silently*: you press the shutter, nothing happens, no error, moment gone. A soft frame you can see and delete beats a missing frame you can't explain. (AF-C's default is already Release, so a1 needs no change.)
  - 💡 **Not applicable in MF** — a1/a2 only gate autofocus modes, so manual-focus macro and astro are unaffected either way.
  - 💡 **Worth trying:** with BBF and both priorities on Release, **AF-C alone covers everything** — thumb down = continuous tracking, thumb up = locked focus, recompose freely. Many BBF shooters never touch the focus-mode selector again. Not a rule; a habit to test.

- **Auto ISO minimum shutter.** ISO sensitivity settings → **Minimum shutter speed → Auto** *(Manual p.120)* — the camera then floors the shutter at ~1/(2 × focal length) and rescales it automatically as you zoom. Nudge it **faster** for action/wildlife. Set **Maximum sensitivity** per scenario: **3200** for cleaner files in decent light, **6400** when you need the shutter speed more than the cleanliness.

---

=== CARD 1 ===
## 🏔 Landscapes — Tripod

**When to use:** Static scenery, maximum detail, time to set up. Sunrise/sunset, vistas, foreground-to-background sharpness.

**Best lens:** **18–105mm @ 18mm** (your widest). Reach for 70–300mm only to *compress* distant ridgelines.

**Mode & drive:** **A** (Aperture priority) or **M** · Single frame (S).

**Settings:**
- **Aperture:** f/8–f/11 (sharpness sweet spot). Avoid f/16+ — diffraction softens DX sensors early.
- **ISO:** 100 (base). Tripod removes any reason to raise it. *(Manual p.118)*
- **Shutter:** Whatever the meter gives — the tripod carries it.
- **WB:** Daylight (consistent) or Auto. *(Manual p.130)*
- **Metering:** Matrix. *(Manual p.123)*
- **Focus:** Single-point AF ~⅓ into the scene, or magnified manual focus in Live View. *(Manual p.103)*
- **Also:** Shoot RAW (NEF). Active D-Lighting optional for high-contrast skies. *(Manual p.153)*

**Stability:** Tripod + **ML-L3 in Delayed remote** mode (2-sec lag built in), or **Exposure delay (d3)** *(Manual p.264)* if the remote's line-of-sight to the front sensor is awkward. **Turn VR OFF** on the tripod.

**Filters:** Polariser for skies/foliage/water glare. **Remove the UV filter** when stacking — two filters invite flare/vignetting at 18mm.

**Gotchas:**
- Polariser gives **uneven sky** at 18mm (ultra-wide) — rotate and check, or skip it.
- Past f/11 you *lose* sharpness to diffraction, you don't gain it.

**Expert tip:** Base ISO, f/8, RAW, and bracket exposures for high-contrast scenes. [Ken Rockwell — D7500](https://www.kenrockwell.com/nikon/d7500.htm) · [CameraTips D7500 cheat cards](https://www.cameratips.com/nikon/d7500/cheat-cards)

**Worth adding:**
- **Ultra-wide lens** (e.g. Tokina 11–20mm f/2.8, Nikon 10–20mm) — true wide drama beyond 18mm.
- **L-bracket** for fast level horizons + portrait orientation.
- **Graduated ND filters** to balance bright sky vs dark land.

---

=== CARD 2 ===
## 🥾 Landscapes — Handheld

**When to use:** Hiking, no time/space for a tripod, changing light.

**Best lens:** **18–105mm @ 18mm** (VR helps here).

**Mode & drive:** **A** · Single frame.

**Settings:**
- **Aperture:** f/8 (keep some sharpness margin; don't chase f/11 if light is dropping).
- **ISO:** **Auto ISO**, base 100, **minimum shutter ~1/100** so you stay sharp. *(Auto ISO control, Manual p.120)*
- **Shutter:** Keep ≥ 1/100 at 18mm. VR buys ~2–3 stops but won't stop *your* sway forever.
- **WB:** Daylight/Auto · **Metering:** Matrix.
- **Focus:** Single-point AF, ⅓ in.

**Stability:** **VR ON.** Brace against a tree/rock; tuck elbows; exhale as you press.

**Filters:** Polariser if needed (costs ~1.5–2 stops of light — watch your shutter speed).

**Gotchas:**
- Below ~1/60 handheld at wide angle, hit rate drops fast — raise ISO instead.
- Polariser + handheld + low light = a recipe for blur. Pick two.

**Expert tip:** Shutter floor = 1 / (focal length × 1.5 crop). At 18mm that's ~1/30 *absolute* min — but 1/100 is the safe working number.

**Worth adding:** A **fast / ultra-wide prime** for low-light wide scenes — your 35mm is too narrow for sweeping vistas, so it doesn't fill this gap.

---

=== CARD 3 ===
## 🌅 Golden Hour / Sunset

**When to use:** The hour after sunrise / before sunset. Warm light, long shadows, saturated skies.

**Best lens:** **18–105mm** for the whole scene · **70–300mm** to throw a big compressed sun behind a subject.

**Mode & drive:** **A** or **M** · Single frame (bracket if contrast is extreme).

**Settings:**
- **Aperture:** f/8–f/11. Stop to **f/16 for sunstars** when the sun is a point on the horizon.
- **ISO:** 100.
- **Exposure comp:** **−0.3 to −1 EV** to keep the sky rich and protect highlights / get clean silhouettes.
- **WB:** **Cloudy or Shade** — this *enhances* the warmth. Auto WB will try to neutralise the colour you're there for. *(Manual p.130)*
- **Metering:** Matrix (or Spot-meter the sky for silhouettes).
- **Focus:** Single-point AF.

**Stability:** Handheld is fine early; as light drops, tripod + exposure delay/2-sec timer.

**Filters:** Polariser *carefully* — it can over-darken a clear sky and kill the glow. Rotate and watch.

**Gotchas:**
- **Never frame the sun through the viewfinder with the 70–300mm** — use Live View to protect your eyes.
- Filters + low sun = flare. Remove the UV filter; consider removing the polariser too.

**Expert tip:** Set WB warm (Cloudy/Shade) and underexpose slightly — the file looks like the moment felt. [Ken Rockwell — D7500](https://www.kenrockwell.com/nikon/d7500.htm)

**Worth adding:** Graduated ND filter · tripod-mounted remote for the blue-hour frames afterward.

---

=== CARD 4 ===
## 🌙 Low Light — Handheld (indoor / available light)

**When to use:** Indoors, cafés, dusk, events — no tripod, no flash, just ambient light.

**Best lens:** **AF-S DX 35mm f/1.8G** — this is its home card. The 52mm-equiv "normal" view at f/1.8 is exactly what this scenario always wanted. Drop back to **18–105mm @ 18mm** only when you need a *wider* field than 35mm gives.

**Mode & drive:** **A** or **M** · Single frame (Qc for quiet candids).

**Settings:**
- **Aperture:** **f/1.8–f/2.8.** Wide open for the dimmest rooms; f/2.8 for a touch more depth (two people, some context).
- **ISO:** **Auto ISO, cap 3200–6400** — but the f/1.8 aperture means you'll often sit far *below* the cap: ISO 800–1600 where the zoom forced 6400. *(Manual p.118, p.120)*
- **Shutter:** ≥ 1/60 still people; 1/125+ if they move.
- **WB:** Auto, or match the ambient source.
- **Metering:** Matrix; add **+0.3–+1 EV** in dim rooms so faces aren't muddy.
- **High ISO NR:** Affects **JPEG only** — it doesn't touch your NEF files, so it's moot if you shoot RAW (which you should here). *(Manual p.255)*

**Stability:** Brace; shoot on the exhale. ⚠️ **The 35mm has no VR** (your zoom does) — respect the shutter floor: ~1/50 is the bare handheld minimum at 35mm, **1/80–1/125 is safe.** The extra ~2.6 stops of aperture more than pay for the missing VR — and VR never helped freeze *moving people* anyway.

**Filters:** **Remove the UV filter** — every bit of light and contrast counts.

**Gotchas:**
- **No VR** — don't let the shutter sag below ~1/60 just because the room is dark.
- **Fixed 35mm** — you zoom with your feet (liberating once you adjust).
- Wide open at f/1.8 the DOF is thin — for a group, stop to **f/2.8–f/4** so everyone's sharp.

**Expert tip:** At the same 35mm framing your zoom is ~f/4.5, so the prime at f/1.8 is **~2.6 stops** faster — and **~3.3 stops** vs the zoom's f/5.6 long end. That turns a grainy ISO 6400 frame into a clean ISO ~700–1000.

**Worth adding:**
- **Speedlight** (e.g. SB-700) for bounce flash — transforms indoor/event work beyond what any aperture can.
- **50mm f/1.8G** later, if you want a slightly tighter, more flattering fast prime alongside the 35mm.

---

=== CARD 5 ===
## ✨ Night Sky / Astro (stars, Milky Way)

**When to use:** Dark skies, no moon, stars or Milky Way as the subject.

**Best lens:** **18–105mm @ 18mm, f/3.5** for wide Milky-Way-over-landscape scenes — the widest view wins for composition. **Secondary: 35mm f/1.8G** for *tighter* star fields / constellations: its f/1.8 gathers ~2 stops more light and runs cleaner ISO, but at 35mm the 500-rule caps you at **~9–10 s** before stars trail (vs ~18 s at 18mm) and you frame less sky.

**Mode & drive:** **M** · **Single frame** · shutter on **Bulb**, driven by the **NEEWER TC-2**. ⚠️ **The in-camera interval timer is the wrong tool here** *(Manual p.256)* — it can't hold a Bulb exposure past the 30-s native maximum, so it can't stack long frames. Turn it **OFF** and let the TC-2 set exposure length (LONG), gap (INTVL) and frame count (N). *(See the TC-2 Accessory Card.)* The ML-L3 "Time" mode *(Manual p.82)* still works for a **single** long trail (≤ 30 min) if you'd rather not run a cable.

**Settings:**
- **Aperture:** f/3.5 (wide open — you need every photon).
- **Shutter:** **~15–20 s.** 500-rule: 500 ÷ (18 × 1.5) ≈ 18 s before stars trail.
- **ISO:** 3200–6400.
- **WB:** ~4000 K (or Auto, fix in RAW).
- **Focus:** **Manual**, Live View magnified on a bright star. ⚠️ **The D7500 has no focus peaking** — magnification is your only aid.
- **Long exposure NR:** On for single shots (this one *does* affect RAW — it's dark-frame subtraction); Off if you'll stack many frames. Note it shoots a matching dark frame afterward, **doubling capture time.** *(Manual p.255)*

**Stability:** Tripod **mandatory.** Trigger with the **TC-2** (its timer removes all hand contact — no need for Exposure delay or mirror-up; at 15 s+ mirror slap is a rounding error). **VR OFF** on the tripod. ML-L3 Delayed remote is the fallback for one-off frames.

**Filters:** Remove everything — UV and polariser both hurt here.

**Gotchas:**
- At 18mm, f/3.5 is your ceiling — a fast *wide* prime (14–16mm f/2–2.8) is still the real astro upgrade. Your 35mm f/1.8 is faster but too narrow for wide Milky Way scenes.
- No peaking → triple-check focus at magnification before committing 20-sec frames.

**Expert tip:** 500 rule for max shutter, shoot RAW, and stack multiple frames (free noise reduction). **TC-2 stacking recipe:** DELAY 5 s · LONG = your exposure · INTVL = exposure + 5 s · N = `---` (unlimited). **Turn Long Exposure NR OFF when stacking** — it doubles capture time and you'll shoot your own dark frames anyway.

**Worth adding:**
- **Fast wide prime** — Samyang/Rokinon **14mm f/2.8** or **16mm f/2** is a *transformative* astro upgrade.
- **Star tracker** (e.g. Move Shoot Move) for pinpoint stars at longer exposures.

---

=== CARD 6 ===
## 💧 Long Exposure (waterfalls, light trails, smooth water/cloud)

**When to use:** Silky water, car-light streaks, dreamy moving cloud. Movement becomes the subject.

**Best lens:** **18–105mm** (wide framing for most scenes).

**Mode & drive:** **M** or **S** · Single frame.

**Settings:**
- **Aperture:** f/11–f/16.
- **ISO:** 100 (use **Lo 1 ≈ ISO 50** only if you need it even darker). *(Manual p.118)*
- **Shutter:** Waterfalls 0.5–2 s · silky rivers 1–5 s · light trails 10–30 s. For longer, set **Bulb** and use the **TC-2** — set LONG to the exact exposure and it times it for you, with **no 30-min ceiling**. (ML-L3 "Time" mode is the cable-free fallback: press to start, press to stop, ≤ 30 min. *(Manual p.82)*)
- **Long exposure NR:** On (subtracts hot pixels; *does* affect RAW) — but it shoots a matching dark frame, **doubling capture time.** A 30-min exposure then ties up the camera for ~60 min. ⚠️ **If you're running a TC-2 sequence with NR on, INTVL must be ≥ 2 × exposure** or frames silently drop. Easier: switch NR off. *(Manual p.255)*
- **Focus:** Single-point AF, then switch to MF so it doesn't re-hunt.

**Stability:** Tripod **mandatory.** Best: **MUP release-dial + EFCS (d4) + TC-2** — the cable release *can* drive MUP (two presses), so you get electronic-front-curtain *and* zero hand contact. Cable-free alternative: **ML-L3 in Remote mirror-up**. *(Manual p.175, p.264)*

**Filters:** Your **polariser doubles as a ~1.5–2 stop ND** *and* cuts glare off wet rock/water — use it. For *daytime* long exposures you'll still need a real ND (see below).

**Gotchas:**
- In daylight, even at f/16 + ISO 100 you can't reach 1 s without an **ND filter** — your kit can't do daytime silky water yet.
- Polariser alone ≈ 2 stops — enough for shade/dusk, not bright sun.

**Expert tip:** Use the polariser as a makeshift ND for ~2 stops; meter, then dial shutter to taste.

**Worth adding:**
- **ND filters** (ND8 for a couple stops, **ND1000 / 10-stop** for daytime long exposure) — biggest unlock for this scenario.
- ~~Remote / intervalometer~~ — ✅ **done** (NEEWER TC-2).

---

=== CARD 7 ===
## 🌸 Macro — Static (flowers, objects, still subjects)

**When to use:** Non-moving subjects, controlled setting, maximum detail at 1:1.

**Best lens:** **Tamron 90mm f/2.8 Macro** (the only choice — and a brilliant one).

**Mode & drive:** **A** or **M** · Single frame (or **MUP**, see Stability).

**Settings:**
- **Aperture:** f/8–f/16. DOF is *razor-thin* at 1:1, but past ~f/16 diffraction bites. **f/11** is the usual compromise; **focus-stack** for more depth.
- **ISO:** 100.
- **Shutter:** Tripod handles it; raise to 1/160+ if there's any air movement.
- **Focus:** **Manual**, magnified Live View. A focusing rail makes this far easier.

**Stability:** Tripod **mandatory.** **Tamron VC OFF** on the tripod. Your best no-touch route here is the **ML-L3 in Remote mirror-up** mode — one press raises the mirror, a second press fires, so neither mirror-slap nor your hand ever shakes the rig. *(Remote control mode (ML-L3), Manual p.175)* For simpler setups, **Delayed remote** + **Exposure delay (d3)** also works. *(Manual p.264)*

**Filters:** None needed; remove the UV filter.

**Gotchas:**
- DOF at 1:1 can be **under a millimetre** — tiny focus shifts matter more than aperture.
- Leave **VC off** on the tripod (on a tripod it can *introduce* motion).
- The smallest breeze ruins a 1-sec macro frame — shoot indoors or shield the subject.

**Expert tip:** Focus by gently rocking the camera/rail back and forth and firing at the peak; focus-stack 5–15 frames for front-to-back sharpness.

**Worth adding:**
- **Focusing rail** (precise 1:1 focus) · **macro diffuser / twin or ring flash** (clean even light) · **MC-DC2 cable release** — unlike your ML-L3 it unlocks the **EFCS** route *and* true **Bulb** (no 30-min Time limit), and needs no line-of-sight to the IR sensor · reflector.

---

=== CARD 8 ===
## 🐝 Macro — Handheld (insects, anything that moves)

**When to use:** Bugs, subjects you can't approach slowly enough for a tripod.

**Best lens:** **Tamron 90mm f/2.8 Macro.**

**Mode & drive:** **A** or **M** · **CH** (continuous) or **Qc** to fire bursts and improve your hit rate. *(Manual p.86)*

**Settings:**
- **Aperture:** f/8–f/11 (a little more DOF to survive handheld focus drift).
- **ISO:** Auto, up to 1600–3200 — you're buying shutter speed.
- **Shutter:** **≥ 1/250**, ideally **1/320–1/500.** Handshake at 1:1 magnifies brutally; the bug moves too.
- **Focus:** AF, or rock-focus MF. Back-button focus helps.

**Stability:** **Tamron VC ON** (opposite of the tripod card). Brace; shoot bursts.

**Filters:** Remove UV.

**Gotchas:**
- VC **ON** here — the single most-confused setting between the two macro cards.
- Even at f/11 the DOF is tiny — keep the sensor plane parallel to the insect's body/eye.

**Expert tip:** Add a **fill flash with a diffuser** — it lets you shoot f/11 *and* a fast shutter *and* low ISO simultaneously. It's the macro game-changer.

**Worth adding:** **Diffused macro flash** (twin or ring) · a bigger/softer diffuser for natural light.

---

=== CARD 9 ===
## 🦅 Wildlife / Birds

**When to use:** Distant, unpredictable animals; birds in flight or perched.

**Best lens:** **70–300mm @ 300mm** (450mm equivalent on DX).

**Mode & drive:** **S** or **A** (+ Auto ISO) · **CH** (8 fps). *(Manual p.86)*

**Settings:**
- **Aperture:** f/5.6 wide open; **f/8 is noticeably sharper** at 300mm if light allows.
- **Shutter:** ≥ 1/500 perched · **1/1000–1/2000** for birds in flight.
- **ISO:** Auto, cap 6400.
- **AF:** **AF-C** · **Dynamic-area 21/51** or **Group-area** for erratic subjects. *(AF-area, Manual p.103)* Back-button focus strongly recommended.
- **VR:** ON (Normal; Sport mode for panning flight).

**Stability:** Monopod or tripod helps a lot at 300mm; otherwise high shutter + good technique.

**Filters:** Remove UV for maximum sharpness/light.

**Gotchas:**
- 300mm **f/5.6 is light-hungry** — overcast days push ISO high fast.
- It's **soft wide open at 300mm** — stop to f/8 when you can.
- Long lens over hot ground = **heat haze**; nothing fixes that but shooting earlier/closer.

**Expert tip:** Minimum shutter = 1/(focal × 1.5) = ~1/450 at 300mm *just for sharpness* — but go 1/1000+ for anything with wings.

**Worth adding:**
- **Longer/faster telephoto** — Nikon 200–500mm f/5.6 or a 100–400mm is the real reach upgrade.
- **Monopod** for all-day handholding · (a teleconverter is possible but costs AF speed/aperture).

---

=== CARD 10 ===
## ⚡ Action / Sports

**When to use:** Kids, pets, field sports — fast, unpredictable motion.

**Best lens:** **70–300mm** (outdoor / far) · **35mm f/1.8G** for *indoor / close* action where you need shutter speed in poor light · **18–105mm** when you want a flexible zoom range up close.

**Mode & drive:** **S** (+ Auto ISO) · **CH** (8 fps). *(Manual p.86)*

**Settings:**
- **Shutter:** **1/1000+** to freeze · ~1/250 for intentional panning blur.
- **Aperture:** Widest available (you're prioritising shutter).
- **ISO:** Auto, cap 6400.
- **AF:** **AF-C** · **Dynamic 21/51** or **3D-tracking** · back-button focus. *(Manual p.100, p.103)*
- **File:** Consider JPEG or RAW-thin if you fill the buffer on long bursts.

**Stability:** VR ON; pan smoothly through the shot, follow through.

**Filters:** Remove UV.

**Gotchas:**
- **Indoor sports kill the 70–300** (f/5.6 forces ISO 12800+) — switch to the **35mm f/1.8** when you're close enough; its 2.6+ stops are the difference between sharp and smeared. Trade-off: it's a fixed normal, so you can't reframe tight-to-wide on the fly.
- 8 fps fills the buffer in RAW quickly — know your card/buffer limits before the decisive moment.

**Expert tip:** Pre-focus on where the action *will* be, and let CH + AF-C do the rest. Panning at 1/250 conveys speed better than a frozen 1/2000.

**Worth adding:**
- **Fast telephoto** (70–200mm f/2.8) for indoor/low light.
- **Faster UHS-I SD card** (the D7500 has a single UHS-I slot) to clear the buffer sooner.

---

=== CARD 11 ===
## 👤 Portraits

**When to use:** People — headshots, environmental portraits, couples.

**Best lens:** **Tamron 90mm f/2.8** for flattering head-and-shoulders (135mm-equiv compression, lovely blur) · **35mm f/1.8G** for **environmental / full-body / tight-room / small-group** portraits (52mm-equiv, f/1.8 separation). Use **18–105mm @ 50–85mm** only when you need zoom flexibility.

**Mode & drive:** **A** · Single frame (Qc for candids). *(Manual p.86)*

**Settings:**
- **Aperture:** f/2.8–f/4 for one person (subject separation) · f/5.6–f/8 for groups (everyone sharp).
- **ISO:** Auto / 100.
- **Shutter:** ≥ 1/200 handheld (freezes subject *and* beats 90mm shake).
- **AF:** **AF-S single-point on the near eye** · AF-C + face detection for moving subjects. *(Manual p.100, p.103)*
- **WB:** Auto or Cloudy (warmer skin) · **Picture Control: Portrait** · Metering: Matrix.

**Stability:** Handheld at 1/200+; brace for f/2.8 keepers.

**Filters:** Polariser can cut skin shine and deepen a sky behind the subject — optional. Remove UV for best rendering.

**Gotchas:**
- At f/2.8 the **eyelashes are sharp and the ear isn't** — nail focus on the near eye.
- 90mm needs **working distance** (a few metres) — tight indoors, switch to the **35mm**.
- With the **35mm, don't fill the frame with a face** — at close range a normal lens exaggerates noses/foreheads. Use it for half- and full-body and step back; save headshots for the 90mm.

**Expert tip:** Focus on the near eye, shoot in open shade or golden-hour light, and let the 90mm's compression flatter the face.

**Worth adding:**
- **85mm f/1.8G** if you want a faster, quicker-focusing dedicated portrait tele than the (slower-focusing) macro 90mm.
- **Speedlight + small softbox** and a **reflector** for shaping light.

---

=== CARD 12 ===
## 🌕 Moon

**When to use:** A clear, detailed moon — craters and all.

**Best lens:** **70–300mm @ 300mm** (450mm equivalent — still small in frame; you'll crop).

**Mode & drive:** **M** (the meter is fooled by the black sky) · Single frame.

**Settings:**
- **Aperture:** f/8–f/11.
- **Shutter:** **1/125–1/250.** The moon is in full sunlight — *"Looney 11" rule:* f/11, shutter ≈ 1/ISO.
- **ISO:** 100–200.
- **Focus:** **Manual to infinity**, magnified Live View.

**Stability:** Tripod + **ML-L3 (Delayed remote)**, or **Remote mirror-up** for the crispest craters, plus Exposure delay (d3) if you like. *(Manual p.175, p.264)* VR OFF.

**Filters:** None — remove UV.

**Gotchas:**
- **Don't use a long exposure** — the moon is *bright*, and seconds-long shutters blow it to a white disc.
- At 300mm the moon **moves visibly**; stay ≤ ~1/125 to keep craters crisp.
- It fills only a small part of the frame — expect to crop hard, so nail focus.

**Expert tip:** "Looney 11" (f/11, 1/ISO, e.g. ISO 100 → 1/100) gets you in the ballpark instantly; refine from there in RAW.

**Worth adding:**
- **Longer telephoto or teleconverter** (TC-14E / 100–400 / 200–500) for a moon that fills the frame.
- **Sturdier tripod head** for rock-steady framing at long focal lengths.

---

=== CARD 13 ===
## 🚶 Street / Everyday (walk-around, candid, travel)

**When to use:** Everyday carry, candids, markets, travel, documentary — one small lens, ready to react.

**Best lens:** **AF-S DX 35mm f/1.8G** (52mm-equiv "normal" — *the* classic street focal length; small, light, fast). This is the scenario the lens was made for.

**Mode & drive:** **A** (or **P** for true grab-and-go) · Auto ISO · **Q / Qc** quiet shutter for discretion. *(Manual p.86)*

**Settings:**
- **Aperture:** **f/5.6–f/8** in daylight (deep DOF = more keepers, enables zone focus) · **f/1.8–f/2.8** as light drops or to isolate a subject.
- **ISO:** Auto, cap 3200–6400, **minimum shutter 1/125** so moving people stay sharp. *(Manual p.120)*
- **Shutter:** ≥ 1/125 for walking subjects; 1/250 for fast movement.
- **WB:** Auto · **Metering:** Matrix · **Picture Control:** Standard.
- **Focus:** AF-C single-point + back-button — *or* **zone focus** (see tip).

**Stability:** Handheld. ⚠️ **No VR on the 35mm** — keep shutter ≥ 1/60–1/80 even in low light.

**Filters:** UV optional. Polariser usually **off** — it steals ~2 stops you can't spare for fast candids.

**Gotchas:**
- **No VR + fixed focal length** — zoom with your feet, and mind the shutter floor.
- f/1.8 + a moving subject = misses; **f/4–f/5.6 in daylight hugely raises your hit rate.**

**Expert tip:** Pre-set **zone focus** — manual focus, f/8, distance ~3 m, and everything roughly 1.5–5 m is sharp. You then shoot instantly with zero AF lag (the real secret to candid street work). Pair with **Qc quiet shutter** to stay unobtrusive.

**Worth adding:**
- **Wrist strap / half-case** for fast, low-profile carry.
- Nothing optical needed — this scenario is exactly what your 35mm delivers.

---

=== ACCESSORY CARD ===
## 🔌 NEEWER TC-2 (MC-DC2) — Wired Timer Remote

*Not a scenario card — a tool reference. Plugs into the **MC-DC2 terminal** on the D7500's left side, under the rubber flap. Runs on 2× AAA. It does the one thing the ML-L3 and the in-camera interval timer **cannot**: hold Bulb open past 30 s, and repeat it automatically.*

**Connect / disconnect — order matters:**
- **Plug in:** camera **OFF** → check `TIMER ACTIVE` + `RELEASE` are *not* showing on the remote → open the terminal cap, push the plug in firmly → camera **ON**.
- **Unplug:** check `TIMER ACTIVE` + `RELEASE` are *not* showing → camera **OFF** → unplug → **replace the cap**.

**The four timer values** — press **SET** (SET flashes) → **←/→** picks the field → **↑/↓** changes the value → **SET** confirms → **TIMER START/STOP** runs it.

| Tab | Meaning | Range |
|---|---|---|
| **DELAY** | Wait before shot 1 | 0 s – 99:59:59 |
| **LONG** | Exposure length *(camera on Bulb)* | 1 s – 99:59:59 |
| **INTVL** | Start-to-start gap between shots | 1 s – 99:59:59 |
| **N** | Number of shots | 1–399, or `---` = unlimited |

- **Unlimited shots:** at `1` press **↓**, or at `399` press **↑**.
- **Interval `00:00:00` auto-becomes `00:00:01`** when you press SET.
- `TIMER ACTIVE` flashes while running — press START/STOP again to abort early.

**Two ways to shoot:**

| | **A · Remote controls the exposure** *(astro stacking, star trails, anything past 30 s)* | **B · Camera controls the exposure** *(timelapse, daylight sequences)* |
|---|---|---|
| Mode | **M** | **M** or **S** |
| Shutter | **Bulb** | Any normal speed |
| Interval timer | **OFF** *(it will fight the remote)* | **OFF** |
| Release mode | **S · single frame** | **S · single frame** |
| Focus | MF (or AF-C) | AF-C or MF |
| On the remote | **LONG** = your exposure | **LONG = 1 s**, **INTVL** > camera's shutter speed |

**⚠️ Interval rules — get these wrong and it silently drops frames:**
- **INTVL ≥ exposure + a few seconds.** Always.
- **Using autofocus?** Set a **DELAY** (not 0) and leave extra INTVL headroom. AF fires ~2 s before the shutter opens (indicator goes **green**, then **red** while the shutter is open).
- **Long Exposure NR ON → INTVL ≥ 2 × exposure.** The dark frame doubles capture time. For stacking, turn NR **OFF** and shoot your own darks.

**Manual shutter button (no timer needed):**
- **Half-press** = focus · **full press** = fire. Behaves exactly like the camera's own shutter button.
- **Slide to HOLD** = shutter held down — this is your manual Bulb. Slide back to release.
- Works **with no batteries** in the remote (display and beep just won't function).
- Works **while the timer is running** too; the shutter stays open until both releases finish.

**Other controls & power:**
- **Backlight / Lock:** tap = backlight (~6 s; any arrow press extends it). **Hold** = lock everything except the shutter + backlight buttons. Hold again to unlock.
- **Beep:** the 5th tab in the SET cycle. Off for wildlife — but a genuinely useful audible confirmation in the dark.
- **No power button.** To save batteries, make sure `TIMER ACTIVE` / `SET` / `RELEASE` are all quiet when it's stowed.
- **Low-battery icon flashing → replace *before* the session.** The timer keeps running even if the camera has stopped shooting (flat EN-EL15a, full card) — you'd never know.

**Starter recipes:**

| Job | DELAY | LONG | INTVL | N |
|---|---|---|---|---|
| **Deep-sky stack** *(200P, MF)* | 5 s | 30 s – 2 min | exposure + 5 s | `---` |
| **Star trails** *(18mm f/3.5, ISO 800)* | 5 s | 30 s | 32 s | `---` |
| **Single ultra-long** *(waterfall + ND)* | 2 s | your call | — | 1 |
| **Timelapse** *(camera-controlled, 1/250)* | 5 s | 1 s | 4 s | 300 |

**Gotchas — the two that will actually bite you:**
1. **Your back-button focus setup (a6 = AF-ON only) means half-pressing the TC-2 won't focus.** Irrelevant for astro (you're on MF). But an *autofocusing* interval sequence will fire every frame on whatever focus was last set. Either temporarily revert **a6** to enable half-press AF, or lock focus manually and leave it. Know this *before* you're standing in a field wondering why nothing's sharp.
2. **The TC-2's *timer* mode cannot drive Mirror-up (MUP).** MUP needs a *second* press to fire; the timer sends one. Timer sequences must use **single-frame** release — which is fine, because at 30 s+ mirror slap is a rounding error. (The TC-2's **manual shutter button** *can* drive MUP + EFCS — that's the short-exposure tripod route.)

---

## Sources
- **Nikon D7500 Reference Manual** — primary source of truth; page citations inline (Bulb p.79–80, ML-L3 "Time" mode p.82, U1/U2 limits p.83, release modes p.86, AF mode p.100, AF-area p.103, ISO p.118, Auto ISO p.120, metering p.123, WB p.130, Active D-Lighting p.153, Remote control mode (ML-L3) p.175, NR p.255, interval timer p.256, exposure delay d3 / EFCS d4 p.264, flash sync e1 p.265).
- **NEEWER TC-2 (MC-DC2) instruction manual** — source of truth for the Accessory Card (timer ranges, interval rules, HOLD/Bulb, lock/backlight, battery behaviour).
- [Ken Rockwell — D7500 review & how-to](https://www.kenrockwell.com/nikon/d7500.htm) · [35mm f/1.8G review](https://www.kenrockwell.com/nikon/35mm-f18-dx.htm) · [site index](https://www.kenrockwell.com/index.htm)
- [CameraTips — D7500 cheat cards](https://www.cameratips.com/nikon/d7500/cheat-cards)
