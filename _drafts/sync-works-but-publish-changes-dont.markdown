---
title: sync works but publish changes don't
date: 2023-02-15 19:47:00 -05:00
---

things get very technical in getting siteleaf and github repository and github pages all to work in sync, not sure exactly how all of it has to fit just right together, but from the looks of things, Siteleaf has an error with Published failed

GET https://api.github.com/repos/bibletld/bibletld.github.io/git/refs/heads?per_page=100: 401 - Bad credentials // See: https://docs.github.com/rest

but yet the status for Synced is successful

um, okay, scratch that.. use just the sync tab in settings, and not the hosting tab in settings here on Siteleaf, and things seem to go much better
