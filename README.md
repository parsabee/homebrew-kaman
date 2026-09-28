# homebrew-kaman

Homebrew tap for [KamanEngine](https://github.com/parsabee/KamanEngine), a Rust game engine for
Apple platforms that renders with raw Metal.

```sh
brew install parsabee/kaman/kaman-engine
kaman-demo
```

**Apple Silicon (arm64) Macs only** — Homebrew refuses to install on Intel Macs.

Installs the prebuilt `kaman-demo` (the engine's playable demo) and the engine source under
`$(brew --prefix)/share/kaman-engine/src` for use as Cargo path dependencies. Run
`brew info kaman-engine` for details.

The canonical formula lives in the main repo at
[`packaging/homebrew/kaman-engine.rb`](https://github.com/parsabee/KamanEngine/blob/main/packaging/homebrew/kaman-engine.rb).
