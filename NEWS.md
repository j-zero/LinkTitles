# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

For changes prior to version 6.0.0, please see [`NEWS.old`](news.old).

## [6.0.0][] - 2019-12-31

### Changed

- Because automatic linking upon page save no longer works with MediaWiki
  versions 1.32 and newer, the default value of the `$wgLinkTitlesParseOnRender`
  is now `true`. Please see `README.md` for more information.

### Fixed

- Prevent crash that occurred with MediaWiki version 1.34 due to a renamed
  constant (DB_SLAVE was renamed to DB_REPLICA). NOTE that the minimum
  required version of MediaWiki is now 1.28 (which is an obsolete version).

[6.0.0]: https://github.com/bovender/LinkTitles/releases/tag/v6.0.0
