# Changelog

## [2.2.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v2.1.0...v2.2.0) (2024-07-02)


### Features

* add issue template ([#119](https://github.com/CloudNationHQ/terraform-azure-vm/issues/119)) ([75e1343](https://github.com/CloudNationHQ/terraform-azure-vm/commit/75e1343e043fb7a0d6ad74e0f1199716d74215f5))
* **deps:** bump github.com/Azure/azure-sdk-for-go/sdk/azidentity ([#115](https://github.com/CloudNationHQ/terraform-azure-vm/issues/115)) ([d8d5bf0](https://github.com/CloudNationHQ/terraform-azure-vm/commit/d8d5bf04caf6ab332b276be639f4b4d4b6a33528))
* **deps:** bump github.com/Azure/azure-sdk-for-go/sdk/azidentity ([#116](https://github.com/CloudNationHQ/terraform-azure-vm/issues/116)) ([9d3aa6d](https://github.com/CloudNationHQ/terraform-azure-vm/commit/9d3aa6da0c53512563771bf5411cd85712a5d424))
* **deps:** bump github.com/gruntwork-io/terratest in /tests ([#118](https://github.com/CloudNationHQ/terraform-azure-vm/issues/118)) ([f1e5f7a](https://github.com/CloudNationHQ/terraform-azure-vm/commit/f1e5f7af50eb85f8999a3152ed5e1b37bb9d2576))
* **deps:** bump github.com/hashicorp/go-getter in /tests ([#117](https://github.com/CloudNationHQ/terraform-azure-vm/issues/117)) ([6c48c7b](https://github.com/CloudNationHQ/terraform-azure-vm/commit/6c48c7bdb0e48ca9595f22c5d8354455883654bb))

## [2.1.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v2.0.0...v2.1.0) (2024-06-07)


### Features

* add pull request template ([#113](https://github.com/CloudNationHQ/terraform-azure-vm/issues/113)) ([12089c4](https://github.com/CloudNationHQ/terraform-azure-vm/commit/12089c4b76fd90c2ad62a29e68cc018a6b5f00b8))

## [2.0.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.13.0...v2.0.0) (2024-06-06)


### ⚠ BREAKING CHANGES

* Introduction of optional multiple IP configurations alters the data structure, making the change not backwards compatible

### Features

* **deps:** bump github.com/Azure/azure-sdk-for-go/sdk/azidentity ([#102](https://github.com/CloudNationHQ/terraform-azure-vm/issues/102)) ([637208c](https://github.com/CloudNationHQ/terraform-azure-vm/commit/637208cdd016de940b5f9c202d00711351e7b784))
* **deps:** bump github.com/hashicorp/go-getter in /tests ([#104](https://github.com/CloudNationHQ/terraform-azure-vm/issues/104)) ([d77904f](https://github.com/CloudNationHQ/terraform-azure-vm/commit/d77904fc33fbb062d4eb36702b8ba47a05500b11))
* **deps:** bump golang.org/x/net from 0.19.0 to 0.23.0 in /tests ([#103](https://github.com/CloudNationHQ/terraform-azure-vm/issues/103)) ([a2cc6e9](https://github.com/CloudNationHQ/terraform-azure-vm/commit/a2cc6e952e8ce87f5593a13e22bd2c7a780c9b9e))
* support multiple IP configurations per interface ([#111](https://github.com/CloudNationHQ/terraform-azure-vm/issues/111)) ([41373cd](https://github.com/CloudNationHQ/terraform-azure-vm/commit/41373cd8b64e1bfb79b333fc6f2ae34b8ee7aee8))

## [1.13.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.12.0...v1.13.0) (2024-04-10)


### Features

* add support for availability sets ([#100](https://github.com/CloudNationHQ/terraform-azure-vm/issues/100)) ([f03f280](https://github.com/CloudNationHQ/terraform-azure-vm/commit/f03f28075280e4e245c73ad0d8ac729b7c7da3bc))

## [1.12.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.11.0...v1.12.0) (2024-04-03)


### Features

* add lifecycle ignore encryption settings managed disks ([#98](https://github.com/CloudNationHQ/terraform-azure-vm/issues/98)) ([5efce4e](https://github.com/CloudNationHQ/terraform-azure-vm/commit/5efce4e9f69759890dd1e3d941161be1f96a29dd))
* update documentation ([#96](https://github.com/CloudNationHQ/terraform-azure-vm/issues/96)) ([cffc8f4](https://github.com/CloudNationHQ/terraform-azure-vm/commit/cffc8f4395a450a976746ddae6759004640ecff9))

## [1.11.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.10.0...v1.11.0) (2024-03-26)


### Features

* **deps:** bump github.com/gruntwork-io/terratest in /tests ([#93](https://github.com/CloudNationHQ/terraform-azure-vm/issues/93)) ([a082584](https://github.com/CloudNationHQ/terraform-azure-vm/commit/a0825847a35acc96bc22cca42593026759383f55))
* use virtual machine name as fallback when computer name is not specified ([#94](https://github.com/CloudNationHQ/terraform-azure-vm/issues/94)) ([c7b0639](https://github.com/CloudNationHQ/terraform-azure-vm/commit/c7b06396ea4f12ced36a04b73462d9e64cd31d19))

## [1.10.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.9.0...v1.10.0) (2024-03-22)


### Features

* allow OS disk name override ([#91](https://github.com/CloudNationHQ/terraform-azure-vm/issues/91)) ([931ff94](https://github.com/CloudNationHQ/terraform-azure-vm/commit/931ff9461d2984b34a4afba33345190a25846dbe))
* **deps:** bump google.golang.org/protobuf in /tests ([#90](https://github.com/CloudNationHQ/terraform-azure-vm/issues/90)) ([649e709](https://github.com/CloudNationHQ/terraform-azure-vm/commit/649e7092b5e41b9047b41d8473c2b8a55aefc59d))

## [1.9.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.8.0...v1.9.0) (2024-03-13)


### Features

* **deps:** bump github.com/stretchr/testify in /tests ([#87](https://github.com/CloudNationHQ/terraform-azure-vm/issues/87)) ([9216ff9](https://github.com/CloudNationHQ/terraform-azure-vm/commit/9216ff9a788c956deba155a830de4f58001b7184))


### Bug Fixes

* change key of instance output ([#88](https://github.com/CloudNationHQ/terraform-azure-vm/issues/88)) ([08763d5](https://github.com/CloudNationHQ/terraform-azure-vm/commit/08763d5df4d1dfbdb050571e2d8f3ca71b2df1dc))

## [1.8.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.7.0...v1.8.0) (2024-02-27)


### Features

* add conditional expression to allow global tagging and changed defaults max shares property on managed disks ([#84](https://github.com/CloudNationHQ/terraform-azure-vm/issues/84)) ([1cd0d76](https://github.com/CloudNationHQ/terraform-azure-vm/commit/1cd0d76dd8393838e195dbb48544b286d8f576a9))
* add user assigned identity output ([#86](https://github.com/CloudNationHQ/terraform-azure-vm/issues/86)) ([0b57df6](https://github.com/CloudNationHQ/terraform-azure-vm/commit/0b57df63f1bcd1c7d9229c6a09a53da96374fdb5))

## [1.7.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.6.1...v1.7.0) (2024-02-26)


### Features

* add missing tag property extensions ([#81](https://github.com/CloudNationHQ/terraform-azure-vm/issues/81)) ([2c5d5d7](https://github.com/CloudNationHQ/terraform-azure-vm/commit/2c5d5d72dafb8d851d34466814c5218d1396ad38))

## [1.6.1](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.6.0...v1.6.1) (2024-02-19)


### Bug Fixes

* fix typo storage account type defaults ([#79](https://github.com/CloudNationHQ/terraform-azure-vm/issues/79)) ([b2292a3](https://github.com/CloudNationHQ/terraform-azure-vm/commit/b2292a3c0a4211d90995500247295c75c9d14b6e))

## [1.6.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.5.1...v1.6.0) (2024-02-19)


### Features

* add auto upgrade version property extensions ([#77](https://github.com/CloudNationHQ/terraform-azure-vm/issues/77)) ([607ec49](https://github.com/CloudNationHQ/terraform-azure-vm/commit/607ec495e4fc3dc85faf6033c205de4859caf798))

## [1.5.1](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.5.0...v1.5.1) (2024-02-16)


### Bug Fixes

* fix defaults sku image offer ([#75](https://github.com/CloudNationHQ/terraform-azure-vm/issues/75)) ([be33a68](https://github.com/CloudNationHQ/terraform-azure-vm/commit/be33a680406f64944b5f92e0ff81db0f2d3150eb))

## [1.5.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.4.1...v1.5.0) (2024-02-16)


### Features

* improve boot diagnostic and additional capabilities blocks ([#73](https://github.com/CloudNationHQ/terraform-azure-vm/issues/73)) ([b33e96e](https://github.com/CloudNationHQ/terraform-azure-vm/commit/b33e96eb79d791d9d78b23488363a4a77f08ec54))

## [1.4.1](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.4.0...v1.4.1) (2024-02-15)


### Bug Fixes

* fix managed disk defaults ([#71](https://github.com/CloudNationHQ/terraform-azure-vm/issues/71)) ([d77b012](https://github.com/CloudNationHQ/terraform-azure-vm/commit/d77b012537b2271d83574131a941065511f35911))

## [1.4.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.3.0...v1.4.0) (2024-02-15)


### Features

* add missing properties managed disks ([#69](https://github.com/CloudNationHQ/terraform-azure-vm/issues/69)) ([16e2dd0](https://github.com/CloudNationHQ/terraform-azure-vm/commit/16e2dd00bcd56ca7ee4da4a79e6e4ff1218a5357))

## [1.3.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.2.1...v1.3.0) (2024-02-14)


### Features

* added option to use generated or external ssh key/password ([#67](https://github.com/CloudNationHQ/terraform-azure-vm/issues/67)) ([c7bb6a5](https://github.com/CloudNationHQ/terraform-azure-vm/commit/c7bb6a5ac839f861ace57bfa54451660abbbfd62))

## [1.2.1](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.2.0...v1.2.1) (2024-02-13)


### Bug Fixes

* make extensions optional again ([#64](https://github.com/CloudNationHQ/terraform-azure-vm/issues/64)) ([5924e82](https://github.com/CloudNationHQ/terraform-azure-vm/commit/5924e828c359f3ea5f6d1ca0cd927623543a6dfa))

## [1.2.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.1.1...v1.2.0) (2024-02-12)


### Features

* naming variable is optional now ([#62](https://github.com/CloudNationHQ/terraform-azure-vm/issues/62)) ([890875a](https://github.com/CloudNationHQ/terraform-azure-vm/commit/890875a2524fb3abb94372183a3ebb54f8713003))

## [1.1.1](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.1.0...v1.1.1) (2024-02-12)


### Bug Fixes

* refactored for each loop by using static keys in the extension resource to prevent unknown value issues ([#60](https://github.com/CloudNationHQ/terraform-azure-vm/issues/60)) ([f6de31c](https://github.com/CloudNationHQ/terraform-azure-vm/commit/f6de31c66ca182dcee165e825bb9abae1b20af6d))

## [1.1.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.0.2...v1.1.0) (2024-01-29)


### Features

* add some missing properties ([#56](https://github.com/CloudNationHQ/terraform-azure-vm/issues/56)) ([99c7448](https://github.com/CloudNationHQ/terraform-azure-vm/commit/99c7448f18ee117e792180651215052887972109))

## [1.0.2](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.0.1...v1.0.2) (2024-01-25)


### Bug Fixes

* separate tags of the nic from the instance ([#54](https://github.com/CloudNationHQ/terraform-azure-vm/issues/54)) ([935301d](https://github.com/CloudNationHQ/terraform-azure-vm/commit/935301d06b84c4622706a6661ee368388e4069a4))

## [1.0.1](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v1.0.0...v1.0.1) (2024-01-24)


### Bug Fixes

* make the disks property in data_disks optional again ([#51](https://github.com/CloudNationHQ/terraform-azure-vm/issues/51)) ([3652a21](https://github.com/CloudNationHQ/terraform-azure-vm/commit/3652a2198e7dec6a384736f0a524671f801e3240))

## [1.0.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v0.9.0...v1.0.0) (2024-01-23)


### ⚠ BREAKING CHANGES

* Enhancing reliability in import scenarios. This change will cause a recreate on existing resources.

### Features

* refined key value configurations for all resources ([#48](https://github.com/CloudNationHQ/terraform-azure-vm/issues/48)) ([fd56760](https://github.com/CloudNationHQ/terraform-azure-vm/commit/fd56760b41c0e7bca183c736caddab4b49768daa))

## [0.9.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v0.8.0...v0.9.0) (2024-01-23)


### Features

* add support for optional plan block ([#47](https://github.com/CloudNationHQ/terraform-azure-vm/issues/47)) ([4ab8f13](https://github.com/CloudNationHQ/terraform-azure-vm/commit/4ab8f13874954e253b203f92d088637c827b5b3a))
* added the ability to override ip config name network interfaces ([#42](https://github.com/CloudNationHQ/terraform-azure-vm/issues/42)) ([9247191](https://github.com/CloudNationHQ/terraform-azure-vm/commit/9247191e487fec57384bcfcc3ab123ada97456c5))
* **deps:** bump github.com/Azure/azure-sdk-for-go/sdk/azidentity ([#46](https://github.com/CloudNationHQ/terraform-azure-vm/issues/46)) ([14cf680](https://github.com/CloudNationHQ/terraform-azure-vm/commit/14cf680c0f97714e3f54add18a43709c180d08f2))
* **deps:** bump github.com/gruntwork-io/terratest in /tests ([#34](https://github.com/CloudNationHQ/terraform-azure-vm/issues/34)) ([a599f7c](https://github.com/CloudNationHQ/terraform-azure-vm/commit/a599f7c38c79cd02bcec2aabe9775a6a40eb2cb9))
* **deps:** bump github.com/gruntwork-io/terratest in /tests ([#45](https://github.com/CloudNationHQ/terraform-azure-vm/issues/45)) ([55c2eb4](https://github.com/CloudNationHQ/terraform-azure-vm/commit/55c2eb4e82db8bff5091ef6337e074d62fb7ac11))
* small refactor workflows ([#43](https://github.com/CloudNationHQ/terraform-azure-vm/issues/43)) ([a83f3b1](https://github.com/CloudNationHQ/terraform-azure-vm/commit/a83f3b1cf18c153aeadb4afa73af0df08bd04a16))

## [0.8.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v0.7.0...v0.8.0) (2024-01-08)


### Features

* add additional validation in variables ([#32](https://github.com/CloudNationHQ/terraform-azure-vm/issues/32)) ([05bc676](https://github.com/CloudNationHQ/terraform-azure-vm/commit/05bc676dc3bb1d5cd0831ab923dd28f082ac2f04))
* add support for additional user assigned identities ([#31](https://github.com/CloudNationHQ/terraform-azure-vm/issues/31)) ([769f6bc](https://github.com/CloudNationHQ/terraform-azure-vm/commit/769f6bc4c55f91a36491a5c85abb486d04f9c6c0))

## [0.7.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v0.6.0...v0.7.0) (2024-01-04)


### Features

* besided generating passwords or ssh keys within the module itself, it is also possible to use outputs from other modules as well ([#29](https://github.com/CloudNationHQ/terraform-azure-vm/issues/29)) ([753e054](https://github.com/CloudNationHQ/terraform-azure-vm/commit/753e05409b20aa6cee7ae3482268512e8ee2f71a))

## [0.6.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v0.5.0...v0.6.0) (2023-12-21)


### Features

* add optional computer name properties ([#26](https://github.com/CloudNationHQ/terraform-azure-vm/issues/26)) ([ce68bf2](https://github.com/CloudNationHQ/terraform-azure-vm/commit/ce68bf26f9fa5b7b0fa0286340d3df2a4ded81b1))
* **deps:** bump github.com/stretchr/testify in /tests ([#23](https://github.com/CloudNationHQ/terraform-azure-vm/issues/23)) ([bf87c88](https://github.com/CloudNationHQ/terraform-azure-vm/commit/bf87c8837196a6c729a489a3b7137bab9f34d0a3))
* **deps:** bump golang.org/x/crypto from 0.14.0 to 0.17.0 in /tests ([#24](https://github.com/CloudNationHQ/terraform-azure-vm/issues/24)) ([660cc62](https://github.com/CloudNationHQ/terraform-azure-vm/commit/660cc6249e1c45ac41b86a3a8f3f3ad021707401))
* **deps:** Bumps https://github.com/gruntwork-io/terratest from 0.46.7 to 0.46.8. ([be40ade](https://github.com/CloudNationHQ/terraform-azure-vm/commit/be40ade9963dce5080247c27c2c5da568b723a00))

## [0.5.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v0.4.0...v0.5.0) (2023-12-08)


### Features

* added an additional example demonstrating how to reference specific subnets in scenarios with multiple virtual machines ([#18](https://github.com/CloudNationHQ/terraform-azure-vm/issues/18)) ([f00c780](https://github.com/CloudNationHQ/terraform-azure-vm/commit/f00c78020909b8da52c10072a67cd9ca1733ed4a))

## [0.4.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v0.3.0...v0.4.0) (2023-12-07)


### Features

* add auto increments on lun id disks ([#15](https://github.com/CloudNationHQ/terraform-azure-vm/issues/15)) ([680e58e](https://github.com/CloudNationHQ/terraform-azure-vm/commit/680e58e3b747c8d7d6df1e565dd79cdf7c17d0bb))

## [0.3.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v0.2.0...v0.3.0) (2023-12-06)


### Features

* add extended tests ([#11](https://github.com/CloudNationHQ/terraform-azure-vm/issues/11)) ([ea913f2](https://github.com/CloudNationHQ/terraform-azure-vm/commit/ea913f24b9eeff99990e464d238d2cefa5d97e3a))

## [0.2.0](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v0.1.1...v0.2.0) (2023-12-05)


### Features

* add custom data example ([#10](https://github.com/CloudNationHQ/terraform-azure-vm/issues/10)) ([aefd0ea](https://github.com/CloudNationHQ/terraform-azure-vm/commit/aefd0ea2271b9f32f7398fe65f1faf6607ec3521))
* add some missing properties ([#9](https://github.com/CloudNationHQ/terraform-azure-vm/issues/9)) ([0918a83](https://github.com/CloudNationHQ/terraform-azure-vm/commit/0918a83995c99b0ed25fa2207e6c6188f4a8b34e))
* change default windows image sku ([#7](https://github.com/CloudNationHQ/terraform-azure-vm/issues/7)) ([5930e49](https://github.com/CloudNationHQ/terraform-azure-vm/commit/5930e49e8803952afffd8f07bb5d2b22099b2e77))

## [0.1.1](https://github.com/CloudNationHQ/terraform-azure-vm/compare/v0.1.0...v0.1.1) (2023-11-27)


### Bug Fixes

* added managed identity ([#3](https://github.com/CloudNationHQ/terraform-azure-vm/issues/3)) ([d11f38f](https://github.com/CloudNationHQ/terraform-azure-vm/commit/d11f38f7951daabf313a4abb5839005f4da3b54d))

## 0.1.0 (2023-11-24)


### Features

* add initial resources ([#1](https://github.com/CloudNationHQ/terraform-azure-vm/issues/1)) ([137fde0](https://github.com/CloudNationHQ/terraform-azure-vm/commit/137fde0bace1c6246c52bc6aa5220ce1f77a0235))
