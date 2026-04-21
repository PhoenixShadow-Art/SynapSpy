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

Replace `RAW_URL` with your GitHub raw file link:

```lua
loadstring(game:HttpGet("RAW_URL"))()
```

## Installation

1. Upload the main script to your GitHub repository.
2. Copy the raw link for the script.
3. Replace `RAW_URL` in the loadstring above with your raw GitHub link.
4. Execute the script in your executor.

## Notes

- Some features depend on executor support, including clipboard access and metatable hooking.
- The log system is capped to help keep performance stable.
- SynapSpy is meant for testing, debugging, and analysis.

## License

See the `LICENSE` file for usage terms.
