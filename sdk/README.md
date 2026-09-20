# KTerminal plugin SDK licensing boundary

Material authored for the plugin SDK in this directory, including its API
documentation and examples, is licensed under [MIT](LICENSE). It may be used to
build free or commercial plugins. Separately identified third-party material
keeps its own license.

**Status:** KTerminal does not yet implement a plugin runtime or a stable plugin
API. This directory establishes the license boundary for that work; it is not
a usable SDK release. The existing `bindings/` tree is for native app clients
and remains part of proprietary KTerminal, not the plugin SDK.

When an SDK is implemented, keep only interface definitions, client helpers,
plugin API documentation, and examples here. Keep terminal, session, rendering,
and workbench implementations outside this directory. Publish the SDK from a
separate repository or package without including proprietary implementation.

Community plugin authors retain ownership and choose their own licenses,
subject to the licenses of code they incorporate. Using this SDK neither
assigns a plugin's copyright to KTerminal nor requires that plugin to be MIT.
MIT attribution requirements still apply when SDK code is redistributed.
