# Weblate helper repository for cockpit-podman

Repository for syncing Weblate translations. If you are not a bot, please ignore this repository.

This repository is for automated translation synchronization. Please make
changes to the English source strings in [cockpit-cron](https://github.com/yashjawale/cockpit-cron),
and translate them in Weblate.

The upstream `weblate-sync-pot` workflow periodically generates and pushes
`cockpit-cron.pot` here. Weblate reads that template and pushes translated
`<language>.po` files here. The upstream `weblate-sync-po` workflow brings
these catalogs back as reviewable pull requests after validation. English is
the source language.

