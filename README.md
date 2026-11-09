# Tenmoku registry

This repository holds [Tenmoku](https://github.com/darylrobbins/tenmoku)'s built grammar
artifacts and the signed index the editor installs languages from. Nothing here is edited by
hand: the artifacts, the index and its signature are published from CI in darylrobbins/tenmoku,
where the grammar sources live (`extensions/grammars/`).

Releases carry the published files. The index is signed with the registry's own Ed25519 key,
separate from the app's update key.
