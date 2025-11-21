# Changelog

## [Unreleased](https://github.com/LucasLarson/update/tree/HEAD)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.7.0...HEAD)

**Merged pull requests:**

- chore\(deps\): bump actions/checkout from v5 to v6 [\#79](https://github.com/LucasLarson/update/pull/79) ([renovate[bot]](https://github.com/apps/renovate))

## [v1.7.0](https://github.com/LucasLarson/update/tree/v1.7.0) (2025-11-05)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.6.0...v1.7.0)

## [v1.6.0](https://github.com/LucasLarson/update/tree/v1.6.0) (2025-10-10)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.5.1...v1.6.0)

**Merged pull requests:**

- feat: skip Biome formatting check [\#78](https://github.com/LucasLarson/update/pull/78) ([LucasLarson](https://github.com/LucasLarson))
- fix: do not force unneeded installations [\#77](https://github.com/LucasLarson/update/pull/77) ([LucasLarson](https://github.com/LucasLarson))
- chore\(config\): migrate renovate config [\#75](https://github.com/LucasLarson/update/pull/75) ([renovate[bot]](https://github.com/apps/renovate))
- chore\(deps\): bump ruby from 3.2.0 to 3.4.7 [\#74](https://github.com/LucasLarson/update/pull/74) ([renovate[bot]](https://github.com/apps/renovate))

## [v1.5.1](https://github.com/LucasLarson/update/tree/v1.5.1) (2025-10-10)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.5.0...v1.5.1)

**Merged pull requests:**

- fix: prevent GitHub Actions credential persistence \(artipacked\) [\#73](https://github.com/LucasLarson/update/pull/73) ([LucasLarson](https://github.com/LucasLarson))
- chore\(deps\): bump super-linter from v7 to v8 [\#72](https://github.com/LucasLarson/update/pull/72) ([dependabot[bot]](https://github.com/apps/dependabot))
- style: apply `prettier` to YAML content [\#70](https://github.com/LucasLarson/update/pull/70) ([LucasLarson](https://github.com/LucasLarson))
- fix: set GitHub actions permissions to `write` \(CKV2\_GHA\_1\) [\#69](https://github.com/LucasLarson/update/pull/69) ([LucasLarson](https://github.com/LucasLarson))
- chore\(deps\): bump github/super-linter from v6 to v7 [\#68](https://github.com/LucasLarson/update/pull/68) ([dependabot[bot]](https://github.com/apps/dependabot))
- chore\(deps\): bump ad-m/github-push-action from v0.8.0 to v1.0.0 [\#67](https://github.com/LucasLarson/update/pull/67) ([renovate[bot]](https://github.com/apps/renovate))
- chore\(deps\): bump actions/checkout from v4 to v5 [\#66](https://github.com/LucasLarson/update/pull/66) ([renovate[bot]](https://github.com/apps/renovate))
- chore\(deps\): bump super-linter from v5 to v6 [\#61](https://github.com/LucasLarson/update/pull/61) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v1.5.0](https://github.com/LucasLarson/update/tree/v1.5.0) (2025-07-02)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.4.6...v1.5.0)

## [v1.4.6](https://github.com/LucasLarson/update/tree/v1.4.6) (2025-05-15)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.4.5...v1.4.6)

## [v1.4.5](https://github.com/LucasLarson/update/tree/v1.4.5) (2025-05-12)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.4.4...v1.4.5)

**Implemented enhancements:**

- feat: retain `svgo` release candidate after `npm update` [\#65](https://github.com/LucasLarson/update/pull/65) ([LucasLarson](https://github.com/LucasLarson))

**Merged pull requests:**

- fix: repair update-available behavior [\#63](https://github.com/LucasLarson/update/pull/63) ([LucasLarson](https://github.com/LucasLarson))

## [v1.4.4](https://github.com/LucasLarson/update/tree/v1.4.4) (2024-04-21)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.4.3...v1.4.4)

**Implemented enhancements:**

- use preferred `Brewfile` location if possible [\#57](https://github.com/LucasLarson/update/issues/57)
- fix: use preferred `Brewfile` location [\#58](https://github.com/LucasLarson/update/pull/58) ([LucasLarson](https://github.com/LucasLarson))

**Closed issues:**

- clear variables with fewer steps [\#53](https://github.com/LucasLarson/update/issues/53)

**Merged pull requests:**

- fix: ensure `rubocop`-compliant `Brewfile` [\#60](https://github.com/LucasLarson/update/pull/60) ([LucasLarson](https://github.com/LucasLarson))

## [v1.4.3](https://github.com/LucasLarson/update/tree/v1.4.3) (2024-02-08)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.4.2...v1.4.3)

**Fixed bugs:**

- user `$IFS` is modified [\#51](https://github.com/LucasLarson/update/issues/51)

**Closed issues:**

- add `--verbose` to `brew upgrade` [\#50](https://github.com/LucasLarson/update/issues/50)
- reduce preposition usage duplication [\#49](https://github.com/LucasLarson/update/issues/49)
- inconsistent `test` calls [\#45](https://github.com/LucasLarson/update/issues/45)

**Merged pull requests:**

- refactor: unset variables with graceful degradation \(\#53\) [\#56](https://github.com/LucasLarson/update/pull/56) ([LucasLarson](https://github.com/LucasLarson))
- feat: add `--verbose` option to `brew upgrade` \(\#50\) [\#55](https://github.com/LucasLarson/update/pull/55) ([LucasLarson](https://github.com/LucasLarson))
- fix: protect user `$IFS` from modification \(\#51\) [\#54](https://github.com/LucasLarson/update/pull/54) ([LucasLarson](https://github.com/LucasLarson))
- docs: reword download prompt [\#52](https://github.com/LucasLarson/update/pull/52) ([LucasLarson](https://github.com/LucasLarson))

## [v1.4.2](https://github.com/LucasLarson/update/tree/v1.4.2) (2024-01-14)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.4.1...v1.4.2)

**Closed issues:**

- `npm` prompts the user to fund packages [\#44](https://github.com/LucasLarson/update/issues/44)

**Merged pull requests:**

- perf: prepend all `test` calls with `command -p` [\#48](https://github.com/LucasLarson/update/pull/48) ([LucasLarson](https://github.com/LucasLarson))

## [v1.4.1](https://github.com/LucasLarson/update/tree/v1.4.1) (2024-01-13)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.4.0...v1.4.1)

**Closed issues:**

- inconsistent `npm` instructions [\#43](https://github.com/LucasLarson/update/issues/43)

**Merged pull requests:**

- suppress `npm` fundraising prompts [\#47](https://github.com/LucasLarson/update/pull/47) ([LucasLarson](https://github.com/LucasLarson))
- keep `npm` recommendations consistent [\#46](https://github.com/LucasLarson/update/pull/46) ([LucasLarson](https://github.com/LucasLarson))

## [v1.4.0](https://github.com/LucasLarson/update/tree/v1.4.0) (2024-01-11)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.3.1...v1.4.0)

**Closed issues:**

- for utilities POSIX guarantees, use `command -p` instead of `command` [\#41](https://github.com/LucasLarson/update/issues/41)

**Merged pull requests:**

- perf: prepend POSIX utilities with `command -p` [\#42](https://github.com/LucasLarson/update/pull/42) ([LucasLarson](https://github.com/LucasLarson))

## [v1.3.1](https://github.com/LucasLarson/update/tree/v1.3.1) (2023-10-29)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.3.0...v1.3.1)

**Merged pull requests:**

- feat: prevent modifying `~/.wget-hsts` [\#40](https://github.com/LucasLarson/update/pull/40) ([LucasLarson](https://github.com/LucasLarson))

## [v1.3.0](https://github.com/LucasLarson/update/tree/v1.3.0) (2023-10-26)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.2.1...v1.3.0)

**Merged pull requests:**

- feat: add Cabal support [\#39](https://github.com/LucasLarson/update/pull/39) ([LucasLarson](https://github.com/LucasLarson))
- bump ad-m/github-push-action from v0.6.0 to v0.8.0 [\#38](https://github.com/LucasLarson/update/pull/38) ([renovate[bot]](https://github.com/apps/renovate))
- harmonize space formatting [\#37](https://github.com/LucasLarson/update/pull/37) ([LucasLarson](https://github.com/LucasLarson))

## [v1.2.1](https://github.com/LucasLarson/update/tree/v1.2.1) (2023-10-05)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.2.0...v1.2.1)

**Merged pull requests:**

- ensure correct exit when offline \(\#32\) [\#36](https://github.com/LucasLarson/update/pull/36) ([LucasLarson](https://github.com/LucasLarson))
- bump actions/checkout from 3 to 4 [\#34](https://github.com/LucasLarson/update/pull/34) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v1.2.0](https://github.com/LucasLarson/update/tree/v1.2.0) (2023-07-21)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.1.0...v1.2.0)

**Implemented enhancements:**

- feature: add check for a newer version of this script from within script [\#15](https://github.com/LucasLarson/update/issues/15)

**Merged pull requests:**

- ensure script can be sourced or copied and pasted [\#32](https://github.com/LucasLarson/update/pull/32) ([LucasLarson](https://github.com/LucasLarson))

## [v1.1.0](https://github.com/LucasLarson/update/tree/v1.1.0) (2023-07-11)

[Full Changelog](https://github.com/LucasLarson/update/compare/v1.0.0...v1.1.0)

**Implemented enhancements:**

- find syntax [\#19](https://github.com/LucasLarson/update/issues/19)
- notify when new script version is available [\#29](https://github.com/LucasLarson/update/pull/29) ([LucasLarson](https://github.com/LucasLarson))
- restore date of last modification to script [\#28](https://github.com/LucasLarson/update/pull/28) ([LucasLarson](https://github.com/LucasLarson))
- skip loading run-commands file load before shell restart [\#27](https://github.com/LucasLarson/update/pull/27) ([LucasLarson](https://github.com/LucasLarson))
- ensure `~/.Brewfile` opens with Ruby hashbang [\#17](https://github.com/LucasLarson/update/pull/17) ([LucasLarson](https://github.com/LucasLarson))

**Fixed bugs:**

- send informational text to standard error [\#18](https://github.com/LucasLarson/update/issues/18)

**Merged pull requests:**

- upgrade, repair changelog generator [\#31](https://github.com/LucasLarson/update/pull/31) ([LucasLarson](https://github.com/LucasLarson))
- add end-of-options delimiter to `read` [\#30](https://github.com/LucasLarson/update/pull/30) ([LucasLarson](https://github.com/LucasLarson))
- bump github/super-linter from 4 to 5 [\#26](https://github.com/LucasLarson/update/pull/26) ([dependabot[bot]](https://github.com/apps/dependabot))
- use more common npm syntax [\#24](https://github.com/LucasLarson/update/pull/24) ([LucasLarson](https://github.com/LucasLarson))
- send informational text to standard error [\#23](https://github.com/LucasLarson/update/pull/23) ([LucasLarson](https://github.com/LucasLarson))
- send informational text to standard error [\#22](https://github.com/LucasLarson/update/pull/22) ([LucasLarson](https://github.com/LucasLarson))
- optimize `find` commands [\#21](https://github.com/LucasLarson/update/pull/21) ([LucasLarson](https://github.com/LucasLarson))
- replace deprecated npm syntax \(\#13\) [\#14](https://github.com/LucasLarson/update/pull/14) ([LucasLarson](https://github.com/LucasLarson))

## [v1.0.0](https://github.com/LucasLarson/update/tree/v1.0.0) (2022-08-23)

[Full Changelog](https://github.com/LucasLarson/update/compare/v0.0.0...v1.0.0)

**Implemented enhancements:**

- add readme with provenance, license [\#6](https://github.com/LucasLarson/update/pull/6) ([LucasLarson](https://github.com/LucasLarson))
- add @GitHub Super-Linter workflow [\#2](https://github.com/LucasLarson/update/pull/2) ([LucasLarson](https://github.com/LucasLarson))

**Merged pull requests:**

- add changelog generator [\#11](https://github.com/LucasLarson/update/pull/11) ([LucasLarson](https://github.com/LucasLarson))
- add changelog generator [\#10](https://github.com/LucasLarson/update/pull/10) ([LucasLarson](https://github.com/LucasLarson))
- add `codeowners` with single entry [\#8](https://github.com/LucasLarson/update/pull/8) ([LucasLarson](https://github.com/LucasLarson))
- add kitchen-sink @Dependabot configuration [\#7](https://github.com/LucasLarson/update/pull/7) ([LucasLarson](https://github.com/LucasLarson))
- add license [\#5](https://github.com/LucasLarson/update/pull/5) ([LucasLarson](https://github.com/LucasLarson))
- Configure Renovate [\#3](https://github.com/LucasLarson/update/pull/3) ([renovate[bot]](https://github.com/apps/renovate))
- Configure WhiteSource Bolt for GitHub [\#1](https://github.com/LucasLarson/update/pull/1) ([mend-bolt-for-github[bot]](https://github.com/apps/mend-bolt-for-github))

## [v0.0.0](https://github.com/LucasLarson/update/tree/v0.0.0) (2021-11-30)

[Full Changelog](https://github.com/LucasLarson/update/compare/v0.0.1...v0.0.0)

## [v0.0.1](https://github.com/LucasLarson/update/tree/v0.0.1) (2021-11-30)

[Full Changelog](https://github.com/LucasLarson/update/compare/2d139b7da18273660b698d9fa041efaaeee0c94c...v0.0.1)

\* *This changelog was [automatically generated](./.github/workflows/changelog.yml) by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator).*
