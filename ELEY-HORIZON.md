# ELEY Horizon

An ELEY customization of the God’s Eye View source checkout. The ELEY entry point is `index.html`: open it directly in a modern browser. It uses CDN Cesium, Tailwind and Lucide, so internet access is required, but no npm install or build is needed.

## What works now

A satellite and terrain globe; 30 fictional customer assets; clustered asset selection; four closed freeze contour polygons; a 0–72 hour simulation timeline; point-in-polygon exposure classification; warning rings; fleet totals; and a downloadable, simulated drain-alert manifest. No messages are sent.

## Custom settings

Edit the `eley-settings` JSON block inside `index.html`. It controls the camera, colors, freeze thresholds and local draft mode. Embedded customer nodes and illustrative freeze contours are in the following inline script. The source selectors describe the current demo; they are not functioning live adapters.

`CRITICAL_BURST` is an illustrative exposure class at 28°F or below, not proof of a burst or a validated product failure threshold. Public satellite and elevation services may fall back or be unavailable. All customer addresses are fictional; coordinates approximate city centers.

## Shared agent skill

Use the installed `$eley-horizon` skill to open the console or generate aggregate briefs from supplied customer points and forecast contours. It refers to the shared `$eley-freeze-readiness` policy and contracts. The Eley Growth Engine can consume those briefs to propose regional care reminders.

## Next capabilities

Import a restricted customer dataset with verified locations and ownership; connect timestamped forecast temperature contours or gridded forecasts; reconcile Weather for Email and existing reminders; resolve channel consent and suppressions; add episode deduplication; and implement an approved sender behind the Growth Engine’s existing gate. These are future work, not installed services.

## Upstream and licensing

Source: https://github.com/bilawalsidhu/gods-eye-view
Base revision: 208814a094104c9a3d6f1af75635d2d5be5fbfbc
The original Vite entry remains in `index.upstream.html`; upstream modules are retained for future integration. This profile replaces the entry point with a standalone ELEY console and adapts the upstream viewer defaults. It does not install or activate the upstream MCP server. Keep LICENSE and THIRD_PARTY_NOTICES.md. Upstream third-party datasets remain archival source and are not loaded by this ELEY entry point.
