# Changelog

## 1.0.0

* If the user doesn't provide a queue explicitly, infer it from time and memory requirements
* Treat `ZOMBI` as a fail state
* Wait on `UNKWN` jobs instead of marking them as finished

## [0.2.0](https://github.com/snakemake/snakemake-executor-plugin-slurm/compare/v0.2.1...v0.2.2) (2024-02-01)


### Bug Fixes

* Integrate changes in Slurm executor up to 0.2.2
* Remove some Slurm references

### Features

* Integrate changes in Slurm executor up to 0.2.2

## [0.1.1](https://github.com/snakemake/snakemake-executor-plugin-slurm/compare/v0.1.0...v0.1.1) (2023-10-29)


### Bug Fixes

* fix release process ([794bba8](https://github.com/snakemake/snakemake-executor-plugin-slurm/commit/794bba86df23ac4d1610f48434e631f0cc43b829))

## 0.1.0 (2023-10-29)


### Bug Fixes

* adapt to API change ([4110331](https://github.com/snakemake/snakemake-executor-plugin-slurm/commit/411033198028eb8f894d1327300b5c10ce9618bb))
* adapt to API changes ([75b2383](https://github.com/snakemake/snakemake-executor-plugin-slurm/commit/75b2383b914a3dab8e64a68213089b509f322691))
* adapt to API changes in Snakemake 8 ([4c12093](https://github.com/snakemake/snakemake-executor-plugin-slurm/commit/4c1209399bfd0ce92fd698447be7fdbd3e526073))
* adapt to changes in snakemake-interface-executor-plugins ([e73f71d](https://github.com/snakemake/snakemake-executor-plugin-slurm/commit/e73f71df9e0087afb58f2acd7e71b61b2740a263))
* add dependency on slurm-jobstep ([fb5cdbc](https://github.com/snakemake/snakemake-executor-plugin-slurm/commit/fb5cdbc7694144dcb291846810b2b44261fc0a5d))
* update to fixed version of snakemake-interface-executor-plugins ([#2](https://github.com/snakemake/snakemake-executor-plugin-slurm/issues/2)) ([3dc72c6](https://github.com/snakemake/snakemake-executor-plugin-slurm/commit/3dc72c69a5cbbfd150c21843adb16530c8fa7d34))
