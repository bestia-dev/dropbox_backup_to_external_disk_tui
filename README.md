<!-- markdownlint-disable MD041 -->
[//]: # (auto_md_to_doc_comments segment start A)

# dropbox_backup_to_external_disk_tui

[//]: # (auto_cargo_toml_to_md start)

**TUI binary executable, one way sync from Dropbox to external disc**  
***version: 2023.820.1613 date: 2023-08-20 author: [bestia.dev](https://bestia.dev) repository: [Github](https://github.com/bestia-dev/dropbox_backup_to_external_disk_tui/)***  

[//]: # (auto_cargo_toml_to_md end)

![pre-alpha](https://img.shields.io/badge/pre_alpha-red) 
![work-in-progress](https://img.shields.io/badge/work_in_progress-yellow) 

[//]: # (auto_lines_of_code start)
[![Lines in Rust code](https://img.shields.io/badge/Lines_in_Rust-1549-green.svg)](https://github.com/bestia-dev/dropbox_backup_to_external_disk_tui/)
[![Lines in Doc comments](https://img.shields.io/badge/Lines_in_Doc_comments-280-blue.svg)](https://github.com/bestia-dev/dropbox_backup_to_external_disk_tui/)
[![Lines in Comments](https://img.shields.io/badge/Lines_in_comments-182-purple.svg)](https://github.com/bestia-dev/dropbox_backup_to_external_disk_tui/)
[![Lines in examples](https://img.shields.io/badge/Lines_in_examples-0-yellow.svg)](https://github.com/bestia-dev/dropbox_backup_to_external_disk_tui/)
[![Lines in tests](https://img.shields.io/badge/Lines_in_tests-0-orange.svg)](https://github.com/bestia-dev/dropbox_backup_to_external_disk_tui/)

[//]: # (auto_lines_of_code end)

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/bestia-dev/dropbox_backup_to_external_disk_tui/blob/main/LICENSE)
[![Rust](https://github.com/bestia-dev/dropbox_backup_to_external_disk_tui/workflows/rust_fmt_auto_build_testuto_build_test/badge.svg)](https://github.com/bestia-dev/dropbox_backup_to_external_disk_tui/)
![Hits](https://bestia.dev/webpage_hit_counter/get_svg_image/584868797.svg)

Hashtags: #rustlang #tutorial #dropbox #tui  
My projects on Github are more like a tutorial than a finished product: [bestia-dev tutorials](https://github.com/bestia-dev/tutorials_rust_wasm).

## TUI

This compiles into a [TUI](https://en.wikipedia.org/wiki/Text-based_user_interface) binary executable. All the user interface is inside this project.  
The main dependency is to the library project `dropbox_backup_to_external_disk_lib` that contains all the program logic.  I separated this projects to show how to use the same library from different binary projects. It is difficult to separate this two layers afterwards. They should be separated from the start.  
Different user-interfaces need different workflows and the common library must allow this. Modern computers and phones are all multi-core. Even javascript has multi-thread capabilities with web-workers. It is recommended to create multi-threaded applications. Most of the calls to the library will be done in a separate thread to have the possibility of communication between the 2 layers (UI and logic). For example for progress bars and similar long running tasks.  

## Development

I use cargo-auto to write all repetitive tasks in automation_tasks_rs.  

## Open-source and free as a beer

My open-source projects are free as a beer (MIT license).  
I just love programming.  
But I need also to drink. If you find my projects and tutorials helpful, please buy me a beer by donating to my [PayPal](https://paypal.me/LucianoBestia).  
You know the price of a beer in your local bar ;-)  
So I can drink a free beer for your health :-)  
[Na zdravje!](https://translate.google.com/?hl=en&sl=sl&tl=en&text=Na%20zdravje&op=translate) [Alla salute!](https://dictionary.cambridge.org/dictionary/italian-english/alla-salute) [Prost!](https://dictionary.cambridge.org/dictionary/german-english/prost) [Nazdravlje!](https://matadornetwork.com/nights/how-to-say-cheers-in-50-languages/) 🍻

[//bestia.dev](https://bestia.dev)  
[//github.com/bestia-dev](https://github.com/bestia-dev)  
[//bestiadev.substack.com](https://bestiadev.substack.com)  
[//youtube.com/@bestia-dev-tutorials](https://youtube.com/@bestia-dev-tutorials)  

[//]: # (auto_md_to_doc_comments segment end A)
