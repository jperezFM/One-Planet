# One Planet, Four Sciences

Interactive 3D study sites for the four NYSSLS Regents sciences, plus **Sphere Connections**, which shows how the geosphere, hydrosphere, atmosphere and biosphere interact and how every course helps explain them.

| Folder | Site | Course |
|---|---|---|
| `/` | One Planet, Four Sciences + Sphere Connections | all four |
| `earth/` | Cosmos to Core | Earth and Space Sciences |
| `biology/` | Molecule to Biosphere | Life Science: Biology |
| `chemistry/` | Nucleus to New York | Physical Science: Chemistry |
| `physics/` | Spark to Supernova | Physical Science: Physics |

## Publish on GitHub Pages
1. Create a repository and upload everything in this folder (including the hidden `.nojekyll` file) to the root.
2. Settings → Pages → Deploy from a branch → `main`, `/ (root)` → Save.
3. The site appears at `https://<username>.github.io/<repository>/`.

Every course page has an **⌂ All sciences** button back to the home page. Links such as `chemistry/#HS-PS1-8-nointro` open a standard directly (`-nointro` skips the start screen). Add `#explore` to the home address to skip the home screen and open Sphere Connections.

The pages load three.js, topojson-client and Google Fonts from public CDNs, so they need an internet connection. Student progress is saved only in each browser.
