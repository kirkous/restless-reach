---
title: Changelog
---

# Changelog

## 24. 9. 2026 – Initial Server Configuration

První kompletní konfigurace modpacku pro Restless Reach.

### 🌍 World & Progression

**Seasonality**
- zapnuta roční období
- propojeno se ZenPath pro zimní gameplay

**ZenWorldSettings**
- progression nastaven jako per-player
- vypnuta replikace player keys mezi okolními hráči
- globální keys se automaticky nepřenášejí na nové postavy

**ZenRaids**
- raid progression oddělen od automatických global keys
- cílem je zachovat smysluplné raidy i pro nové postavy na starším světě

---

### 🗺️ Exploration

**More World Locations AIO**
- povoleny nové POI
- povoleny nové / procedurální dungeony
- povoleny Shipping Ports
- vypnuti dodateční tradeři
- vypnuti trainers
- vypnuty shrines
- vypnuty waypoint / teleport systémy
- custom location YAML zatím nepoužíván

**Dvala**
- Crypts: ON
- Caves: ON
- Mines: ON
- Hildir Rooms: ON
- Camps: OFF
- Ashlands: OFF
- interior veins lze obnovit
- reset interval: **120 herních dní**
- reset obsazených dungeonů zakázán

---

### 🛣️ Seasons & Paths

**ZenPath**
- dirt / wood / metal stamina usage: **60 %**
- paved / stone stamina usage: **25 %**
- zimní movement speed: **85 %**
- Seasonality `season_winter` používán jako snow state

---

### 🎒 Inventory & Equipment

**ExtraSlots**
- equipment slots povoleny
- utility slot povolen
- 3 Quick Slots
- další inventory rows vypnuty
- food slots vypnuty
- misc slots vypnuty

**ExtraSlotsCustomSlots**
- aktivní AdventureBackpacks slot
- ostatní nepoužívané mod slots vypnuty
- Backpack slot se zpřístupní až po objevení backpacku

**AdventureBackpacks**
- backpack používá vlastní equipment slot
- zachovány biome progression recepty
- special effects ponechány aktivní
- crafting / building z backpacku povolen
- overflow a auto-store povoleny

---

### ⚔️ Combat & Weapons

**ValheimArmory**
- většina weapon balance ponechána podle autora
- early magic ponechána aktivní
- vanilla sledges zachovávají vanilla attack styl
- Abyssal Razor nepřeváděn na blunt weapon
- vanilla Flint Spear / Flint Axe nahrazeny VA variantami

**ZenCombat**
- zachováno především combat QoL
- globální damage / movement multipliers ponechány blízko vanilla hodnotám
- žádný výrazný overall combat rebalance

---

### 🔨 Building

**ZenConstruction**
- crafting z otevřených containerů povolen
- crafting station používá blízký container
- attached cart lze používat při stavění
- vehicle container auto-open range zvýšen na **12 m**
- normal building on scenery povolen
- vypnut automatický full refund defensive stakes
- vypnut NoMap build cursor reset
- paved road nedeformuje terén
- synchronizace double doors zapnuta
- advanced rotation zapnuta

**ZenRedecorate**
- při přesouvání je hráč encumbered
- nosné konstrukční části nelze přesouvat
- support warning zapnut
- max carry range: **35 m**
- max grip range: **5 m**
- fire pits / bonfires / hearths / windmills nelze přesouvat

---

### 🛒 Logistics

**ZenDistributor**
- distribuce z Cart / Karve / Longship povolena
- distribution range: **10 m**
- cart attach distance: **5 m**
- připojení převráceného cartu povoleno
- odstraněn artificial cart mass ceiling
- hmotnost nákladu tedy zůstává důležitá
- Strength potion může pomoci s taháním cartu

---

### ♻️ Recycling

**ZenRecycle**
- recycling přes Obliterator aktivní
- vrací jednu náhodně zvolenou surovinu
- každé použití stojí **1× Thunderstone**
- ochrana proti portal exploitům aktivní
- ingoty lze převádět zpět na ore / scrap
- spalování trash itemů povoleno v Bonfire / Iron Fire Pit
- ničení itemů přímo na zemi vypnuto

---

### 🌀 Portals

**UnifiedTargetPortal**
- target-based portal system
- Public / Private portály
- vanilla item teleport restrictions zachovány
- nepojmenované portály nejsou běžně nabízeny jako cíle

---

### 💀 Player Rules

**ZenPlayer**
- equipment se po smrti nezachovává automaticky
- Drop On Death: All
- jídlo se po smrti nezachovává
- skill loss zachován blízko vanilla pravidlům
- Corpse Run / No Skill Drain ochrany aktivní

---

### 🖥️ UI & QoL

**ZenUI**
- lepší crafting UI
- recipe grouping / sorting
- search
- craftable-first
- multicraft
- rozšířené tooltipy
- ZenUI equipment slots vypnuty ve prospěch ExtraSlots

**ZenHoverItem**
- rozšířené hover informace pro kontejnery a crafting zařízení

**ZenItemStands**
- pohodlnější práce s Item / Armor Stands

**ZenBeehive**
- vylepšená práce s honey a beehives

**ZenLogin**
- klientské login QoL

---

### 🌐 Network

**NetworkPerformanceSystem**
- ponechán na výchozí konfiguraci
- další tuning až podle reálného multiplayer provozu

---

### 🔧 Utility

**VehicleRemoval**
- výchozí konfigurace

**ZenRecycle / ZenDistributor / ZenRedecorate**
- nakonfigurovány tak, aby QoL nenahrazovalo klasickou Valheim logistiku

---

## Filosofie první verze

První konfigurace serveru se snaží držet čtyř pravidel:

1. **QoL má odstranit klikání, ne gameplay.**
2. **Exploration má být bohatší než vanilla.**
3. **Progression a doprava mají stále význam.**
4. **Nový obsah má působit jako rozšíření Valheimu, ne jako jiná hra.**