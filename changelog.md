<!--
[//]: # (project_name = 'funTasia BloX World')
[//]: # (project_alias = 'funtasia')
[//]: # (file_name = 'changelog')
[//]: # (file_extension = 'md')
[//]: # (file_format = 'markdown')
[//]: # (file_version = {major_version = 0, minor_version = 0, patch_version = 0, suffix_version = {'unreleased', 'alpha'}})
[//]: # [!] File version numbers have to match with that release version number where the file was last amended
[//]: # (author = {surname = 'Christian', lastname = 'Trant'})
[//]: # (date_of_creation = {day = 21, month = 05, year = 2017})
[//]: # (date_of_last_change = {day = 23, month = 05, year = 2017})
[//]: # (license = 'CC0')
-->
# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

Possible entry types are 'Added', 'Changed', 'Depricated', 'Removed', 'Fixed' and 'Security'.

A release can be marked as 'YANKED'. Because of its security risks it mustn't be used anymore. Download must be prohibited.
## [0.2.0-unreleased-alpha] <!-- (YANKED) -->
## Added
- funtasia -> lua-module log_helper.lua added
- funtasia -> init.lua
  - tell_log_info(self, message) added
  - tell_error(self, message) added
  - tell_mod_identifier(self) added
  - some integrity checks added
## Changed
- funtasia -> init.lua refactored
  - local log_error(message) refactored to tell_log_error(self, message)
  - local log_message(log_type, message) refactored out to log_helper.write_log_message(log_type, mod_identifier, message)
### Depricated

### Removed

### Fixed

### Security

  ## [0.1.0-unreleased-alpha] <!-- (YANKED) -->

### Added
- emojiblox -> Emoji blocks
  - subset of EmojiOne emojis as blocks
  - descritption.txt added
- descritption.txt added
- init.lua
  - local log_error(message)
  - local log_message(log_type, message)
- commands.lua added

- recipes.lua added
  - Add cooking recipe: generic tree to 2x coal lump in 10 sec
  - Add cooking recipe: generic wood to coal lump in 8 sec
- CC0 Public Domain license added
### Changed
- init.lua refactored
  - loading recipes.lua
- debug logging improved 
  - log_info(message), log_error(message) -> local log_message(log_type, message)
  - set log_info(message) to local
### Depricated

### Removed

### Fixed

### Security

## [0.0.0-unreleased-alpha] - 2017-05-21 <!-- ([YANKED]) -->

## Added
- depends.txt
- init.lua
  - funtasia:get_version_string() added
  - log_info(message)
- license.md
  - [?] license model not sure yet
- contributing.md created
  - Olivier Lacan added
- changelog.md created
- readme.md created

# History of releases
[0.1.0-unreleased-alpha]: local
[0.0.0-unreleased-alpha]: local
