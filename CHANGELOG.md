# Changelog

## [0.19.0](https://github.com/Mattis1337/BmSDK/compare/v0.18.0...v0.19.0) (2026-09-06)


### Features

* Add "Level", "Name" params to SpawnActor ([#96](https://github.com/Mattis1337/BmSDK/issues/96)) ([ac89337](https://github.com/Mattis1337/BmSDK/commit/ac89337da70af0f44602d35a61d627ad6cb1fee0))
* Add AllowSubtypes property to RedirectAttribute ([#46](https://github.com/Mattis1337/BmSDK/issues/46)) ([9527d39](https://github.com/Mattis1337/BmSDK/commit/9527d39ad28e363c2f644370751d1e4cf50c24cf))
* Add Dispose() function to FString ([#88](https://github.com/Mattis1337/BmSDK/issues/88)) ([fbba37d](https://github.com/Mattis1337/BmSDK/commit/fbba37d014591e8f7bfdf594db368596c1f055dd))
* Add enumerable wrapper for inline arrays ([#97](https://github.com/Mattis1337/BmSDK/issues/97)) ([be27b66](https://github.com/Mattis1337/BmSDK/commit/be27b6658c3ed9b2fc6a2042deb14574d986c426))
* Add further helper functions to InlineArray ([#105](https://github.com/Mattis1337/BmSDK/issues/105)) ([300eb74](https://github.com/Mattis1337/BmSDK/commit/300eb74464853cd240f282befcb3d763b9fc01c3))
* Add Game.FindObjects() ([#81](https://github.com/Mattis1337/BmSDK/issues/81)) ([4d86356](https://github.com/Mattis1337/BmSDK/commit/4d863561a691237ddf7dac3eb9e50b67832ebdb8))
* Add interface support ([#49](https://github.com/Mattis1337/BmSDK/issues/49)) ([49a468f](https://github.com/Mattis1337/BmSDK/commit/49a468f0816c3ed9f9f13e9b6e31d45c142ca35e))
* Add multiple redirect support ([#40](https://github.com/Mattis1337/BmSDK/issues/40)) ([c4384b8](https://github.com/Mattis1337/BmSDK/commit/c4384b8dc416fce102d2b59d485050fe07f7e17f))
* Add sequence graph traversal helpers ([#56](https://github.com/Mattis1337/BmSDK/issues/56)) ([6a65492](https://github.com/Mattis1337/BmSDK/commit/6a6549232f48133e55cc7421045fc1f9e5d7dc87))
* Add strongly-typed .DefaultObject helper ([#82](https://github.com/Mattis1337/BmSDK/issues/82)) ([3d43f8f](https://github.com/Mattis1337/BmSDK/commit/3d43f8f645d9832a8292c0c3b5debf7dbc6aa59d))
* Add VSCode workspace for ScriptsDev  ([#76](https://github.com/Mattis1337/BmSDK/issues/76)) ([f12ecd1](https://github.com/Mattis1337/BmSDK/commit/f12ecd12c3fe723d1f0fdf24d16907211b6181ce))
* Allow a function to global redir multiple types ([#108](https://github.com/Mattis1337/BmSDK/issues/108)) ([fa0c807](https://github.com/Mattis1337/BmSDK/commit/fa0c807a9ba4d72393b8462433a111185c8b3eec))
* Allow intrinsic classes to contain properties ([#115](https://github.com/Mattis1337/BmSDK/issues/115)) ([1d7c52e](https://github.com/Mattis1337/BmSDK/commit/1d7c52e8076a96d3cba4a4431dda5f2c0a6efa3e))
* Allow usage of Mod in Script ctor ([#89](https://github.com/Mattis1337/BmSDK/issues/89)) ([238322d](https://github.com/Mattis1337/BmSDK/commit/238322d5f87aceec8465950e97aabb448e9a5ff6))
* Emit debug symbols for compiled Mods ([#91](https://github.com/Mattis1337/BmSDK/issues/91)) ([894a311](https://github.com/Mattis1337/BmSDK/commit/894a311b62cf7cd9aab54ff031cd03de0da5d60c))
* Fall back to next known super in case of unknown class ([#131](https://github.com/Mattis1337/BmSDK/issues/131)) ([acb7a26](https://github.com/Mattis1337/BmSDK/commit/acb7a26e04ea5235c7f7adb3cc421ee21089a72b))
* Fix window detection ([#69](https://github.com/Mattis1337/BmSDK/issues/69)) ([938c923](https://github.com/Mattis1337/BmSDK/commit/938c923ddeafd8575f12c5cd52355e12e7803f73))
* **generator:** Return struct properties as "ref" ([#80](https://github.com/Mattis1337/BmSDK/issues/80)) ([c63d2f1](https://github.com/Mattis1337/BmSDK/commit/c63d2f1f694a9298126ec7f1dcbb9420e71a526b))
* Make DetourUtil public ([#73](https://github.com/Mattis1337/BmSDK/issues/73)) ([74cb4b1](https://github.com/Mattis1337/BmSDK/commit/74cb4b17a0ac55fcb5675356414f4181416de12a))
* Make GetPlayerPawn() return null ([#107](https://github.com/Mattis1337/BmSDK/issues/107)) ([b28001c](https://github.com/Mattis1337/BmSDK/commit/b28001c5afaa228eb878b28c0c2e6491c3c4b3da))
* Make GetSC return null instead of throwing ([#106](https://github.com/Mattis1337/BmSDK/issues/106)) ([f4e7b1a](https://github.com/Mattis1337/BmSDK/commit/f4e7b1a3756acb73f36f502997ac4e58aeeecb0e))
* Make IsValid into a property ([#63](https://github.com/Mattis1337/BmSDK/issues/63)) ([f0bdd52](https://github.com/Mattis1337/BmSDK/commit/f0bdd5241ddadb128125aef8950929828cac16fe))
* Make MarshalUtil partially public ([#86](https://github.com/Mattis1337/BmSDK/issues/86)) ([c256140](https://github.com/Mattis1337/BmSDK/commit/c256140aeec27726eb24145ad00f1ec42285097f))
* Make MemUtil public ([#75](https://github.com/Mattis1337/BmSDK/issues/75)) ([53849e4](https://github.com/Mattis1337/BmSDK/commit/53849e4820e90ae846d29dd02bc8123a7b0a3739))
* Make ToManaged() and ToUnmanaged() public ([#87](https://github.com/Mattis1337/BmSDK/issues/87)) ([206beeb](https://github.com/Mattis1337/BmSDK/commit/206beeb19cd5f5f83bc8285e783b8b4dfca646bb))
* Marshal FVector as Vector3, add Rotator type ([#44](https://github.com/Mattis1337/BmSDK/issues/44)) ([444e0bb](https://github.com/Mattis1337/BmSDK/commit/444e0bbc0675ebfdf77122c54496b48fe57bbbd6))
* Port C# FName ToString behavior to Generator ([#99](https://github.com/Mattis1337/BmSDK/issues/99)) ([2bd767c](https://github.com/Mattis1337/BmSDK/commit/2bd767c61f3026477356ba3081addea06d6237bb))
* Print error messages to on-screen overlay ([#102](https://github.com/Mattis1337/BmSDK/issues/102)) ([2ebcc0d](https://github.com/Mattis1337/BmSDK/commit/2ebcc0d562112eef1de5492b066e482da136e2f8))
* **SDK:** Make GetPlayerPawn() give a RPawnPlayer ([19cc546](https://github.com/Mattis1337/BmSDK/commit/19cc5464cf59467862a2786c35a19979c87399c1))
* Set "BATMAN2" macro for scripts ([#109](https://github.com/Mattis1337/BmSDK/issues/109)) ([e2f71cf](https://github.com/Mattis1337/BmSDK/commit/e2f71cfc40fe1c695aadb4dbdc9e29556942d233))
* Support any UObject with ScriptComponents ([#71](https://github.com/Mattis1337/BmSDK/issues/71)) ([a804b9b](https://github.com/Mattis1337/BmSDK/commit/a804b9b8d040b7e45460ba48ee44172a90c3684d))
* Support inline unrealscript arrays ([#67](https://github.com/Mattis1337/BmSDK/issues/67)) ([a0319da](https://github.com/Mattis1337/BmSDK/commit/a0319da55702f05b011f3ea03994ece969dc1f7f))
* Support multiple script components of the same type ([#77](https://github.com/Mattis1337/BmSDK/issues/77)) ([ceb86a7](https://github.com/Mattis1337/BmSDK/commit/ceb86a7e2dd197fcaf3cf5cbb84a28ac6591a6a9))
* Support new "mods" format ([#85](https://github.com/Mattis1337/BmSDK/issues/85)) ([0936577](https://github.com/Mattis1337/BmSDK/commit/0936577b09739666f1f77bb5c370df46f7eb806e))
* Support new() syntax for spawning actors ([#94](https://github.com/Mattis1337/BmSDK/issues/94)) ([8c368aa](https://github.com/Mattis1337/BmSDK/commit/8c368aa95bc6f9852dc74166ad6859ccc63e048c))
* Support object preloading for mods ([#93](https://github.com/Mattis1337/BmSDK/issues/93)) ([764cd1c](https://github.com/Mattis1337/BmSDK/commit/764cd1c182a534faff43d61b5cfd7a50e66480aa))
* Support TArray instantiation ([#62](https://github.com/Mattis1337/BmSDK/issues/62)) ([b8c8029](https://github.com/Mattis1337/BmSDK/commit/b8c8029fb24e6577e6d8661680ad9d9676150183))
* Support TArray resizing ([#60](https://github.com/Mattis1337/BmSDK/issues/60)) ([bb76c72](https://github.com/Mattis1337/BmSDK/commit/bb76c72279880c3d66d174a47da01033bf491555))
* Update publish script with new file naming ([#65](https://github.com/Mattis1337/BmSDK/issues/65)) ([f5b2f5f](https://github.com/Mattis1337/BmSDK/commit/f5b2f5f4a9a74fe6e0ec42f1a326c0130f812bb7))


### Bug Fixes

* Adjust RF_NeedPostLoad offset ([d8732a6](https://github.com/Mattis1337/BmSDK/commit/d8732a61f21d1da0182215cb6e5f590db30da8c7))
* Explicitly declare Rotator mem layout ([1d96dd8](https://github.com/Mattis1337/BmSDK/commit/1d96dd8b41303647cc8264b4c1cd31e5b620138b))
* Fix a divide by zero error in TArray.Resize ([#66](https://github.com/Mattis1337/BmSDK/issues/66)) ([43812ab](https://github.com/Mattis1337/BmSDK/commit/43812ab2a2bd9a90e54c3377ba9809e6d1e125af))
* Fix scripts not being loaded since host update ([#127](https://github.com/Mattis1337/BmSDK/issues/127)) ([5bb7ecb](https://github.com/Mattis1337/BmSDK/commit/5bb7ecbe68400c715bb5da0bbf9da6287b7f67ed))
* Fix syntax errors introduced by [#63](https://github.com/Mattis1337/BmSDK/issues/63) ([fc58044](https://github.com/Mattis1337/BmSDK/commit/fc5804440011ef667f9e888dd1629f7b413f25a9))
* Generate enums with underlying type byte ([#95](https://github.com/Mattis1337/BmSDK/issues/95)) ([5ade522](https://github.com/Mattis1337/BmSDK/commit/5ade5228ab2274dcb58430226351a2f2afbfadc2))
* **host:** Use hostfxr_initialize_for_dotnet_command_line for self-contained support ([#122](https://github.com/Mattis1337/BmSDK/issues/122)) ([fc369cb](https://github.com/Mattis1337/BmSDK/commit/fc369cb06cd624aab946565f83b8fa8e72a291a1))
* Improve class coverage ([#57](https://github.com/Mattis1337/BmSDK/issues/57)) ([2d0ca11](https://github.com/Mattis1337/BmSDK/commit/2d0ca11932e0ff921e9f860302516f88cd573d18))
* **input:** Fix OnKeyDown not firing when run through Steam ([#125](https://github.com/Mattis1337/BmSDK/issues/125)) ([6f311a0](https://github.com/Mattis1337/BmSDK/commit/6f311a02ebcc405e4255bbfef9e40a24698eaf67))
* Logic bug in Guards.Bounds() ([4ca0dd6](https://github.com/Mattis1337/BmSDK/commit/4ca0dd683d004b62d03d8077f8e99e1b1bbf193a))
* Manual function redirect not configured ([#43](https://github.com/Mattis1337/BmSDK/issues/43)) ([6f93b4c](https://github.com/Mattis1337/BmSDK/commit/6f93b4c2f1cba206b0321240dfb14e515b1654ae))
* Print FName suffixes ([#90](https://github.com/Mattis1337/BmSDK/issues/90)) ([28c79ee](https://github.com/Mattis1337/BmSDK/commit/28c79eeed5eb28d49c38084ded92ea3dc540d0fe))
* Redirect UFunctions with empty bodies ([#42](https://github.com/Mattis1337/BmSDK/issues/42)) ([9b13196](https://github.com/Mattis1337/BmSDK/commit/9b1319679ef289a62be4ef8a7836d9960cb29451))
* Redirects of base functions causing infinite recursion  ([#98](https://github.com/Mattis1337/BmSDK/issues/98)) ([d6e0990](https://github.com/Mattis1337/BmSDK/commit/d6e0990985d96b70ac8498b798ef305a7fdba24b))
* SCs auto-attaching to CDOs ([#72](https://github.com/Mattis1337/BmSDK/issues/72)) ([dd812a3](https://github.com/Mattis1337/BmSDK/commit/dd812a3b7067b67b920a6b0b6a8710fdfdafac4a))
* **sdk:** Fix crash when detaching script components within OnTick() ([#51](https://github.com/Mattis1337/BmSDK/issues/51)) ([3c67555](https://github.com/Mattis1337/BmSDK/commit/3c67555c2e1a76d1329f6e49162b06ede9b6ba70))
* **sdk:** Fix TArray.Pop() always resizing to 0 ([#41](https://github.com/Mattis1337/BmSDK/issues/41)) ([d4676a4](https://github.com/Mattis1337/BmSDK/commit/d4676a46e8ffa293ecaf0bafa311fcf2b8852c00))
* Switch to positional params in DemoScript ([ac5176f](https://github.com/Mattis1337/BmSDK/commit/ac5176f102e7e4946daa224d80d8795e5288a0fe))
* UFunction overrides not translating to generated code ([#68](https://github.com/Mattis1337/BmSDK/issues/68)) ([ca69266](https://github.com/Mattis1337/BmSDK/commit/ca69266de429638eaecc904ec06aac1dfde06af5))
* Use degree instead of RUUs in SpinScript ([b7f4963](https://github.com/Mattis1337/BmSDK/commit/b7f4963edd12deb6fd962840d3a8ffa216b7de63))

## [0.18.0](https://github.com/Team-BmSDK/BmSDK-AC/compare/v0.17.2...v0.18.0) (2026-08-23)


### Features

* Fall back to next known super in case of unknown class ([#131](https://github.com/Team-BmSDK/BmSDK-AC/issues/131)) ([acb7a26](https://github.com/Team-BmSDK/BmSDK-AC/commit/acb7a26e04ea5235c7f7adb3cc421ee21089a72b))

## [0.17.2](https://github.com/Team-BmSDK/BmSDK-AC/compare/v0.17.1...v0.17.2) (2026-07-10)


### Bug Fixes

* Fix scripts not being loaded since host update ([#127](https://github.com/Team-BmSDK/BmSDK-AC/issues/127)) ([5bb7ecb](https://github.com/Team-BmSDK/BmSDK-AC/commit/5bb7ecbe68400c715bb5da0bbf9da6287b7f67ed))
* **input:** Fix OnKeyDown not firing when run through Steam ([#125](https://github.com/Team-BmSDK/BmSDK-AC/issues/125)) ([6f311a0](https://github.com/Team-BmSDK/BmSDK-AC/commit/6f311a02ebcc405e4255bbfef9e40a24698eaf67))

## [0.17.1](https://github.com/Team-BmSDK/BmSDK-AC/compare/v0.17.0...v0.17.1) (2026-07-10)


### Bug Fixes

* **host:** Use hostfxr_initialize_for_dotnet_command_line for self-contained support ([#122](https://github.com/Team-BmSDK/BmSDK-AC/issues/122)) ([fc369cb](https://github.com/Team-BmSDK/BmSDK-AC/commit/fc369cb06cd624aab946565f83b8fa8e72a291a1))

## [0.17.0](https://github.com/Team-BmSDK/BmSDK-AC/compare/v0.16.0...v0.17.0) (2026-07-09)


### Features

* Allow intrinsic classes to contain properties ([#115](https://github.com/Team-BmSDK/BmSDK-AC/issues/115)) ([1d7c52e](https://github.com/Team-BmSDK/BmSDK-AC/commit/1d7c52e8076a96d3cba4a4431dda5f2c0a6efa3e))

## [0.16.0](https://github.com/Team-BmSDK/BmSDK-AC/compare/v0.16.0...v0.16.0) (2026-06-24)


### Features

* Add further helper functions to InlineArray ([#105](https://github.com/Team-BmSDK/BmSDK-AC/issues/105)) ([300eb74](https://github.com/Team-BmSDK/BmSDK-AC/commit/300eb74464853cd240f282befcb3d763b9fc01c3))
* Allow a function to global redir multiple types ([#108](https://github.com/Team-BmSDK/BmSDK-AC/issues/108)) ([fa0c807](https://github.com/Team-BmSDK/BmSDK-AC/commit/fa0c807a9ba4d72393b8462433a111185c8b3eec))
* Make GetPlayerPawn() return null ([#107](https://github.com/Team-BmSDK/BmSDK-AC/issues/107)) ([b28001c](https://github.com/Team-BmSDK/BmSDK-AC/commit/b28001c5afaa228eb878b28c0c2e6491c3c4b3da))
* Make GetSC return null instead of throwing ([#106](https://github.com/Team-BmSDK/BmSDK-AC/issues/106)) ([f4e7b1a](https://github.com/Team-BmSDK/BmSDK-AC/commit/f4e7b1a3756acb73f36f502997ac4e58aeeecb0e))
* Set "BATMAN2" macro for scripts ([#109](https://github.com/Team-BmSDK/BmSDK-AC/issues/109)) ([e2f71cf](https://github.com/Team-BmSDK/BmSDK-AC/commit/e2f71cfc40fe1c695aadb4dbdc9e29556942d233))


### Bug Fixes

* Logic bug in Guards.Bounds() ([4ca0dd6](https://github.com/Team-BmSDK/BmSDK-AC/commit/4ca0dd683d004b62d03d8077f8e99e1b1bbf193a))
