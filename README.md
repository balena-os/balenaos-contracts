BalenaOS Contracts
==================

The collection of contracts for BalenaOS.

Contracts
---------

Each contract is a `.json` file inside the `contracts/` directory. The
convention is to store one contract per file, located in
`contracts/<type>/contract.json`.

Contract types
--------------

__sw.image__: HostOS block images. They define the `hw.device-type` and `sw.os`
the image applies to in its `requires` section, as well as a list of
`sw.recipe.yocto` recipes to build and `sw.package.yocto.ipk` to install.
__sw.os__: Operating system and distribution settings.

Contribute
----------

- Issue Tracker: [https://github.com/balena-os/balenaos-contracts/issues][issues]
- Source Code: [https://github.com/balena-os/balenaos-contracts][source]

License
-------

The project is licensed under the Apache 2.0 license.

[issues]: https://github.com/balena-os/balenaos-contracts/issues
[source]: https://github.com/balena-os/balenaos-contracts
