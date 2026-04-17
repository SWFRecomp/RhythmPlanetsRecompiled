# Recomp Template

A base to start recompiling a SWF.

## Building

1. Run `SWFRecomp config.toml`.

1. Build this folder in Visual Studio.

## Maintaining the AS2Runtime

1. Clone this repo (and recurse submodules) and clone `SWFRecomp/AS2Runtime` too.

1. In your `AS2Runtime` folder, make your changes to the runtime API.

1. Run `make` in the `AS2Runtime` folder.

1. Copy the resulting `runtime7.swf` into your `RecompTemplate` folder.

1. Follow the build instructions for this repo.