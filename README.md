<!-- BEGIN_ANSIBLE_DOCS -->

# Ansible Role: trippsc2.bleachbit
This role runs Bleachbit from a portable executable on Windows systems.

## Requirements

| Platform | Versions |
| -------- | -------- |
| Windows | 2016, 2019, 2022 |

## Dependencies

| Collection |
| ---------- |
| chocolatey.chocolatey |
| community.windows |

## Role Arguments
|Option|Description|Type|Required|Choices|Default|
|---|---|---|---|---|---|
| bleachbit_options | List of BleachBit options to clean. See https://docs.bleachbit.org/doc/cleanerml.html for a list of available options. | list of 'str' | no |  | ["deepscan.cache", "deepscan.ds_store", "deepscan.thumbs_db", "deepscan.tmp", "deepscan.vim_swap_root", "deepscan.vim_swap_user", "internet_explorer.cache", "internet_explorer.cookies", "internet_explorer.downloads", "internet_explorer.forms", "internet_explorer.history", "internet_explorer.logs", "paint.mru", "system.clipboard", "system.logs", "system.memory_dump", "system.muicache", "system.prefetch", "system.recycle_bin", "system.tmp", "system.updates", "windows_defender.backup", "windows_defender.history", "windows_defender.logs", "windows_defender.quarantine", "windows_defender.temp", "windows_explorer.mru", "windows_explorer.recent_documents", "windows_explorer.run", "windows_explorer.search_history", "windows_explorer.shellbags", "windows_explorer.thumbnails", "windows_media_player.cache", "windows_media_player.mru", "wordpad.mru"] |


## License
MIT

## Author and Project Information
Jim Tarpley
<!-- END_ANSIBLE_DOCS -->
