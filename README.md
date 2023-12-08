# Intellij-Community sqlite library 

This repo is a copy of the source files included in the [/platform/sqlite directory](https://github.com/JetBrains/intellij-community/tree/bb46f227f1fecc9e020bf8fb25f14ba3bfd5848e/platform/sqlite) of the [intellij-community repository](https://github.com/JetBrains/intellij-community) hosted on the hub of gitness.
The purpose of this repository was to build the library for OpenBSD which is not currently provided natively by intellij. In it's current state, it does include minor modifications to allow it's facilitation with OpenBSD. Unfortunately, it currently does not successfully build the desired library.
This failure is the result of differencing versions of the ld linkage library. 

So...yeah.
