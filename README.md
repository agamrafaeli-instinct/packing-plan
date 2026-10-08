# Six bags, one packing plan

A static packing checklist with six bags and 24 items. GitHub Pages publishes from `main`, repository root. No build step or backend is needed.

`index.html` contains the styles, checklist data and JavaScript. `2-packing.png` is the luggage illustration. All paths are relative, so the page works at a project directory URL ending in `/`.

Ticks save in this browser's localStorage under `packing.v1` as `{checked: {}, extras: {}}`. There is no account or cross-device sync. Ticks from the earlier site's domain do not migrate automatically. Browser storage can be cleared. If storage is unavailable, the page shows a warning and works only while open.

To revise the checklist, edit the bags array in `index.html`. Keep existing bag IDs and item positions stable to preserve the meaning of saved ticks. This repo and page are public. No license has been assigned.
