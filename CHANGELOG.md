# Change Log

All notable changes to the `vscode-dtdl` extension will be documented in this file.

## v1.2.0 (2022-04-27)

- Accumulated updates & fixes from the 1.1.x pre-release iterations.

## v1.1.3 pre-release (2022-04-21)

- Fix package-lock.json versioning.

## v1.1.2 pre-release (2022-04-21)

- Uses `dtdl-language-server` `0.4.7`.
  - Adds language support for unknown adjunct co-types.
  - Usage of '`commandType`' produces a warning indicating deprecation in DTDL v2.
  - Improved `@context` evaluation.
  - Improved detection of IoT Central context when using central semantic types (nested context are evaluated).
  - Code action for resolving lack of IoT Central context when needed and root `@context` is an array changed to an 'append' instead of a 'replace'.
  - Error is shown when using complex schema type of 'Array' under a 'Property' type element (v2 constraint).
  - Fixed bug where undefined or empty text file body caused an error when using code completion.

## v1.1.1 pre-release (2022-02-24)

- A new quick fix for `@context` is available if an IoT Central semantic type is used and the Central context is missing.
  - Uses `dtdl-language-server` `0.4.6`.

## v1.1.0 pre-release (2022-02-09)

- Support for IoT Central Semantic Types (through increment of `dtdl-language-server` to `0.4.5`).
  - Added validation to ensure the IoT Central context IRI exists when using an IoT Central specific semantic type.

## v1.0.0 (2020-09-30)

- Adds built-in code snippets.
- Adds support for user defined templates.

## v0.2.0 (2020-08-10)

- Adds support for basic semantic type and units.

## v0.1.1 (2020-07-06)

- Changed the extension logo.

## v0.1.0 (2020-05-19)

- Adds support for syntax validation.
- Adds Intellisense to help with DTDL language syntax (including auto-completion).
- Create interfaces from the command palette.
