## 0.9.0
### Changed
- fixproj.toml: Bumped `fix_version` to 1.6.0. Depends on minilib-common@0.15.0.

## 0.8.0
### Changed
- Merged PR#2 (thanks to tttmmmyyyy san).
  - Migrate to the unboxed-Array standard library.
  - fixproj.toml: Bumped `fix_version` to 1.5.0.
- Upgraded to minilib-common@0.14.0.

## 0.7.4
### Changed
- Upgraded to minilib-common@0.13.2.
- Modified some code to remove the deprecation warnings.

## 0.7.3
### Changed
- Upgraded to minilib-common@0.13.1, hashmap@2.0.0.

## 0.7.2
### Changed
- Utilized minilib-common@0.13.0.

## 0.7.1
### Added
- Minilib.App.Clap: Added `Command::empty`, `Command::find_subcommand`, `ArgMatches::get_flag`, `ArgMatches::dispatch_subcommands`.
### Changed
- Utilized minilib-common@0.12.3.

## 0.7.0
### Changed
- fixproj.toml: Bumped `fix_version` to 1.3.0. Depends on minilib-common@0.12.0.

## 0.6.0
### Changed
- Minilib.App.Clap: The effect of a boolean arg, which has a `set_true()` or a `set_false()` action, will be negated if `--no-{long-option}` is specified in the command line.
- Minilib.App.Clap: Update documentation

