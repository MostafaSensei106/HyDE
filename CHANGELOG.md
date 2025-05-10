# Changelog

## [0.2.0](https://github.com/MostafaSensei106/HyDE/compare/v0.1.5...v0.2.0) (2025-04-29)


### Features

* --filetypes arg to indicate filetypes for wallpaper.sh ([0c0369a](https://github.com/MostafaSensei106/HyDE/commit/0c0369a634835da49a95254a64694458f4ebb45d))
* add Kitty tab bar styling and add new tab shortcut ([eb04da7](https://github.com/MostafaSensei106/HyDE/commit/eb04da7cd9aa89f952b0a71b3cff6fe25227e934))
* Add some new fastfetch icons ([#411](https://github.com/MostafaSensei106/HyDE/issues/411)) ([289eff0](https://github.com/MostafaSensei106/HyDE/commit/289eff04fbd72936647e49b4328edb8a9b1d57a0))
* add wallet false to fix popup keyring prompt ([d4cdf18](https://github.com/MostafaSensei106/HyDE/commit/d4cdf18ac534dc9336b6d6c7aef83b14606cd235))
* Add xdg-user-dirs as deps. This package is not used for now but will be used on further iterations. ([a14c524](https://github.com/MostafaSensei106/HyDE/commit/a14c5245743309a02092cd1695274c86dbe06eb1))
* Added hydectl, Official CLI for HyDE ([5dc5719](https://github.com/MostafaSensei106/HyDE/commit/5dc57193cd3a0499ffaa1344eb61e7e21d64a25e))
* Added Icon them meta data into ~/.icons/default ([f9b1e68](https://github.com/MostafaSensei106/HyDE/commit/f9b1e68fc46acb139c7cbc07e5ee15e459ba75de))
* Added OCR script  and check package function to validate ([6c8b9c3](https://github.com/MostafaSensei106/HyDE/commit/6c8b9c3a6a136e71758ae7f8e6a764042669e107))
* Added workflow modes ([#480](https://github.com/MostafaSensei106/HyDE/issues/480)) ([8017ed9](https://github.com/MostafaSensei106/HyDE/commit/8017ed9aed184ceb06b3ac42f3250fb2f84b2280))
* Handle cursors and font for gtk3 settings. ([55d62ce](https://github.com/MostafaSensei106/HyDE/commit/55d62ce963f457aa554cd5fecb3470928dfe915e))
* Put print_log as logging to avoid issues in stdout  ([#432](https://github.com/MostafaSensei106/HyDE/issues/432)) ([167a1cd](https://github.com/MostafaSensei106/HyDE/commit/167a1cd2e04a3e00ae23ac7a63c46a503f047c51))
* Screen Recorder script ([#477](https://github.com/MostafaSensei106/HyDE/issues/477)) ([9c34033](https://github.com/MostafaSensei106/HyDE/commit/9c3403302f7384c856558c6c08632cad1ea8183e))
* x2 pacman query see https://github.com/HyDE-Project/HyDE/pull/445 ([8fc47b2](https://github.com/MostafaSensei106/HyDE/commit/8fc47b292d971bf82bcf286b3d399bc40fb76dc0))
* x2 pacman query see https://github.com/HyDE-Project/HyDE/pull/445 ([fb870e8](https://github.com/MostafaSensei106/HyDE/commit/fb870e80e9e2d4ed7fe92b5e926ef5eee33f89f0))


### Bug Fixes

* [Bug]: Short description of the issue [#503](https://github.com/MostafaSensei106/HyDE/issues/503) ([d9131e6](https://github.com/MostafaSensei106/HyDE/commit/d9131e65dd9a263ab72e5d1f12f00daeab1624f7))
* [Docs]: Wrong shortcut listed in KEYBINDINGS.md [#504](https://github.com/MostafaSensei106/HyDE/issues/504) ([4b6bd6e](https://github.com/MostafaSensei106/HyDE/commit/4b6bd6e48f049114f22f4688cd590af445a2b7b2))
* A few typos ([#398](https://github.com/MostafaSensei106/HyDE/issues/398)) ([56e22cb](https://github.com/MostafaSensei106/HyDE/commit/56e22cb329363a7337d7070a9c666071296745a8))
* **animations:** not sourced || wrong sourced path ([26ac697](https://github.com/MostafaSensei106/HyDE/commit/26ac69715aaed8f788d981c4078a5d6dbbb01312))
* cava arg parsing ([cc7db47](https://github.com/MostafaSensei106/HyDE/commit/cc7db478021e9152cc121c961ba90e7351f6fd8a))
* codium-flags instead of vscodium ([f5a974b](https://github.com/MostafaSensei106/HyDE/commit/f5a974bd9ec12046170864e8b0ee028d060ec5cf))
* color setter  fix  disown logic ([70365f8](https://github.com/MostafaSensei106/HyDE/commit/70365f8266f773c3be9d6ba3fe5b746a11ec6ecb))
* Corrects folder Icon ([4b86be5](https://github.com/MostafaSensei106/HyDE/commit/4b86be51c18bea8384fcb9b6e5afc4ab86a39cb6))
* CURSORS. Steam and other apps relying on xdg_share/icons/default/index.theme follows theme ([2ba9a90](https://github.com/MostafaSensei106/HyDE/commit/2ba9a90372597add7b8f850692b9c0210e8feaeb))
* discord colors ([f8a68bc](https://github.com/MostafaSensei106/HyDE/commit/f8a68bc212c0f548faaa02dd12517f204e2bda00))
* editor mode should at least have  blur if not opaque ([40da9da](https://github.com/MostafaSensei106/HyDE/commit/40da9daba860197e9b655a530a7f261d7e553493))
* fix the package manager alias ([#396](https://github.com/MostafaSensei106/HyDE/issues/396)) ([c4de251](https://github.com/MostafaSensei106/HyDE/commit/c4de251855a87e3ef4cd30e798e3c08f8f5fd164))
* follow up [#501](https://github.com/MostafaSensei106/HyDE/issues/501) ([b56686e](https://github.com/MostafaSensei106/HyDE/commit/b56686e6f0101378dc621a246ae15d39de80da2a))
* gethashmap should not include logos, added error handeling for animations.sh ([c362ac4](https://github.com/MostafaSensei106/HyDE/commit/c362ac45cfaa7ad293bed5b04bf8df2a7a9a07e8))
* gethashmap should not include logos, added error handling for animations.sh ([79ed088](https://github.com/MostafaSensei106/HyDE/commit/79ed0887d3f32affa003f206f5cdd5f809e5f53f))
* Handle if pokego do not exist! Update .hyde.zshrc ([d347033](https://github.com/MostafaSensei106/HyDE/commit/d3470337f2764d4de7b53b4da942416c43b00a25))
* hyde-shell ([94909a6](https://github.com/MostafaSensei106/HyDE/commit/94909a64ac8fab8041fc4fe1d4b0b51107f8d0b7))
* **hyprlock:** Put warning on bottom-left corner. ([023c6fc](https://github.com/MostafaSensei106/HyDE/commit/023c6fc0d1cba10f154e8373ca912cf4f5e1785f))
* Provide request package for weather.py and versioned requirements ([9b674f8](https://github.com/MostafaSensei106/HyDE/commit/9b674f84f860ed6a6cc0b7687ba5d2f7fb772e35))
* remove alias for ls and fix looping in command_not_found_handler ([eef2597](https://github.com/MostafaSensei106/HyDE/commit/eef2597a5f9cc755d64ae6232a3c20e24dee5180)), closes [#388](https://github.com/MostafaSensei106/HyDE/issues/388)
* remove alias for ls and fix looping in command_not_found_handler ([00c1d19](https://github.com/MostafaSensei106/HyDE/commit/00c1d19c9460be341e2252c787f817da092dbc03)), closes [#388](https://github.com/MostafaSensei106/HyDE/issues/388)
* Rofi uwsm launcher command ([8c00f58](https://github.com/MostafaSensei106/HyDE/commit/8c00f58e88b665de8197756c02c2a3945fd6a234))
* rofilaunch and improve arg parsing ([b417b81](https://github.com/MostafaSensei106/HyDE/commit/b417b8197f5d6e854e6ea744e2bec95d2698f32c))
* **screenrecord:** help message ([bd04422](https://github.com/MostafaSensei106/HyDE/commit/bd0442280c91ee41eed8d6203a64845f036d4e40))
* some systems can't resolve path without realpath. ([156cd90](https://github.com/MostafaSensei106/HyDE/commit/156cd909d7c50bee2a641224eee16e9d964dfc0c)), closes [#406](https://github.com/MostafaSensei106/HyDE/issues/406)
* spotify jsonc ([d5aa5cf](https://github.com/MostafaSensei106/HyDE/commit/d5aa5cf22bdf396d7cd5389cf81be316f30ff80d))
* Typos ([#393](https://github.com/MostafaSensei106/HyDE/issues/393)) ([9cfc9e9](https://github.com/MostafaSensei106/HyDE/commit/9cfc9e9ce6926e77c22ca884cf81203f59534dfb))
* wallpaper.sh --set comment: https://github.com/HyDE-Project/HyDE/issues/406#issuecomment-2761655834 from issue https://github.com/HyDE-Project/HyDE/issues/406 ([63e229d](https://github.com/MostafaSensei106/HyDE/commit/63e229d4b17bf4f6e7cb9b773308342e2a02b5aa))
* wallpaper.sh errors ([a2487bf](https://github.com/MostafaSensei106/HyDE/commit/a2487bfa518bf779d68251ed2c5f83889ba93ee0))


### Performance Improvements

* Loaded hypr.theme in advance then wallbash ([87217f9](https://github.com/MostafaSensei106/HyDE/commit/87217f9126f1cda44d5df6b6371a92f974f299a2)), closes [#451](https://github.com/MostafaSensei106/HyDE/issues/451)


### Reverts

* wrong branch ([71aeb95](https://github.com/MostafaSensei106/HyDE/commit/71aeb9504324f9a3d1235387058223e8ac9f242e))
