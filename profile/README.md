# Towertail

Towertail monitors a fleet of remote servers from your menu bar or system tray.
The desktop apps connect to each host over SSH (usually on a Tailscale network) and run a small collector, the sampler.
The sampler sends one JSON sample per poll: CPU, memory, disk, network, and processes.
The host does not need a daemon, an agent, or an open port.

- [towertail](https://github.com/towertail/towertail): the macOS and Windows apps, and the self-hosted server (AGPL-3.0).
- [sampler](https://github.com/towertail/sampler): the Go collector that runs on each host (Apache-2.0).
- Website: [towertail.com](https://towertail.com)
