# Bijnis Beats: published knowledge maps

This repository holds only the **signed knowledge-map bundles** that Beats laptops download by themselves.

* `latest.json` names the newest bundle.
* `bundles/beats-map-<version>.zip` is the bundle (YAML descriptions of tables, columns, metrics and vetted questions). It holds **no data rows**.
* A laptop installs a bundle only if its signature matches the publisher key built into the Beats program. A file changed or added here by anyone else is refused, so write access to this repository is the only thing that needs protecting.

Published by the Beats owner with `beats bundle release` (see `docs/MAP_UPDATES.md` in the Beats repository). Do not edit files here by hand.
