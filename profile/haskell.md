# λ Building Apps in Haskell

We've built a lot of applications in Haskell, and along the way we've contributed lots of reusable parts to the Haskell ecosystem.

## 🖼️ Full-Stack Framework
* [obelisk](https://github.com/obsidiansystems/obelisk): full-stack haskell applications

## 🖱️ GUIs
* [reflex](https://github.com/reflex-frp/reflex): functional reactive programming
* [reflex-dom](https://github.com/reflex-frp/reflex-dom): DOM-based FRP GUIs

## ⌨️ TUIs & CLIs
* [reflex-vty](https://github.com/reflex-frp/reflex-vty): Build terminal apps with FRP
* [cli-extras](https://github.com/obsidiansystems/cli-extras): Tools for writing CLIs, including logging, process management, and printing to the terminal

## 🏗️ Infrastructure & Tools
* [reflex-platform](https://github.com/reflex-frp/reflex-platform/): Nix tooling to build multi-platform Haskell apps
* [reflex-ghci](https://github.com/reflex-frp/reflex-ghci): Run GHCi from within a Reflex FRP application and interact with it using a functional reactive interface.
* [gargoyle](https://github.com/obsidiansystems/gargoyle): A framework for managing daemons from Haskell and libraries for use with postgresql and nix
* [openapi-hs-generator](https://github.com/obsidiansystems/openapi-hs-generator): Nix wrapper for the openapi generator CLI tool to automatically generate haskell bindngs from openapi specifications.

## 🧑‍🏫 Examples
* [reflex-examples](https://github.com/reflex-frp/reflex-examples): See Reflex FRP in action with tinker-friendly code samples you can run yourself.
* [reflex-todomvc](https://github.com/reflex-frp/reflex-todomvc): TodoMVC implemented with reflex
* [obelisk-examples](https://github.com/obsidiansystems/obelisk-examples): Examples of full-stack applications using Obelisk
* [Lithograph](https://gitlab.com/obsidian.systems/lithograph): an example obelisk app that implements a very simple blog.
* [reflex-gadt-api example](https://github.com/reflex-frp/reflex-gadt-api?tab=readme-ov-file#example-usage): Example of a full-stack Haskell application with an API specified as a GADT.

## 📚 Libraries

### 🐚 Shell and Filesystem interaction
* [reflex-process](https://github.com/reflex-frp/reflex-process): Run and interact with system processes from within a Reflex FRP application.
* [reflex-fsnotify](https://github.com/reflex-frp/reflex-fsnotify): Watch files and directories for changes using a functional-reactive interface
* [directory-contents](https://github.com/obsidiansystems/directory-contents): Recursively build a tree of directory contents, avoiding symlink cycles
* [coquina](https://github.com/obsidiansystems/coquina): A very convenient shell command monad
* [which](https://github.com/obsidiansystems/which): Like the linux `which` command, to bake in the path to an executable

### 💾 Database
* [beam-automigrate](https://github.com/obsidiansystems/beam-automigrate): Automatically generated migrations for beam databases
* [gargoyle-postgresql](https://github.com/obsidiansystems/gargoyle/tree/develop/gargoyle-postgresql): tools for managing PostgreSQL servers that can live in local folders and communicate via a Unix domain socket or be run remotely
* [postgresql-lo-stream](https://github.com/obsidiansystems/postgresql-lo-stream): Library for streaming large objects to and from PostgreSQL in Haskell

### 📡 API
* [reflex-gadt-api](https://github.com/reflex-frp/reflex-gadt-api): Interact with a JSON-serialized API defined by a GADT in your reflex-dom application
* [snap-stream](https://github.com/obsidiansystems/snap-stream): Snap handlers for streaming access with range requests

### 📱 Cross-platform
* [obelisk-ios-libfrontend](https://github.com/obsidiansystems/obelisk-ios-libfrontend): Compile your obelisk frontend as a C library that can be used with an XCode project.
* [android-activity](https://github.com/obsidiansystems/android-activity): embed a haskell application in an android app as an Android Activity.

### 🧬 Datastructures
* [patch](https://github.com/reflex-frp/patch): Data structures for describing changes to other data structures.
* [dependent-sum-template](https://github.com/obsidiansystems/dependent-sum-template): Template Haskell code to generate instances of classes found in the `some` package
* [commutative-semigroups](https://github.com/obsidiansystems/commutative-semigroups): semigroup where the order of arguments to mappend does not matter
* [constraints-extras](https://github.com/obsidiansystems/constraints-extras): Convenience functions for working with constraints
* [dependent-sum](https://github.com/obsidiansystems/dependent-sum): Dependent sums and supporting typeclasses for comparing and displaying them
* [dependent-map](https://github.com/obsidiansystems/dependent-map): Dependently-typed finite maps (partial dependent products)
* [vessel 🍶](https://github.com/obsidiansystems/vessel): Functor-parametric containers
* [aeson-gadt-th](https://github.com/obsidiansystems/aeson-gadt-th): Template Haskell for generating ToJSON and FromJSON instances for GADTs

### 🪝 Integrations
* [haveibeenpwned](https://github.com/obsidiansystems/haveibeenpwned): Haskell library that uses the HIBP breach database to evaluate passwords
* [dombuilder-pandoc](https://github.com/obsidiansystems/dombuilder-pandoc): Convert Pandoc documents into reflex-dom nodes.
* [echarts-jsdom](https://github.com/obsidiansystems/echarts-jsdom): Bindings for the echarts.js library for use with GHCJS.
* [reflex-dom-echarts](https://github.com/obsidiansystems/reflex-dom-echarts): echarts.js + reflex-dom!
* [obelisk-oauth](https://github.com/obsidiansystems/obelisk-oauth): OAuth authentication from an Obelisk app.
* [hs-openmoji-data](https://github.com/obsidiansystems/hs-openmoji-data): OpenMoji for Haskell
* [obelisk-google-analytics](https://github.com/obsidiansystems/obelisk-google-analytics): Google Analytics for Obelisk apps.
* [haven](https://github.com/obsidiansystems/haven): Use haskell to produce a nix set of maven dependencies
* [gitea-api](https://github.com/obsidiansystems/gitea-api): Gitea API bindings for Haskell
* [vikunja-api](https://github.com/obsidiansystems/vikunja-api): [Vikunja](https://vikunja.io/) API bindings for Haskell
