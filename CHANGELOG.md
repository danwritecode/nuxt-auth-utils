# Changelog

## 0.0.26 (2024-05-31)


### Features

* add `redirectUrl` to OAuthMicrosoftConfig for HTTP vs HTTPS Handling ([50ba6fe](https://github.com/Atinux/nuxt-auth-utils/commit/50ba6fe5b59a04b2375a68dc427948aa5df5a6ae))
* add auth0 connection parameter to config ([#39](https://github.com/Atinux/nuxt-auth-utils/issues/39)) ([2ea2ba8](https://github.com/Atinux/nuxt-auth-utils/commit/2ea2ba856a315f32df040ac0e3ad9625add6e62f))
* add authorizationParams in oauth config ([#56](https://github.com/Atinux/nuxt-auth-utils/issues/56)) ([5c79590](https://github.com/Atinux/nuxt-auth-utils/commit/5c7959032b8cbb54264636d079d3e91c3bda23d8))
* add facebook OAuth provider ([777d8b2](https://github.com/Atinux/nuxt-auth-utils/commit/777d8b26285ace142633b72f0423cd3eb6d5d005))
* add fields support to facebook provider ([8e53936](https://github.com/Atinux/nuxt-auth-utils/commit/8e5393608405fd019d9067e0bc6046c72f2cd4af))
* add max_age param for auth0 ([#26](https://github.com/Atinux/nuxt-auth-utils/issues/26)) ([e7a0dbd](https://github.com/Atinux/nuxt-auth-utils/commit/e7a0dbd3dd897b2a62a011df795c89fb9171b965))
* add opts to requireUserSession for error message and status code customization ([015e847](https://github.com/Atinux/nuxt-auth-utils/commit/015e847f0dfe885fc82515985338a7306d62a07f))
* add replaceUserSession() ([#44](https://github.com/Atinux/nuxt-auth-utils/issues/44)) ([e74f238](https://github.com/Atinux/nuxt-auth-utils/commit/e74f238d5e16fccbfae4b4d3639a7ed45c9ce3e1))
* add sessionHooks to extend user sessions ([c470319](https://github.com/Atinux/nuxt-auth-utils/commit/c4703199c41e46093b89d0dcec1818cb1ddf6f3c))
* added auth0 as oauth provider ([#6](https://github.com/Atinux/nuxt-auth-utils/issues/6)) ([ffecb82](https://github.com/Atinux/nuxt-auth-utils/commit/ffecb82cf4ce876f529a204e470f2cd4e14d63ae))
* added aws cognito provider ([#36](https://github.com/Atinux/nuxt-auth-utils/issues/36)) ([4b67d6c](https://github.com/Atinux/nuxt-auth-utils/commit/4b67d6cc5b3cb59f816da126d9b55e67380f0329))
* added discord auth provider ([#7](https://github.com/Atinux/nuxt-auth-utils/issues/7)) ([ba78a8b](https://github.com/Atinux/nuxt-auth-utils/commit/ba78a8b9fea8077051414f272417d52cd4b76e6d))
* added google as oauth provider ([#3](https://github.com/Atinux/nuxt-auth-utils/issues/3)) ([af4e2d1](https://github.com/Atinux/nuxt-auth-utils/commit/af4e2d14cd32c1e33b1f9243be3ea1135dca95c2))
* added keycloak as oauth provider ([#23](https://github.com/Atinux/nuxt-auth-utils/issues/23)) ([10398a6](https://github.com/Atinux/nuxt-auth-utils/commit/10398a61986df2919df38e9d37cfbb7ae991dd32))
* added linkedIn auth provider ([#13](https://github.com/Atinux/nuxt-auth-utils/issues/13)) ([2c9252d](https://github.com/Atinux/nuxt-auth-utils/commit/2c9252d2e64735bba41e0af6ef372e0596beb16a))
* added Microsoft as oauth provider ([#8](https://github.com/Atinux/nuxt-auth-utils/issues/8)) ([2fb01d3](https://github.com/Atinux/nuxt-auth-utils/commit/2fb01d3cfcb5a63b527e6138e68611c3e8c94820))
* added oauth battle.net ([#11](https://github.com/Atinux/nuxt-auth-utils/issues/11)) ([b6cdec5](https://github.com/Atinux/nuxt-auth-utils/commit/b6cdec581204d7e99f0d53394840e1db708ef1e4)), closes [#7](https://github.com/Atinux/nuxt-auth-utils/issues/7)
* added twitch as supported oauth provider ([#5](https://github.com/Atinux/nuxt-auth-utils/issues/5)) ([ec17cb2](https://github.com/Atinux/nuxt-auth-utils/commit/ec17cb231a356ce1231c57a1f15e34d7792f24e4))
* allow users to define custom session factory + types ([#2](https://github.com/Atinux/nuxt-auth-utils/issues/2)) ([15764a7](https://github.com/Atinux/nuxt-auth-utils/commit/15764a72452d3b51c35bac1f57c1482aec49dbe2))
* generate NUXT_SESSION_PASSWORD and throw if not set in production ([de890ed](https://github.com/Atinux/nuxt-auth-utils/commit/de890ed2239a39beeeda55d9a761f3b43acf749f))
* refactor login buttons to use dropdown ([#14](https://github.com/Atinux/nuxt-auth-utils/issues/14)) ([76357c6](https://github.com/Atinux/nuxt-auth-utils/commit/76357c6d07ddc012a32c915e068307b348d98f42))


### Bug Fixes

* add audience to auth0 runtime config types ([#27](https://github.com/Atinux/nuxt-auth-utils/issues/27)) ([f6f8ae6](https://github.com/Atinux/nuxt-auth-utils/commit/f6f8ae646f026e40eefac5c5b2ef16bced2f69f7))
* avoid duplicate trigger of session fetch hook due to request retry ([5fac9a1](https://github.com/Atinux/nuxt-auth-utils/commit/5fac9a10456dffa64cdd8159baf31fa26e1a488a))
* avoid infinite loop with latest Nuxt ([93b949d](https://github.com/Atinux/nuxt-auth-utils/commit/93b949defec0e61a2788fbc3996e6280e8dbe8e9))
* correct arguments for hooks ([6e0193e](https://github.com/Atinux/nuxt-auth-utils/commit/6e0193e9e593c41b1c55942d07f587a6201148dc))
* don't log warning about password when preparing types ([804057b](https://github.com/Atinux/nuxt-auth-utils/commit/804057b1026db522899c929d7604e45df227c0da))
* **google:** remove `redirectUrl` type ([#52](https://github.com/Atinux/nuxt-auth-utils/issues/52)) ([cad99b0](https://github.com/Atinux/nuxt-auth-utils/commit/cad99b01f7a6ef4bed568eeff4932297b8838ec8))
* import useRuntimeConfig ([bdbb4b8](https://github.com/Atinux/nuxt-auth-utils/commit/bdbb4b815751ebb7f7b31dca20c15290cff89f1e))
* leverage NUXT_SESSION_PASSWORD provided at runtime ([4932959](https://github.com/Atinux/nuxt-auth-utils/commit/49329590ff4a9e6398a5ddb2467f4996fcdada60))
* leverage runtimeConfig to check password ([7c23543](https://github.com/Atinux/nuxt-auth-utils/commit/7c235439b6467d58ad9e983e97e583c7bca87c95))
* **oauth:** add generic OAuthConfig type ([#18](https://github.com/Atinux/nuxt-auth-utils/issues/18)) ([5b060b8](https://github.com/Atinux/nuxt-auth-utils/commit/5b060b879187ea95bdabcae5ded55f568674fec3))
* replace encoded space characters with regular spaces ([#40](https://github.com/Atinux/nuxt-auth-utils/issues/40)) ([e1f33fa](https://github.com/Atinux/nuxt-auth-utils/commit/e1f33fab845f62dba796b376eda8bb21349e57a8))
* **types:** narrowed session type passed to fetch session hook ([77c82e7](https://github.com/Atinux/nuxt-auth-utils/commit/77c82e7f063acbd000efc885c57a7f397f82ac7c))
* use import presets ([f16ebc9](https://github.com/Atinux/nuxt-auth-utils/commit/f16ebc93df9bfe811b04102d2e1b062e98f2b064)), closes [#1](https://github.com/Atinux/nuxt-auth-utils/issues/1)
* user session types ([#55](https://github.com/Atinux/nuxt-auth-utils/issues/55)) ([6a6043a](https://github.com/Atinux/nuxt-auth-utils/commit/6a6043aeb21397b9e5f0b1d7b7b75671557e7753))
* UserSession user type augmentation ([#54](https://github.com/Atinux/nuxt-auth-utils/issues/54)) ([1b99533](https://github.com/Atinux/nuxt-auth-utils/commit/1b99533c494ae12e22ec86c6aba6e8850054ae1e))
* workaround for addServerImportsDir not working ([5a189df](https://github.com/Atinux/nuxt-auth-utils/commit/5a189df115c03a22e9e7c6b67500d0a28cb0e734))

## v0.0.25

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.24...v0.0.25)

### 🚀 Enhancements

- Add fields support to facebook provider ([8e53936](https://github.com/Atinux/nuxt-auth-utils/commit/8e53936))

### 🏡 Chore

- Update to latest `@nuxt/module-builder` ([c9e4ff7](https://github.com/Atinux/nuxt-auth-utils/commit/c9e4ff7))

### ❤️ Contributors

- Ozan Cakir ([@ozancakir](http://github.com/ozancakir))
- Daniel Roe ([@danielroe](http://github.com/danielroe))

## v0.0.24

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.23...v0.0.24)

### 🚀 Enhancements

- Add facebook OAuth provider ([777d8b2](https://github.com/Atinux/nuxt-auth-utils/commit/777d8b2))

### 🏡 Chore

- Update deps ([3e42be4](https://github.com/Atinux/nuxt-auth-utils/commit/3e42be4))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- Adam Hudák ([@adam-hudak](http://github.com/adam-hudak))

## v0.0.23

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.22...v0.0.23)

### 🚀 Enhancements

- Add opts to requireUserSession for error message and status code customization ([015e847](https://github.com/Atinux/nuxt-auth-utils/commit/015e847))

### 🩹 Fixes

- Avoid duplicate trigger of session fetch hook due to request retry ([5fac9a1](https://github.com/Atinux/nuxt-auth-utils/commit/5fac9a1))

### 📖 Documentation

- Removed reference to /api in readme ([#77](https://github.com/Atinux/nuxt-auth-utils/pull/77))

### 🏡 Chore

- Migrate to eslint v9 ([964b67b](https://github.com/Atinux/nuxt-auth-utils/commit/964b67b))
- Update deps ([a77a334](https://github.com/Atinux/nuxt-auth-utils/commit/a77a334))
- Add vscode settings for eslint ([4f1afc9](https://github.com/Atinux/nuxt-auth-utils/commit/4f1afc9))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- Deth <gabriel@rosa.dev.br>
- Conrawl Rogers <diizzayy@gmail.com>
- Daniel Roe ([@danielroe](http://github.com/danielroe))
- Max ([@onmax](http://github.com/onmax))

## v0.0.22

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.21...v0.0.22)

### 🚀 Enhancements

- Add `redirectUrl` to OAuthMicrosoftConfig for HTTP vs HTTPS Handling ([50ba6fe](https://github.com/Atinux/nuxt-auth-utils/commit/50ba6fe))

### 🩹 Fixes

- **types:** Narrowed session type passed to fetch session hook ([77c82e7](https://github.com/Atinux/nuxt-auth-utils/commit/77c82e7))

### 📖 Documentation

- Use new nuxi module add command in installation ([d64b9d3](https://github.com/Atinux/nuxt-auth-utils/commit/d64b9d3))
- Improve readme ([00c8287](https://github.com/Atinux/nuxt-auth-utils/commit/00c8287))

### ❤️ Contributors

- Gerben Mulder <github.undergo381@passmail.net>
- André Agro Ferreira ([@andreagroferreira](http://github.com/andreagroferreira))
- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- Daniel Roe ([@danielroe](http://github.com/danielroe))

## v0.0.21

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.20...v0.0.21)

### 🏡 Chore

- Update deps ([c8b8eb9](https://github.com/Atinux/nuxt-auth-utils/commit/c8b8eb9))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.20

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.19...v0.0.20)

### 🩹 Fixes

- Leverage NUXT_SESSION_PASSWORD provided at runtime ([4932959](https://github.com/Atinux/nuxt-auth-utils/commit/4932959))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.19

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.18...v0.0.19)

### 🚀 Enhancements

- Generate NUXT_SESSION_PASSWORD and throw if not set in production ([de890ed](https://github.com/Atinux/nuxt-auth-utils/commit/de890ed))

### 🩹 Fixes

- Leverage runtimeConfig to check password ([7c23543](https://github.com/Atinux/nuxt-auth-utils/commit/7c23543))

### 🏡 Chore

- Fix types ([34dfb7b](https://github.com/Atinux/nuxt-auth-utils/commit/34dfb7b))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.18

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.16...v0.0.18)

### 🚀 Enhancements

- Add authorizationParams in oauth config ([#56](https://github.com/Atinux/nuxt-auth-utils/pull/56))

### 🩹 Fixes

- UserSession user type augmentation ([#54](https://github.com/Atinux/nuxt-auth-utils/pull/54))
- User session types ([#55](https://github.com/Atinux/nuxt-auth-utils/pull/55))

### 📖 Documentation

- Update badge colors ([ff868a6](https://github.com/Atinux/nuxt-auth-utils/commit/ff868a6))

### 🏡 Chore

- Update deps ([fdaa88c](https://github.com/Atinux/nuxt-auth-utils/commit/fdaa88c))
- Add api test route ([9aed7fe](https://github.com/Atinux/nuxt-auth-utils/commit/9aed7fe))
- Update deps in playground ([95c657f](https://github.com/Atinux/nuxt-auth-utils/commit/95c657f))
- **release:** V0.0.17 ([a814b58](https://github.com/Atinux/nuxt-auth-utils/commit/a814b58))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- Gerben Mulder ([@Gerbuuun](http://github.com/Gerbuuun))

## v0.0.17

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.16...v0.0.17)

### 🩹 Fixes

- UserSession user type augmentation ([#54](https://github.com/Atinux/nuxt-auth-utils/pull/54))

### 🏡 Chore

- Update deps ([fdaa88c](https://github.com/Atinux/nuxt-auth-utils/commit/fdaa88c))
- Add api test route ([9aed7fe](https://github.com/Atinux/nuxt-auth-utils/commit/9aed7fe))
- Update deps in playground ([95c657f](https://github.com/Atinux/nuxt-auth-utils/commit/95c657f))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- Gerben Mulder ([@Gerbuuun](http://github.com/Gerbuuun))

## v0.0.16

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.15...v0.0.16)

### 🚀 Enhancements

- Add replaceUserSession() ([#44](https://github.com/Atinux/nuxt-auth-utils/pull/44))

### 🩹 Fixes

- **google:** Remove `redirectUrl` type ([#52](https://github.com/Atinux/nuxt-auth-utils/pull/52))

### 🏡 Chore

- Better server types ([#51](https://github.com/Atinux/nuxt-auth-utils/pull/51))
- Update deps ([b930118](https://github.com/Atinux/nuxt-auth-utils/commit/b930118))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- Maximilian Götz-Mikus ([@maximilianmikus](http://github.com/maximilianmikus))
- Harlan Wilton ([@harlan-zw](http://github.com/harlan-zw))

## v0.0.15

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.14...v0.0.15)

### 🚀 Enhancements

- Add auth0 connection parameter to config ([#39](https://github.com/Atinux/nuxt-auth-utils/pull/39))
- Added aws cognito provider ([#36](https://github.com/Atinux/nuxt-auth-utils/pull/36))

### 🩹 Fixes

- Replace encoded space characters with regular spaces ([#40](https://github.com/Atinux/nuxt-auth-utils/pull/40))

### 🏡 Chore

- Up deps ([a7bd06b](https://github.com/Atinux/nuxt-auth-utils/commit/a7bd06b))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- Dvir Hazout <dvir@dazz.io>
- Silvio Eckl <silvio@whitespace.no>
- Ahmed Rangel ([@ahmedrangel](http://github.com/ahmedrangel))

## v0.0.14

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.13...v0.0.14)

### 🚀 Enhancements

- Added keycloak as oauth provider ([#23](https://github.com/Atinux/nuxt-auth-utils/pull/23))

### 🏡 Chore

- Test bundler module resolution ([#32](https://github.com/Atinux/nuxt-auth-utils/pull/32))
- Update deps ([9d6b258](https://github.com/Atinux/nuxt-auth-utils/commit/9d6b258))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- Yue JIN 
- Daniel Roe <daniel@roe.dev>

## v0.0.13

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.12...v0.0.13)

### 🏡 Chore

- Rename session from verify to fetch ([10694e9](https://github.com/Atinux/nuxt-auth-utils/commit/10694e9))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.12

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.11...v0.0.12)

### 🩹 Fixes

- Correct arguments for hooks ([6e0193e](https://github.com/Atinux/nuxt-auth-utils/commit/6e0193e))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.11

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.10...v0.0.11)

### 🚀 Enhancements

- Add sessionHooks to extend user sessions ([c470319](https://github.com/Atinux/nuxt-auth-utils/commit/c470319))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.10

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.9...v0.0.10)

### 🚀 Enhancements

- Added linkedIn auth provider ([#13](https://github.com/Atinux/nuxt-auth-utils/pull/13))

### 🩹 Fixes

- Add audience to auth0 runtime config types ([#27](https://github.com/Atinux/nuxt-auth-utils/pull/27))

### 📖 Documentation

- Add LinkedIn in providers ([c9b9925](https://github.com/Atinux/nuxt-auth-utils/commit/c9b9925))

### 🏡 Chore

- Update deps ([bb3a510](https://github.com/Atinux/nuxt-auth-utils/commit/bb3a510))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- José Manuel Madriaza Caravia 
- H+ <serdar@justserdar.dev>

## v0.0.9

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.8...v0.0.9)

### 🚀 Enhancements

- Add max_age param for auth0 ([#26](https://github.com/Atinux/nuxt-auth-utils/pull/26))
- Added Microsoft as oauth provider ([#8](https://github.com/Atinux/nuxt-auth-utils/pull/8))

### ❤️ Contributors

- Jakub Frelik <j.frelik.it@outlook.com>
- Uģis ([@BerzinsU](http://github.com/BerzinsU))

## v0.0.8

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.7...v0.0.8)

### 🩹 Fixes

- Avoid infinite loop with latest Nuxt ([93b949d](https://github.com/Atinux/nuxt-auth-utils/commit/93b949d))

### 🏡 Chore

- **playground:** Better with right title ([97a3ad3](https://github.com/Atinux/nuxt-auth-utils/commit/97a3ad3))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.7

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.6...v0.0.7)

### 🩹 Fixes

- **oauth:** Add generic OAuthConfig type ([#18](https://github.com/Atinux/nuxt-auth-utils/pull/18))

### 📖 Documentation

- Use consistent reference to module ([13daa78](https://github.com/Atinux/nuxt-auth-utils/commit/13daa78))

### 🏡 Chore

- Add SameSite=lax ([1b296e2](https://github.com/Atinux/nuxt-auth-utils/commit/1b296e2))

### ❤️ Contributors

- Sigve Hansen ([@sifferhans](http://github.com/sifferhans))
- Daniel Roe <daniel@roe.dev>
- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.6

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.5...v0.0.6)

### 🚀 Enhancements

- Added discord auth provider ([#7](https://github.com/Atinux/nuxt-auth-utils/pull/7))
- Added oauth battle.net ([#11](https://github.com/Atinux/nuxt-auth-utils/pull/11))
- Refactor login buttons to use dropdown ([#14](https://github.com/Atinux/nuxt-auth-utils/pull/14))

### 🏡 Chore

- Update deps ([05f4a9c](https://github.com/Atinux/nuxt-auth-utils/commit/05f4a9c))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- Arash 
- Samuel LEFEVRE 
- H+ <serdar@darweb.nl>

## v0.0.5

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.4...v0.0.5)

### 🚀 Enhancements

- Added google as oauth provider ([#3](https://github.com/Atinux/nuxt-auth-utils/pull/3))
- Added twitch as supported oauth provider ([#5](https://github.com/Atinux/nuxt-auth-utils/pull/5))
- Added auth0 as oauth provider ([#6](https://github.com/Atinux/nuxt-auth-utils/pull/6))

### 💅 Refactors

- Use `useSession` generic rather than assertion ([#4](https://github.com/Atinux/nuxt-auth-utils/pull/4))

### 📖 Documentation

- Add demo ([cbc8b7a](https://github.com/Atinux/nuxt-auth-utils/commit/cbc8b7a))

### 🏡 Chore

- **release:** V0.0.4 ([2bc6f9a](https://github.com/Atinux/nuxt-auth-utils/commit/2bc6f9a))

### ❤️ Contributors

- Antoine Lassier <toinousp@gmail.com>
- Gerben Mulder ([@Gerbuuun](http://github.com/Gerbuuun))
- Ahmed Rangel ([@ahmedrangel](http://github.com/ahmedrangel))
- Akshara Hegde <akshara.dt@gmail.com>
- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- Daniel Roe ([@danielroe](http://github.com/danielroe))

## v0.0.4

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.3...v0.0.4)

### 🩹 Fixes

- Use import presets ([f16ebc9](https://github.com/Atinux/nuxt-auth-utils/commit/f16ebc9))

### 🏡 Chore

- **release:** V0.0.3 ([9d1342c](https://github.com/Atinux/nuxt-auth-utils/commit/9d1342c))
- Add comment ([1923dcc](https://github.com/Atinux/nuxt-auth-utils/commit/1923dcc))

### ❤️ Contributors

- Daniel Roe ([@danielroe](http://github.com/danielroe))
- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.3

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.2...v0.0.3)

### 🚀 Enhancements

- Allow users to define custom session factory + types ([#2](https://github.com/Atinux/nuxt-auth-utils/pull/2))

### 🩹 Fixes

- Don't log warning about password when preparing types ([804057b](https://github.com/Atinux/nuxt-auth-utils/commit/804057b))
- Import useRuntimeConfig ([bdbb4b8](https://github.com/Atinux/nuxt-auth-utils/commit/bdbb4b8))

### 🏡 Chore

- Remove `.nuxtrc` ([3f96e97](https://github.com/Atinux/nuxt-auth-utils/commit/3f96e97))
- Add type testing script ([e9ffa5e](https://github.com/Atinux/nuxt-auth-utils/commit/e9ffa5e))
- Move playground into workspace ([bd8108c](https://github.com/Atinux/nuxt-auth-utils/commit/bd8108c))
- Add playground type test ([74f452c](https://github.com/Atinux/nuxt-auth-utils/commit/74f452c))

### 🤖 CI

- Run lint + test actions in ci ([f50c1b5](https://github.com/Atinux/nuxt-auth-utils/commit/f50c1b5))

### ❤️ Contributors

- Daniel Roe ([@danielroe](http://github.com/danielroe))
- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.2

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.1...v0.0.2)

## v0.0.1


### 🩹 Fixes

- Workaround for addServerImportsDir not working ([5a189df](https://github.com/Atinux/nuxt-auth-utils/commit/5a189df))

### 📖 Documentation

- Update readme ([06f1504](https://github.com/Atinux/nuxt-auth-utils/commit/06f1504))

### 🏡 Chore

- Init ([19caed2](https://github.com/Atinux/nuxt-auth-utils/commit/19caed2))
- Add runtime config ([9013484](https://github.com/Atinux/nuxt-auth-utils/commit/9013484))
- V0 ([18ea43a](https://github.com/Atinux/nuxt-auth-utils/commit/18ea43a))
- Init ([9b75953](https://github.com/Atinux/nuxt-auth-utils/commit/9b75953))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
