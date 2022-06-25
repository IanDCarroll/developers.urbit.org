+++
title = "Aqua"
template = "doc.html"
[extra]
category = "arvo"
+++

**Aqua** is something like Docker but for Urbit; it is a virtualization tool whose primary purpose is testing and development.

Aqua is a [Gall](/docs/glossary/gall) app that runs an [Arvo](/docs/glossary/arvo) instance or instances in userspace. It pretends to be [Vere](/docs/glossary/vere), and as such it loads [Pills](/docs/glossary/pill) to boot up a virtual ship or fleet of ships and then manages them from within the parent Arvo instance. Running tests for a virtual fleet of Aqua ships is done using [pH](/docs/glossary/ph).

Aqua is jetted with the usual [Nock](/docs/glossary/nock) interpreter and thus virtual ships do not run any slower than the parent ship.
