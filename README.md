# SynapSpy

SynapSpy is a Roblox **RemoteSpy-style** LocalScript built for monitoring, inspecting, and interacting with `RemoteEvent` and `RemoteFunction` calls. It includes a modern UI, live call logging, filtering, and per-remote controls for copying paths, firing/invoking, and blocking.

## Features

- Detects `RemoteEvent` and `RemoteFunction` objects
- Real-time logging with timestamps
- View remote call arguments in a readable format
- Fire / Invoke popup with argument support
- Copy full remote path to clipboard
- Block / unblock individual remotes
- Search remotes by name
- Filter by `All`, `Events`, or `Functions`
- Clear logs
- Refresh remote list
- Auto-scroll toggle
- Draggable window
- Mobile and PC layout support
- Passive monitoring through metatable hooking
- Log cap to help keep performance stable

## Installation

1. Put the script inside a **LocalScript**.
2. Place it in either:
   - `StarterPlayerScripts`, or
   - `StarterGui`
3. Run the game and the SynapSpy window will load automatically.

## How It Works

SynapSpy scans common Roblox containers and registers remotes it finds. When a remote is used, it records the call, updates the UI, and adds a log entry. It also tracks whether a remote is currently blocked or being watched.

## Controls

### Top bar
- **Search box**: filter remotes by name
- **All / Events / Functions**: switch the remote list view
- **Refresh**: rescan and rebuild the remote list
- **Clear**: remove log entries
- **Auto-scroll**: toggle whether logs stay pinned to the newest entry

### Remote row actions
- **Copy**: copy the remote path
- **Fire**: open the argument popup for firing or invoking
- **Spy**: toggle logging for that remote
- **Block**: prevent that remote from being used while blocked

## Notes

- Some actions depend on executor support, such as clipboard access and metatable hooking.
- The log system is capped at 500 entries to avoid unnecessary performance issues.
- This script is intended for testing, debugging, and analysis.

## Version

**SynapSpy v1.0**
