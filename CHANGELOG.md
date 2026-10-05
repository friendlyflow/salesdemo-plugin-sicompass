# Changelog

## 0.3.0

The sales demo is a program of its own now, instead of a sandboxed WebAssembly
component. Sicompass starts it and talks to it, one per tab, and it runs with your
rights. It asks for no access at all: it reads only the files it ships with.

- One build for each of Linux (x86_64 and arm64, static), macOS (Apple Silicon and
  Intel) and Windows.
- Needs a Sicompass that runs plugin programs. An older Sicompass keeps the 0.2
  version it has.
