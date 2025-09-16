# holochain-binaries with iroh patch

This if a fork of the https://github.com/matthme/holochain-binaries

And has a patch to include darksoils iroh implementation

```toml
[patch.crates-io]
wasmer-vm = { git = "https://github.com/guillemcordoba/wasmer", branch = "fix-x86" }
wasmer-types = { git = "https://github.com/guillemcordoba/wasmer", branch = "fix-x86" }
kitsune2 = { git = "https://github.com/guillemcordoba/kitsune2", branch = "iroh-transport" }
kitsune2_api = { git = "https://github.com/guillemcordoba/kitsune2", branch = "iroh-transport" }
kitsune2_core = { git = "https://github.com/guillemcordoba/kitsune2", branch = "iroh-transport" }
kitsune2_dht = { git = "https://github.com/guillemcordoba/kitsune2", branch = "iroh-transport" }
kitsune2_gossip = { git = "https://github.com/guillemcordoba/kitsune2", branch = "iroh-transport" }
kitsune2_bootstrap_client = { git = "https://github.com/guillemcordoba/kitsune2", branch = "iroh-transport" }
```

This repo automatically builds the holochain and lair and hc binaries for Linux/macOS/Windows.
