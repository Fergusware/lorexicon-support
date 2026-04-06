# **🪄 The Lorexicon Grimoire of Creation**

_Your PF2e Arcane Companion — Foundry VTT & Web_

---

### Choosing Your Platform

Lorexicon offers two paths to the forge:

|                  | **Lorexicon Web**                                    | **Foundry VTT Module**                                                    |
| ---------------- | ---------------------------------------------------- | ------------------------------------------------------------------------- |
| **Best for**     | Quick access from any browser — no Foundry required  | GMs who run their games in Foundry VTT                                    |
| **Requirements** | A modern web browser and a Patreon account           | Foundry VTT v12.343+, PF2e Remaster v6.12+                                |
| **Creations**    | Stored in your Lorexicon library                     | Placed directly into your Foundry world                                   |
| **Get started**  | [Chapter I: Lorexicon Web](#chapter-i-lorexicon-web) | [Chapter II: The Foundry Module](#chapter-ii-invoking-the-foundry-module) |

Both platforms share the same creation engine and interface — your prompts, contexts, and job history work identically on either.

---

### Chapter I: Lorexicon Web

1. Navigate to **[app.fergusware.com](https://app.fergusware.com)** in your browser.
2. Click **Sign in with Patreon** to forge your pact and enter the realm.
3. Behold the enchanted prompt window, alive with your monthly usage display.

That's it — no installation, no dependencies, just arcane creation at your fingertips.

> **Tip:** The **☰ hamburger menu** in Lorexicon Web lets you switch between the **Parchment** (Light) and **Grimoire** (Dark) themes, and toggle image generation on or off — the same option Foundry users find in their module settings.

---

### Chapter II: Invoking the Foundry Module

1. In Foundry's **Add-on Modules → Install Module**, seek out [Lorexicon](https://foundryvtt.com/packages/lorexicon) and click Install:

   ![Lorexicon Install](./images/installation.png)

   Should you require, you may paste the manifest directly from the Oracle:

   ```
   https://raw.githubusercontent.com/Fergusware/lorexicon-support/refs/heads/main/manifests/module.json
   ```

2. Click **Install**, then in **Manage Modules** enable **Lorexicon**.
3. Restart your Foundry realm if the fates demand it.

**Compatibility runes:**

- **Foundry VTT**: v12.343 or later
- **Pathfinder 2e Remaster**: v6.12 or later
- **Dependencies**: None — Lorexicon stands alone

---

### Chapter III: Opening the Lorexicon Portal

To call Lorexicon forth:

- **Lorexicon Web:** Navigate to [app.fergusware.com](https://app.fergusware.com) and log in — you'll arrive at the creation portal directly.
- **Foundry VTT:** Venture to either the **Actors** tab or **Journal** tab and click the **Lorexicon** button nestled at the bottom.

On first start, you will be prompted to **Bind Your Patreon Pact** (see below). Behold the enchanted prompt window, alive with your monthly usage display.

---

### Chapter IV: Binding Your Patreon Pact

When you first awaken Lorexicon's arcane circuits, you must forge a Patreon pact:

- **Lorexicon Web:** Click **Sign in with Patreon** on the login page. Grant Lorexicon access to view your Patreon identity, pledges, and account status. Success delivers you to the creation portal.
- **Foundry VTT:** A popup window beckons — ensure your browser allows pop-ups for your Foundry domain. Grant the same Patreon access in that window. Success seals the pact — Lorexicon's welcome grimoire unfurls in Foundry. Failure or denial scrawls an error in chat.

On either platform, you may unbind the ritual at any time by clicking the 🔗 Unlink icon in the Usage panel.

---

### Chapter V: The Welcome Invocation

When first summoned, Lorexicon will unfurl its greeting, welcoming you to the forge of creation.

---

### Chapter VI: Crafting Your Creation

| **Element**     | **Description**                                                                                                          |
| --------------- | ------------------------------------------------------------------------------------------------------------------------ |
| **Type**        | **NPC**, **Creature**, **Hazard**, **Encounter**, or **Merchant**                                                        |
| **Prompt**      | Textarea (up to 50,000 characters) for your narrative or mechanical visions                                              |
| **Result**      | When the summoning is complete, displays your creation's name, linked to its new document                                |
| **Usage Panel** | • **Completed:** x / y<br>• **Remaining:** z (flames red at 0)<br>• **Patreon ID:** 12345 🔗<br>• **Subscription:** free |
| **Buttons**     | • **Submit**: begin creation<br>• **Cancel**: close the window<br>• **Reset**: clear all fields                          |

Below, a **Progress Bar** pulses while the forge works its magic (~30-60 seconds).

---

### Chapter VII: Consulting the Prompt Advisor

Before you commit your incantation to the forge, consider calling upon the **Prompt Advisor**. Click the **Advise** button (right next to Submit), and it will review your prompt and return a revised version with an explanation of what it changed and why. A dialog presents the Advisor's counsel — click **Use** to accept the suggestions, or **Discard** to keep your original text.

The Prompt Advisor **does not count against your monthly quota** — only the final Submit spends a spell slot. Discard the suggestions and you can consult it again; once you click Use, the Advisor steps aside for that creation. For the full guide, see [The Prompt Advisor](Prompt-Advisor).

---

### Chapter VIII: The Summoning of Your Creation

When the progress bar runs its course:

- Lorexicon conjures your creation into being — in Foundry, it's safely nestled within a "Lorexicon" folder on the **Actor** or **Journal** tab; in Lorexicon Web, it appears on-screen and in your library.
- The creation opens automatically.
- The **Result** rune bears the name of the creation as a link -- your new creation awaits.

_No further import rituals are required to begin using your creation._

---

### Chapter IX: Tracking Your Magical Quota

Each month's magic is finite. Observe your Usage Panel:

- **Completed:** Prompts expended this month
- **Remaining:** Spells left (resets at the turn of the calendar)
- **Patreon ID:** Your bonded Patreon identity (click 🔗 to sever the bond)
- **Subscription:** Your current tier

Hover any rune for further illumination.

---

### Chapter X: When the Fates Frown

Should darkness cloud your ritual:

| **Affliction**                   | **Lorexicon's Response**                                                     |
| -------------------------------- | ---------------------------------------------------------------------------- |
| **Auth Denied/Failure**          | An "authentication error" appears — retry the login or pop-up and try again. |
| **Quota Depleted**               | A red "Remaining" rune blazes 0; a warning cries "No more magic."            |
| **Generation Timeout/API Error** | "Generation failed — please try again."                                      |
| **Popup Blocked/Closed/Timeout** | (Foundry) "Patreon authentication failed. Allow pop-ups and retry."          |

---

### Chapter XI: Sage Advice & Troubleshooting

- **Lorexicon button vanished? (Foundry)** Ensure the module is enabled and your realm restarted.
- **Pop-up barred? (Foundry)** Permit pop-ups for your Foundry domain.
- **Can't log in? (Web)** Ensure your browser accepts cookies from app.fergusware.com.
- **Remaining stuck at 0?** Quotas renew at the start of each calendar month.
- **Auth errors persist?** Click 🔗 to unlink, then reforge your Patreon pact.

---

### Appendix: Of Deeper Runes and Hidden Scripts

For those who would wield Lorexicon's magic in more intricate ways--binding theme, tone, structure, or lore across multiple summonings--look beyond these pages to the scroll titled:

🧠 [Contexts: Anchoring Your Arcane Intent](Contexts)

This companion tome reveals how to store and reuse prompt fragments, customize behaviors, and guide the generative spirits with precision.

_May its guidance sharpen your craft._

---

_Go forth, brimming with confidence. May every NPC you summon serve your tale, and may your creatures be legends in their own right._
