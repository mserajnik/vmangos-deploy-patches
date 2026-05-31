# vmangos-deploy-patches

[![Lint status][badge-lint-status]][badge-lint-status-url]

This repository contains patches for [VMaNGOS][vmangos] that are applied when
building the Docker images for [vmangos-deploy][vmangos-deploy].

The patches are strictly for:

- Correcting problems that would cause build failures, runtime crashes, or
  database corruption.
- Making Docker-specific adjustments that would not be appropriate to include
  upstream.

At no point will a patch be added that changes the behavior of the server or
otherwise alters its functionality.

Once a patch is no longer needed, it will be removed from this repository.
Therefore, there may be times when this repository contains no patches at all.

## Licenses

- [`GPL-2.0-or-later`][license-gpl-2.0-or-later] (Patches, matching VMaNGOS
  source)
- [`AGPL-3.0-or-later`][license-agpl-3.0-or-later] (Workflow files)
- [`CC-BY-SA-4.0`][license-cc-by-sa-4.0] (Documentation)
- [`CC0-1.0`][license-cc0-1.0] (Configuration files)

This project follows the [REUSE specification][reuse-spec].

[badge-lint-status]: https://github.com/mserajnik/vmangos-deploy-patches/actions/workflows/lint.yaml/badge.svg
[badge-lint-status-url]: https://github.com/mserajnik/vmangos-deploy-patches/actions/workflows/lint.yaml
[vmangos]: https://github.com/vmangos/core
[vmangos-deploy]: https://github.com/mserajnik/vmangos-deploy
[license-agpl-3.0-or-later]: LICENSES/AGPL-3.0-or-later.txt
[license-gpl-2.0-or-later]: LICENSES/GPL-2.0-or-later.txt
[license-cc-by-sa-4.0]: LICENSES/CC-BY-SA-4.0.txt
[license-cc0-1.0]: LICENSES/CC0-1.0.txt
[reuse-spec]: https://reuse.software/spec/
