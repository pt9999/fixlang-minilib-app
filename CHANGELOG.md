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

