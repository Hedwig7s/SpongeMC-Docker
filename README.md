# FabricMC-Docker

Docker image running [FabricMC](https://fabricmc.net/)

## Usage

```bash
$ docker run -d \
    -v minecraft:/home/server \
    -p 25565:25565 \
    thisredh/purpurmc
```

## Environment Variables

All of the Environment Variables:

| Variable | Value | Description |
| - | - | - |
| MC_VERSION | `1.20.1` | The Minecraft version to use |
| MC_EULA | `true` | Accepting the [EULA](https://account.mojang.com/documents/minecraft_eula) |
| MC_RAM_XMS | `1536M` | Preallocated RAM (for Purpur) |
| MC_RAM_XMX | `2048M` | Max RAM (for Purpur) |
| MC_PRE_JAR_ARGS | `<ARGS>` | Java Arg's (for experienced User's only) |
| MC_POST_JAR_ARGS | `<ARGS>` | Purpur Arg's (for experienced User's only) |
| MC_URL_ZIP_SERVER_FILES | `<URL to archive(zip, rar, tar, ...)>` | Import files from another Server or Import Config's/Plugin's (for experienced User's only) |
| MC_URL_ZIP_SERVER_FILES | `<URL to archive(zip, rar, tar, ...)>` | Import files from another Server or Import Config's/Plugin's (for experienced User's only) |
| MC_URL_ZIP_SERVER_FILES | `<URL to archive(zip, rar, tar, ...)>` | Import files from another Server or Import Config's/Plugin's (for experienced User's only) |
| FABRIC_VERSION | `<Fabric version>` | Fabric version to use |
| FABRIC_INSTALLVER | `` | Fabric installer version to use |
| FORCE_INSTALL | `<Should force install>` | Install whether the jar exists or not. Leave empty to update when jar is missing |
