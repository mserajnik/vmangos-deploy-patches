# vmangos-deploy-patches

This repository contains patches for [VMaNGOS][vmangos] that are applied when
building the Docker images for [vmangos-deploy][vmangos-deploy].

The patches are strictly for:

+ Correcting problems that would cause build failures, runtime crashes, or
  database corruption
+ Making Docker-specific adjustments that would not be appropriate to include
  upstream

At no point will a patch be added that changes the behavior of the server or
otherwise alters its functionality.

Once a patch is no longer needed, it will be removed from this repository.
Therefore, there may be times when this repository contains no patches at all.

[vmangos]: https://github.com/vmangos/core
[vmangos-deploy]: https://github.com/mserajnik/vmangos-deploy
