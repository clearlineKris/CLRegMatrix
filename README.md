# CLRegMatrix

The published product site for **ClearLine's RegMatrix** — state-by-state cannabis regulatory intelligence across the penumbra.

Live at: `https://clearlinekris.github.io/CLRegMatrix/` (enable GitHub Pages → Settings → Pages → source: `main`, folder: `/root`).

## What this is

A Jekyll site (GitHub Pages–native) that ties the RegMatrix state offerings together as one product:

- **`index.html`** — the master index / state selector, doctrine explainer, and methodology.
- **`states/<state>/index.md`** — a per-state landing page linking to that state's six documents.
- **`states/<state>/*.md`** — the six offering documents (State Profile, Penumbrant, WCE, RegBible, Reg & Pol, Context Map), rendered by Jekyll.

## Status model

| Badge | Meaning |
|-------|---------|
| `Complete` | All six documents built and published. |
| `In progress` | Penumbral / statutory papers under development (source maintained in the Hexa_Spire working repo). |

## How to add a state

1. Build the six documents with the `regmatrix-pipeline` skill (source of truth: `Hexa_Spire/20_Doctrine/24.00/<state>/`).
2. Create `states/<state>/` and copy the six `.md` docs in.
3. Create `states/<state>/index.md` (copy an existing one, swap the summary + links).
4. Add the state to the Master Index in `index.html` under the right status group.
5. Commit and push `main`. GitHub Pages rebuilds automatically.

## Notes

- Documents carry Obsidian `[[wikilinks]]` from the working repo; these render as plain text on the site and are harmless.
- All content is regulatory intelligence, not legal advice. Citations are point-in-time.
