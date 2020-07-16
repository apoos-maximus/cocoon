1. Polari
    * No Problem with Build

2. GNOME - Games
    * Build Isuue Found
    * Rwquires a general fix for beginners
    * Stacktrace
    ```
        cp: cannot stat '/home/apoos_maximus/.var/app/org.gnome.Builder/cache/gnome-builder/flatpak-builder/git/https_github.com_libretro_parallel-n64': No such file or directory
        cp: cannot stat '/home/apoos_maximus/.var/app/org.gnome.Builder/cache/gnome-builder/flatpak-builder/git/https_github.com_libretro_parallel-n64': No such file or directory
        Error: module libretro-parallel_n64: Child process exited with code 1
        flatpak-builder --arch=x86_64 --ccache --force-clean --disable-updates --disable-download --state-dir /home/apoos_maximus/.var/app/org.gnome.Builder/cache/gnome-builder/flatpak-builder --stop-at=gnome-games /home/apoos_maximus/.var/app/org.gnome.Builder/cache/gnome-builder/projects/gnome-games/flatpak/staging/x86_64-master /home/apoos_maximus/Projects/gnome-games/flatpak/org.gnome.Games.json
        Emptying app dir '/home/apoos_maximus/.var/app/org.gnome.Builder/cache/gnome-builder/projects/gnome-games/flatpak/staging/x86_64-master'
        Starting build of org.gnome.GamesDevel
        Cache hit for lua-5.3, skipping build
        Cache hit for SDL1, skipping build
        Cache hit for SDL_net, skipping build
        Cache hit for libretro-bsnes-mercury, skipping build
        Cache hit for libretro-desmume2015, skipping build
        Cache hit for libretro-dosbox_svn, skipping build
        Cache hit for libretro-gambatte, skipping build
        Cache hit for libretro-gearsystem, skipping build
        Cache hit for libretro-handy, skipping build
        Cache hit for libretro-mednafen_ngp, skipping build
        Cache hit for libretro-mednafen_pce_fast, skipping build
        Cache hit for libretro-mednafen_saturn, skipping build
        Cache hit for libretro-mednafen_vb, skipping build
        Cache hit for libretro-mednafen_wswan, skipping build
        Cache hit for libretro-mgba, skipping build
        Cache hit for libretro-nestopia, skipping build

        (flatpak-builder:819): flatpak-builder-WARNING **: 02:57:06.236: Failed to get current git checksum: Failed to change to directory “/home/apoos_maximus/.var/app/org.gnome.Builder/cache/gnome-builder/flatpak-builder/git/https_github.com_libretro_parallel-n64” (No such file or directory)
        Cache miss, checking out last cache hit

        (flatpak-builder:819): flatpak-builder-WARNING **: 02:57:06.332: rofiles-fuse not available, doing without
        ========================================================================
        Building module libretro-parallel_n64 in /home/apoos_maximus/.var/app/org.gnome.Builder/cache/gnome-builder/flatpak-builder/build/libretro-parallel_n64-4
        ========================================================================
        cp: cannot stat '/home/apoos_maximus/.var/app/org.gnome.Builder/cache/gnome-builder/flatpak-builder/git/https_github.com_libretro_parallel-n64': No such file or directory
        Error: module libretro-parallel_n64: Child process exited with code 1
    ```
3. GNOME Maps
    * No Problem with build
    * Builder Crashed once - Restarting works just fine

4. Music
    * No Build Issues

5. Nautilus
    * No Build Issues in Builder
    * Also I would love to supply a build-documentation using toolbox

6. Sound Recorder
    * No Build Issues

7. Photos
    * Build Failed
    * Reason - Meson Version
    * StackTrace
```
    Already on 'master'
    The Meson build system
    Version: 0.53.2
    Source dir: /run/build/babl
    Build dir: /run/build/babl/_flatpak_build
    Build type: native build

    meson.build:1:0: ERROR: Meson version is 0.53.2 but project requires >=0.54.0

    A full log can be found at /run/build/babl/_flatpak_build/meson-logs/meson-log.txt
    Error: module babl: Child process exited with code 1
    flatpak-builder --arch=x86_64 --ccache --force-clean --disable-updates --disable-download --state-dir /home/apoos_maximus/.var/app/org.gnome.Builder/cache/gnome-builder/flatpak-builder --stop-at=gnome-photos /home/apoos_maximus/.var/app/org.gnome.Builder/cache/gnome-builder/projects/gnome-photos/flatpak/staging/x86_64-master /home/apoos_maximus/Projects/gnome-photos/flatpak/org.gnome.Photos.json

    (flatpak-builder:367): Json-WARNING **: 04:20:58.110: Failed to deserialize "disable-shallow-clone" property of type "gboolean" for an object of type "BuilderSourceGit"
    Emptying app dir '/home/apoos_maximus/.var/app/org.gnome.Builder/cache/gnome-builder/projects/gnome-photos/flatpak/staging/x86_64-master'
    Starting build of org.gnome.Photos
    Cache miss, checking out last cache hit

    (flatpak-builder:367): flatpak-builder-WARNING **: 04:20:58.319: rofiles-fuse not available, doing without
    ========================================================================
    Building module babl in /home/apoos_maximus/.var/app/org.gnome.Builder/cache/gnome-builder/flatpak-builder/build/babl-2
    ========================================================================
 ```

8. Boxes
   * No Build Issues

9. Gitg
    * No build issues

10. Clocks
    * No build issues

11. Connections
    * Tile for Connections is not present by default
        in Builder.
    * mentioning about clone-project option can be helpful
    * No build Issues

---------------------------------------------------------------------

