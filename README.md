# Industrial Agentic AI use cases: GE Vernova AI Symposium

A 31-slide, 3D animated technical walkthrough (Mastek × Faclon Labs) of:

1. **Power plant co-pilot: RCA agents.** 21 MW cogeneration, live. A 4-agent chain on Bruce, ontology + smart context, 37 parameters every hour, 98.4% validated accuracy.
2. **Auxiliary power reduction agents.** 90 MW captive plant, application live, savings validation under way. 114 drive signals, best-day benchmarks, coal personas, a day-ahead scheduler, 8% → 7% target.
3. **AI closed-loop soot blowing** (technical reference). 16 MW recovery boiler, live. EM + Extended Kalman Filter soft sensor, MPC-style scheduler, 9-point safety gate, −30% blowing steam.

There is also a technology section covering the Faclon stack, a technical deep dive per product, and the IT/OT reference architecture. A closing section has the one-page summary and GE Vernova Q&A readiness.

`index.html` is self-contained. The logo is embedded, and Three.js (cdnjs, r128) and Google Fonts load from CDNs.

## Host on GitHub Pages

1. Create a repository (private recommended, see the note below) and push `index.html` and this README to the `main` branch root.
2. In the repository, go to **Settings → Pages → Build and deployment → Source: Deploy from a branch**, then pick `main` / `(root)` and save.
3. The site goes live at `https://<user>.github.io/<repo>/`. Deep link a slide with `#5`.

## Controls

- `←` / `→`, Page Up / Page Down, or the on-screen arrows: change slide · `M`: slide list · `F`: full screen
- Drag the 3D scene to rotate it; double-click resets the view
- Interactive slides: stack layer chips, product tabs, agent cards, live-example steps, and the aux-power value calculator

## Sources

- Review meeting transcript, 26 Oct 2026 (Nirmal K, Parth Chaudhary, Abhay Kale, Mohan)
- Faclon Labs solution pages (Oct 2026): "GE Vernova AI Symposium – Faclon × Mastek" (v4), "Power Plant Co-pilot: RCA Agents – Technical Brief" (v3), "Auxiliary Power Reduction Agents – Technical Brief", "AI Closed-Loop Soot Blowing – Technical Brief", "Power Plant AI Dashboards"

Items tagged **TBC** are still pending from Faclon. Visuals labelled "illustrative" or "schematic" are explanatory, not plant data.

**Confidentiality:** the deck holds customer names, plant data and architecture details that Faclon shared privately. Use a **private** repository, or get Faclon's agreement before publishing it publicly.
