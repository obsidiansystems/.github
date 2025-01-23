# 🧰 Nix Ecosystem and Infra

We use [nix](https://nixos.org/) and nixos for the majority of our projects, on every developer machine, and on most servers we deploy. We also regularly contribute to the open source nix ecosystem.

## 🪐 Nix + InterPlanetary File System
We've been working to add [IPFS support to Nix](https://github.com/obsidiansystems/ipfs-nix-guide). This involved a series of changes [to nix itself](https://github.com/obsidiansystems/ipfs-nix-guide/blob/master/branches.md), including adding [better git protocol support](https://github.com/obsidiansystems/ipfs-nix-guide/blob/master/tutorial.md#part-1-better-git--nix-integration) and [adding native support for IPFS](https://github.com/obsidiansystems/ipfs-nix-guide/blob/master/tutorial.md#part-2-ipfs--nix-integration). 
* [Software Heritage Bridge](https://blog.obsidian.systems/software-heritage-bridge/): Access SWH archive via IPFS.


## 🦀 Nix + Rust Toolchain for Hardware Wallets
[alamgu](https://github.com/alamgu/alamgu) is a Nix toolchain for writing Ledger hardware wallet applications in Rust. We originally did all our hardware wallet applications in C, and were the first to take advantage of Rust support for Ledger. We needed security and the ability to target a very specific set of devices, and for both of these criteria nix was a great fit.

## 📁 Super Colliding Nix Stores
We've been working with [Repl.it and Tweag](https://discourse.nixos.org/t/super-colliding-nix-stores/28462) to make it possible to merge local and remote nix stores. Take a look at the [local-overlay Nix store RFC](https://github.com/NixOS/rfcs/pull/152) for more on this.

## 📲 Cross-Compilation
We led the complete rewrite and upstreaming of the core [cross compilation](https://nixos.org/manual/nixpkgs/stable/#chap-cross) infrastructure in nixpkgs. A great many projects are now using this foundation to cross-compile to a variety of platforms via nix!

## λ Nix + Haskell
We use Haskell for a lot of our projects and on a lot of platforms. Nix makes this possible. We use nix to manage developer environments, deployments, and to facilitate cross-platform builds. Most of our work on cross-compilation has been merged into nixpkgs itself.
* [reflex-platform](https://github.com/reflex-frp/reflex-platform): Nix toolchain for cross-platform haskell projects.
* [splices-load-save.nix](https://github.com/obsidiansystems/splces-load-save.nix): Automated template-haskell splices for platforms that don't support TH.
* [obelisk-systemd](https://github.com/obsidiansystems/obelisk-systemd): Run an [obelisk](https://github.com/obsidiansystems/obelisk) project as a systemd service
* [openapi-hs-generator](https://github.com/obsidiansystems/openapi-hs-generator): Generate haskell API bindings from Swagger/OpenAPI specifications via Nix

## 🔐 Nix + Security
We're part of the Nix Security Working Group, and have contributed to the [nix-security-tracker](https://github.com/Nix-Security-WG/nix-security-tracker) project.

## 🧺 Nix + Miscellaneous
Even when using other package management systems or build tools, we try to use them via Nix so that things stay consistent and reproducible.
* [haven](https://github.com/obsidiansystems/haven): Retrieve maven dependencies and nixify them. We use the maven solver to build the dependency graph and then create a nix set representing all of the dependencies.
* [opam-nixify](https://github.com/obsidiansystems/opam-nixify): Nixify ocaml opam dependencies.
* [nix-daml-sdk](https://github.com/obsidiansystems/nix-daml-sdk): Packaging of the daml sdk, canton infrastrucutre, and related tools.
* [polygon-nix](https://github.com/obsidiansystems/polygon-nix): Run polygon nodes via nix.
* [nix-thunk](https://github.com/obsidiansystems/nix-thunk): A lightweight Nix dependency manager designed to make it easy to contribute improvements to dependencies upstream.
