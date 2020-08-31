# beets-alternative-mod
Mod to install the beets-alternatives plugin into the linuxserver/beets container

## Instructions

More instructions to follow as this is in testing, but to add beets-alternative to the linuxserver/beets controller you should only need to supply the following argument to your docker run command:

```
-e DOCKER_MODS=furiousgeorge/beets-alternative-mod:latest
```
