# bitdrive-network-heuristics
Networking heuristics for announcing Bitdrives on Bitswarm

These heuristics are used in the [`bitdrive-daemon-client`](https://github.com/bitwebs/bitdrive-daemon-client) and [`bitdrive-cli`](https://github.com/bitwebs/bitdrive-cli).

### Usage
There's only one exported method, which is used to enable the networking heuristics:

#### `applyHeuristics(drive, networker)`

Applies networking heuristics to a drive.

- `drive`: A Bitdrive instance
- `networker`: A `@web4/chainstore-networker` or Bitspace `RemoteNetworker`

### License
MIT
