# Orkestra Staging — Development & Testing Build

**Orkestra Staging** is the same Brain + Gateway as production, preconfigured to talk to the **staging API** for local testing and development.

## When to use this add-on

- Testing new Orkestra features before they ship to production
- Developing against `https://staging-api.orkestra-assistant.com`
- Running a staging instance side-by-side with the production **Orkestra** add-on

## Getting Started

1. Click **Install**. New installs default to **Start on boot** (`boot: auto`) and expose an Ingress sidebar entry (**Show in sidebar** / `panel_title: Orkestra Staging`).
2. Open the **Configuration** tab and enter your **Orkestra Cloud** credentials:
   - **Orkestra Cloud URL** — defaults to `https://staging-api.orkestra-assistant.com`
   - **Orkestra Instance Token** — from your staging Orkestra Cloud account
3. Save, start the add-on if needed, then open **Orkestra Staging** from the Home Assistant sidebar.

**Auto-update** is a Home Assistant user preference — Supervisor does not allow add-ons to enable it by default. Turn it on in the add-on info page if you want automatic upgrades.

Home Assistant API access is configured automatically — no long-lived access token required for normal add-on use.

---

*Questions or feedback? Visit the [Orkestra Beta add-on repository](https://github.com/orkestrasmarthome/orkestra-ha-addon-beta).*
