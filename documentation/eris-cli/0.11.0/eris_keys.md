---

layout:     documentation
title:      "Documentation | eris:cli | eris keys"

---

# eris keys

Do specific tasks with keys *for dev only*.

## Synopsis

The keys subcommand is an opiniated wrapper around
eris-keys and requires a keys container to be running.

It is for development only. Advanced functionality is available via
the [eris services exec keys "eris-keys CMD"] command.

See https://docs.erisindustries.com/documentation/eris-keys/ for more info.

```bash
eris keys
```

## Options inherited from parent commands

```
  -d, --debug            debug level output
  -m, --machine string   machine name for docker-machine that is running VM (default "eris")
  -n, --num int          container number (default 1)
  -v, --verbose          verbose output
```

## Subcommands

* [eris keys convert](https://docs.erisindustries.com/documentation/eris-cli/0.11.0/eris_keys_convert/)	 - Convert and eris-keys key to tendermint key
* [eris keys export](https://docs.erisindustries.com/documentation/eris-cli/0.11.0/eris_keys_export/)	 - Export a key from container to host.
* [eris keys gen](https://docs.erisindustries.com/documentation/eris-cli/0.11.0/eris_keys_gen/)	 - Generates an unsafe key using the keys container.
* [eris keys import](https://docs.erisindustries.com/documentation/eris-cli/0.11.0/eris_keys_import/)	 - Import a key to container from host.
* [eris keys ls](https://docs.erisindustries.com/documentation/eris-cli/0.11.0/eris_keys_ls/)	 - List keys on host and in running keys container
* [eris keys pub](https://docs.erisindustries.com/documentation/eris-cli/0.11.0/eris_keys_pub/)	 - Returns a machine readable pubkey given an address.

## See Also

* [eris](https://docs.erisindustries.com/documentation/eris-cli/0.11.0/eris/)	 - The Blockchain Application Platform

## Specifications

* [Actions Specification](https://docs.erisindustries.com/documentation/eris-cli/0.11.0/actions_specification/)
* [Chains Specification](https://docs.erisindustries.com/documentation/eris-cli/0.11.0/chains_specification/)
* [Contracts Specification](https://docs.erisindustries.com/documentation/eris-cli/0.11.0/contracts_specification/)
* [Motivation](https://docs.erisindustries.com/documentation/eris-cli/0.11.0/motivation/)
* [Services Specification](https://docs.erisindustries.com/documentation/eris-cli/0.11.0/services_specification/)

