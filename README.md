# vmangos-deploy-patches

This repository contains patches for [VMaNGOS][vmangos] that are applied when
building the Docker images for [vmangos-deploy][vmangos-deploy].

These patches provide temporary workarounds for bugs and issues before they
are fixed upstream. The patches are strictly for correcting problems that would
cause build failures or result in a faulty database state if not addressed.
At no point will a patch be added that changes the behavior of the server or
otherwise alters its functionality.

Once a patch is no longer needed, it will be removed from this repository.
Therefore, there may be times when this repository contains no patches at all.

[vmangos]: https://github.com/vmangos/core
[vmangos-deploy]: https://github.com/mserajnik/vmangos-deploy
