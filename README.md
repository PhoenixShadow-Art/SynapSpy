# SynapSpy

SynapSpy is a Roblox RemoteSpy-style **executor script** made for monitoring, inspecting, and interacting with `RemoteEvent` and `RemoteFunction` calls. It includes a modern UI, live call logging, filtering, and remote controls for copying paths, firing/invoking, and blocking.

## What it does

- Detects `RemoteEvent` and `RemoteFunction` objects
- Shows real-time call logs with timestamps
- Displays remote arguments in a readable format
- Lets you fire / invoke remotes through the UI
- Copies full remote paths
- Blocks / unblocks individual remotes
- Searches remotes by name
- Filters by `All`, `Events`, or `Functions`
- Clears logs
- Refreshes the remote list
- Supports auto-scroll
- Uses a draggable window
- Works on mobile and PC layouts

## How to use

This script is designed to be used with an executor.

Copy loadstring and Execute in Game:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/PhoenixShadow-Art/SynapSpy/refs/heads/main/SynapSpy"))()
```

## Installation

1. Copy the loadString  for the script.
2. Execute the script in your executor.

## Notes

- Some features depend on executor support, including clipboard access and metatable hooking.
- The log system is capped to help keep performance stable.
- SynapSpy is meant for testing, debugging, and analysis.

## License

See the `LICENSE` file for usage terms.
