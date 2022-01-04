# MiningsBoard

This is a (WIP) utility to consolidate mining rigs status data into telemetry format that [Thingsboard](https://github.com/thingsboard/thingsboard) recognizes.

The usage of this tool assumes that you already have a Thingsboard running locally or on a cloud instance. Another possible scenario is to register for a free trial at [Thingsboard Cloud](https://thingsboard.cloud). The "Maker" Tier works for up to 10 devices

# Table of Contents
1. [Dependencies](#dependencies)
2. [Supported Miners](#supported-miners)
3. [Prerequisites](#prerequisites)
4. [Customization](#customization)
5. [Troubleshooting](#troubleshooting)

# Dependencies

MiningsBoard's functionality depends on:
- (obviously) a running `Thingsboard`
- `browsh` - a modern command line browser with JS support
- `httpie` - a `curl` alternative for mere mortals
- `csvkit` - used for the `csvjson` utility
- (Optionally) [`log2ram`](https://github.com/azlux) - Recommended if your system is running on MicroSD or SSD

Most of the dependencies (short of Thingsboard and Log2RAM) can be conveniently installed using `install-deps` script

# Supported Miners

Basically only:
- Antminer S17+ on Stock FW

Upcoming:
- GPU Rigs using T-Rex Miner
- Cheetah F3 on Stock FW (like, is there any custom FW for it?)

# Prerequisites

<deployment assumptions>

# Customization

Coming soon-ish.

# Troubleshooting

LOL not yet. Look at the bash scripts for now.
