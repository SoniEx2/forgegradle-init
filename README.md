# forgegradle-init

A simple Lua 5.3 script that creates Forge mod boilerplate for you.

## Requirements

- Lua 5.3
- Gradle
- LuaFileSystem (for `lfs.mkdir`)
- LuaSocket (for `socket.http`)
- A JSON library that can be loaded with `require("json")` and supports `json.decode(str)`. (e.g. luajson)
- git (for author information and automated `git init`)

## Usage

`mkdir ModName && cd ModName && forgegradle-init yourname.modid modid "ModName" 1.0 1.7.10-latest`
