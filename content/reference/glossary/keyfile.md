+++
title = "Keyfile"

template = "doc.html"
[extra]
category = "azimuth"
+++

A **keyfile** is a piece of information used to associate a [ship](/docs/glossary/ship) with an Urbit identity so that the ship can use the [Arvo](/docs/glossary/arvo) network. A keyfile is dependent upon the [networking keys](/docs/glossary/bridge) that have been set for the identity; we recommend using [Bridge](/docs/glossary/bridge) to set the networking keys and to generate the corresponding keyfile.

The keyfile is used as an argument in the command line when booting a ship. During the boot process, [Vere](/docs/glossary/vere) passes the keyfile into the Arvo state.

### Further Reading

- [Installation Guide](/getting-started/): Instructions on using a keyfile to boot a ship.
