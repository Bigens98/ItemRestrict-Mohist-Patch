# ItemRestrict (Named IDs / Mohist 1.12.2 Patch)

An updated and enhanced version of the original **ItemRestrict 2.4.1** plugin by CraftersLand. Designed to solve the issue of shifting numerical IDs on Forge+Bukkit hybrid Minecraft servers by introducing permanent Material Name support.

---

### 🖥️ Supported Server Cores & Versions

* **Minecraft Version:** `1.12.2` (Primary target)
* **Tested Hybrid Cores (Forge + Bukkit):**
  * ✅ **Mohist 1.12.2** (Fully tested & recommended)
  * ✅ **CatServer 1.12.2** (Compatible)
  * ✅ **Magma 1.12.2** (Compatible)
  * ✅ **Crucible 1.12.2** (Compatible)
* **Vanilla / Bukkit Cores:**
  * ✅ **Spigot / Paper 1.12.2** (Works for standard vanilla material names)

> ⚠️ **Note:** Not compatible with Minecraft 1.13+ due to Bukkit API material flattening changes.

---

### ✨ Key Features

1. **Named Material IDs:** Use text-based material names (e.g. `CFM_COMPUTER:*` or `ic2:te:1`) instead of shifting numerical IDs.
2. **Auto Converter (`/ir convert`):** Convert your entire legacy `RestrictedItems.yml` from numbers to names with a single command (includes dual-check protection and automatic backups).
3. **In-Game Hand Management:**
   * `/ir check` — View exact item name, current ID, and active restrictions for the held item.
   * `/ir add <section> [data] [reason]` — Add held item directly to a restriction list.
   * `/ir remove [section]` — Remove held item restrictions.
4. **Pickup Handling Customization (`bmw-settings.yml`):** Prevent item destruction on ground pickup (`remove-item-on-pickup: false`) with automatic item repelling.
5. **Localization:** Multi-language message support (`uk`, `ru`, `en`) via `/ir lang`.

---

### 📜 Commands & Permissions

* `/ir check` — Inspect held item properties
* `/ir add <section> [data] [reason]` — Add restriction for held item
* `/ir remove [section]` — Remove restriction for held item
* `/ir convert [preview]` — Convert config to material names
* `/ir reload` — Reload configuration files
* `/ir lang <uk|ru|en>` — Switch message language
* **Permission:** `ItemRestrict.admin`

---

### ⚖️ License & Credits

* **Original Plugin:** ItemRestrict 2.4.1 by CraftersLand.
* **Patch Author:** Bigens98 (Big MineWorld).
* **License:** GNU General Public License v3.0 (GPLv3).
