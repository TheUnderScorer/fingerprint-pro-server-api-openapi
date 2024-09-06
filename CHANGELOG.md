# [1.1.0](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/compare/v1.0.0...v1.1.0) (2024-08-09)

## 1.9.1

### Patch Changes

- a0528a8: Patch change test

## 1.9.0

### Minor Changes

- f9e1796: Another minor change

## 1.8.0

### Minor Changes

- 1a1dd15: Minor change

## 1.7.0

### Minor Changes

- 3d4b588: Minor change

## 1.6.0

### Minor Changes

- b61d81b: Minor chanfge

## 1.5.0

### Minor Changes

- 70b2d8f: Test minor change

## 1.4.4

### Patch Changes

- 01472ea: Patch change

## 1.4.3

### Patch Changes

- 07c164d: **visitors**: Test patch

## 1.4.2

### Patch Changes

- 95e00bf: **events**: Test patch

## 1.4.1

### Patch Changes

- 3cc8d71: **events**: Test patch change

## 1.4.0

### Minor Changes

- b624765: **visitors**: Test minor

## 1.3.0

### Minor Changes

- f98272c: **webhook**: Minor change

## 1.2.0

### Minor Changes

- 991a552: **events**: Test minor change

### Features

- make `tag` field optional for webhook ([b9b3efa](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/b9b3efadd98eb86fcdba2b63cb4bef3f8276873f))
- test release ([d41b2cd](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/d41b2cd4a672552745049bff18ce5598a62c3654))

# 1.0.0 (2024-08-09)

### Bug Fixes

- add favicon link ([7220acb](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/7220acb581fc69f7cdf54df2672c95810544d30e))
- add missed `additionalProperties: false`, remove outdated comments ([618cbc1](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/618cbc1736f1ce345e308cc6682ca85a8fd200ba))
- add missed `in` value for `paginationKey` ([872af0e](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/872af0e67d8920adfde79ff8e7d3d05444e0a817))
- add sample languages ([d3ac47e](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/d3ac47ef8d3ca9a479446400e9fe41b4c75ff421))
- add sample languages ([8e89e1d](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/8e89e1deab86360508dc0754676b278a98cf665e))
- add sample languages ([e059d41](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/e059d4168cf4188a5b1d2db283ee4c809070cc47))
- add title field property to some of the fields ([5ba0ecc](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/5ba0ecc3b0a47f800bb43b3d85e79080ed1f18a2))
- add visits 403 error example, ([228dc99](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/228dc995fa5fb717076502c90e1269c130c3194b))
- allow `Visit` and `BotdResult` to be extended ([f04edf4](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/f04edf42f9670e0ec3a1199b1af8acbe49111ef8))
- allow url format for `BotdResult` to be empty string ([27b4598](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/27b4598bff0393415d2b97f31222e3474381d328))
- clarify mobile signals availability ([c785417](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/c7854171179e2daa21a95913531ac34c01c88e73))
- deprecate `IPLocation` field ([6bc2ec2](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/6bc2ec29e8d26b43b5df725781b2cd54ff35b2c0))
- don't deprecate `geolocation` field for the `IpInfoResult` signal ([de7e0de](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/de7e0de70fb19b5c1931eefdffb985dcbd7be54b))
- error reporting for validation ([b7fb327](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/b7fb32727b4944877e3b01e2cf2c89bc44422b2e))
- extra fields mock ([2ad70bc](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/2ad70bcc7790a47c789a0141cba2b09755c8363a))
- fix dependabot checks ([00e02b9](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/00e02b96e65e073a6bf90afc130e303cfce4f01c))
- fix description for visits and events endpoints ([87a9517](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/87a9517a50fb886c75b7a5669de474512b6df120))
- fix errors in schema found during validation ([e0f2ff3](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/e0f2ff3739a6209d9d3544c969886d83e1ca60c8))
- fix schema errors and warnings ([5c4dddd](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/5c4dddd7bacbe90cc561d6a64b8342560ecd252f))
- fix visits 429 error example ([579d126](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/579d1266eb82401b6393216691e52c188ad47fee))
- generate correct exit code ([bffb12d](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/bffb12d68a4bd05ffb69dff1619b64dd5edf096f))
- groom schema after review ([4460908](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/446090857ae8aaf0c4110545f06cc5856e818eab))
- improve signals name in webhooks to not repeat models names ([50930fa](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/50930fac347d16d52b3471bf6f1d6ea7d9430028))
- mark fields as required where it was missed before ([ef7f5f9](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/ef7f5f9d7d53294497081e426e7b4cda0421b4af))
- rawDeviceAttributes error example for getEvent ([2b71725](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/2b71725127e061a914558110406585083ab3cb85))
- remove transformer ([0c30b93](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/0c30b936e061e65ae380557eb2618f3cfd4103bb))
- revert custom plugin for externalValue because it didn't work ([075b183](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/075b1833119d037847d3bbc70fceed5eaae2c34e))
- revert flexibility from the `ProductsResponse`. SDK shouldn't fail with any new fields in schema. ([f9d7ef9](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/f9d7ef919adc81b60d7ce630dac0de91e8c165c2))
- sample languages order ([c1e36a1](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/c1e36a12889452c8ca0c584f6d651b6d60a633a8))
- schema and schema examples ([#85](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/issues/85)) ([df04f62](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/df04f62fb8d42fdf5f3f51c6493727364f1d16a5))
- **SCHEMA:** change before param format to int64 ([2f5755d](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/2f5755df6fad218f58c550a69c9ef3cada158116))
- Set correct $ref for objects ([b17f4f8](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/b17f4f8ee2ca9689d4ac34097a948967895f9b83))
- set up `additionalProperties` for `BotdResult` and `Visit` as a default ([fd8de4d](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/fd8de4d0185a7ed63fa5bdc9b7c52e48a78bfc26))
- simplify raw attributes union to fix problems in typed languages ([7c653a6](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/7c653a636a49923f8d19b42d3ce75abf7b9f235b))
- structures names conflict ([#86](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/issues/86)) ([51734e4](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/51734e4d4b056aae5cd3c1733498e8b7f7584f88))
- StSeenAt global is nullable ([e24fae5](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/e24fae532a13063b8056ff9b865180103c9fed2a))
- update 403 response for visitors method ([c020bc1](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/c020bc1c5c84299af032c3f591837e64c175dd27))
- url format ([57533d6](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/57533d6cf7e470e9ca4a6dfadb42ae7c6524af74))
- use IdentificationError for smart signals that come from identification backend ([35cf823](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/35cf8231c4a0349dbd7d9aa0bcfb708042d443de))

### Features

- add /events/:request_id endpoint schema ([a8ab91d](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/a8ab91d4e79effbdb9cc17d50308a1a00d351fc5))
- add `additionalProperties: false` for all objects to improve schema verification ([69e35ff](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/69e35ff3a248f3281f7eb2194217b2dcb911eb28))
- add `url` field to the BotdResult, closes [#19](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/issues/19) ([9ae244b](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/9ae244b71be9ea03e4fba922541b46cbbddf7b53))
- add compact schema without examples and x-readme ([47bfeb4](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/47bfeb43897c90db918bd670ce8611f5c8e03b21))
- add contact info ([3827473](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/382747309ab3f23d75896f8b87dbfb0575ea1883))
- add demo api key support ([91a51b4](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/91a51b4ef45711a8f701a60aeff0b5d4735b216d))
- add error examples for new smart signals ([3004411](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/3004411976fcf1e09b24ffb3a4f19eb6b9c06423))
- add external examples and some webpack code for them, add tests ([c9c8808](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/c9c8808505fc1f8811c996e5b0fee9fc15ba466b))
- add favicon ([d2898d6](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/d2898d6c3dfe6657c247bc5bc83b30ad27833c3e))
- add more mock responses ([a72c0fd](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/a72c0fd6752b5fb0f8f98346c6eb8da7ab8dbeb6))
- add schema validation by schedule ([7ed047a](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/7ed047a21b9cd1a61e7834d4775c1709a15389fa))
- add schema validation with real data ([455ea1c](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/455ea1cbf7e29444aea63867bbe495d33d5674d7))
- add types for webhook ([4eb9cf1](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/4eb9cf1ac5e8c1f969b1f65d3521314109549d4a))
- add validation with real requests, fix schema after validation ([45dac54](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/45dac54de9f4b4406391bb1456557eca35249b90))
- allow new products for `events` method ([aea7561](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/aea756184582604d133d324c0840de1d564ed5b6))
- describe jailbroken, frida, factoryReset, clonedApp, vm ([#56](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/issues/56)) ([63ec720](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/63ec720f4604e7eb2592aed80ecf6850f2ebc99a))
- describe more signals in the schema ([30293e9](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/30293e94eaefc95ac645a8d6a5d72860db5b4462))
- describe raw device attributes smart signal ([a793a39](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/a793a39de16a1af94518bba6abaabccbe5b9a151))
- describe rawDeviceAttributes structure ([9779ac3](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/9779ac3e52c50e609662d650f2d194c35489e854))
- fix schema, add additional fields for correct code generation ([807ebf3](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/807ebf305061b5cc82cb7708f382ea93745ed27c))
- introduce `datacenter` field for the `IpInfo` signal in addition to the wrong `dataCenter` ([bd9fc46](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/bd9fc46a61c990d853617db4d49c56a671bb7dce))
- keep only one `datacenter` field for the `IpInfo` signal ([27e40bc](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/27e40bc9c3ee120dc46079821d11db338cf53547))
- make `body` required for the `updateEvent` method ([2304560](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/230456076dd2b99106b4b1730dd4b2db891ff047))
- make `IPLocation` and all its fields not required ([e246496](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/e24649662f7a527c8a1e318910891be1ad43f051))
- make `tag` field optional for webhook ([b9b3efa](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/b9b3efadd98eb86fcdba2b63cb4bef3f8276873f))
- make rawDeviceAttributes structure generic ([6f0ee02](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/6f0ee02b88236e0f5baacdb2bf69639d8a264d84))
- publish examples to gh-pages ([8fa0b21](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/8fa0b218419efce7e89b0ffff3f85b7a8cc93d81))
- rename ManyRequestsResponse to TooManyRequestsResponse ([63071ee](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/63071eeb789e6ac58db48a2263331448cd33a144))
- rename type `StSeenAt` to `SeenAt` [#26](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/issues/26) ([73f623c](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/73f623c1a6e3ec1d90db55c125c376689004188e))
- simplify schema structure for better codegeneration ([876bed0](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/876bed02230a86ea3724a810f0ac7644f541a240))
- type RawAttributes error my precisely ([74901c6](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/74901c6b667e00293d241cfb562734c7d2659f19))
- update examples ([7af74f7](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/7af74f7a38f2df19bedbf7eca4d430947d705761))
- update schema according new errors reporting ([0780bff](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/0780bffde2638c35ffc1e87982570521efa72ad7))
- use ts-loader for ts ([0eb94f3](https://github.com/theunderscorer/fingerprint-pro-server-api-openapi/commit/0eb94f312e66119a4c20ce33e84907fd3c593002))
