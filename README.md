# Cockpit Cron Weblate buffer

This repository is for automated translation synchronization. Please make
changes to the English source strings in [cockpit-cron](https://github.com/yashjawale/cockpit-cron),
and translate them in Weblate once the project has been set up.

The upstream `weblate-sync-pot` workflow periodically generates and pushes
`cockpit-cron.pot` here. Weblate reads that template and pushes translated
`<language>.po` files here. The upstream `weblate-sync-po` workflow brings
these catalogs back as reviewable pull requests after validation. English is
the source language: no `en.po` is needed.

Hosted Weblate component settings: GNU gettext PO, English source, file mask
`*.po`, template for new translations `cockpit-cron.pot`, no monolingual base
file, repository branch `main`, and push access to *this repository only*.
