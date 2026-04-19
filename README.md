# StressTestBots — Minecraft 26.1.2

> **This build targets Minecraft 26.1.2.** It will not work on older Minecraft versions.

A simple plugin used to stress test Minecraft servers by loading in fake players (bots).

This is a fork of the [**original**](https://github.com/crpmax/mc-bots) with a big re-write to the codebase making it a plugin instead of a standalone app.

# Requirements:
- **Minecraft 26.1.2** server (Paper / Bukkit-based, offline mode)
- **Java 25+** (Minecraft 26.1 ships on OpenJDK 25)

# Minecraft 26.1.2 version bump
This version replaces the previous 1.21.11 target. Key changes:
- Paper API `26.1.2.build.+` (new post-26.1 `.build.+` versioning scheme)
- MCProtocolLib `26.1-SNAPSHOT` from [repo.opencollab.dev/maven-snapshots/](https://repo.opencollab.dev/maven-snapshots/)
- CommandAPI `11.2.0` (first release with 26.1 support)
- Gradle `9.1.0` + Shadow `9.4.1` (required for the Java 25 toolchain)
- `ClientCommand.RESPAWN` → `ClientCommand.PERFORM_RESPAWN` (enum rename in the 26.1 protocol)

# Download:
See the [**releases**](https://github.com/ShaneBeee/StressTestBots/releases) page for all releases.

# How To Use:
Please see the [**wiki**](https://github.com/ShaneBeee/StressTestBots/wiki) for all details.

# JavaDocs
Incase you want to interact a bit more, check out the [**JavaDocs**](https://shanebeee.github.io/docs/StressTestBots/)
