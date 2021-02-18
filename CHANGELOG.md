# Change Log

All notable changes to the "rust-go-classic-eclipse-color-theme" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

## [1.0.0] - 2020-12-28
### Added
 - the theme file "rust-go-classic-eclipse-color-theme-color-theme.json"

## [1.0.1] - 2020-12-28
### Changed
 - Fix invalid.illegal.receive-channel.go was using a bold type face.

## [1.1.0] - 2020-12-30
### Added
 - Following scopes that seem to be newly introduced are now supported.
```
"scope": "storage.modifier.visibility.rust",
"scope": "entity.name.type.param.rust",
"scope": "entity.name.type.mod.rust",
"scope": "storage.modifier.mutable.rust",
"scope": "variable.other.mutable.rust",
"scope": "storage.type.core.rust",
"scope": "storage.class.std.rust",
"scope": "keyword.operator.sigil.rust",
"scope": "storage.type.function.rust",
"scope": "variable.other.map.rust",
"scope": "variable.other.return-value.rust",
"scope": "keyword.other.as.rust",
"scope": "variable.other.ref.rust",
"scope": "constant.other.placeholder.rust",
"scope": "support.constant.core.rust",
"scope": "keyword.other.where.rust",
"scope": "entity.name.type.generic.rust",
"scope": "storage.modifier.const.rust",
"scope": "entity.name.lifetime.rust",
"scope": "support.function.std.rust",
"scope": "support.function.core.rust",
"scope": "support.function.builtin.rust",
"scope": "punctuation.other.paren.rust",
"scope": "constant.character.escape.rust",
"scope": "storage.type.module.rust",
"scope": "entity.name.type.module.rust",
"scope": "keyword.operator.arithmetic.rust",
"scope": "constant.language.boolean.rust",
"scope": "variable.language.ignored.rust",
"scope": "entity.name.type.hashmap.rust"
```
### Changed
 - Fix constant.other.placeholder.go was set to be black instead of green.

## [1.2.0] - 2020-12-31
### Added
 - Optional color theme that supports python and typescript in addition.
### Added
 - Fix "keyword.control.fn.rust"
### Changed
 - Fix "variable.other.metavariable.specifier.rust"
 - Fix "keyword.operator.dereference.rust"

## [1.2.1] - 2021-02-18
### Changed
 - Modified "keyword.operator.arithmetic.go" from black to purple
