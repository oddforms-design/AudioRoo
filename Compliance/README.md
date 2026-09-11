# Third-Party Sources (License Compliance)

AudioRoo is made possible by open-source software and I am grateful to the developers of these packages.

The app uses FFmpeg, FFprobe, LAME, mpg123, libsoxr, libogg, libvorbis and libopus under various licenses. 

This folder exists so the complete source and licenses for these components is available from the same place.

## Where the source is

Every AudioRoo release v2+ has a matching tag here, with the complete and unmodified source
archives attached as release assets.

Each release includes the FFmpeg/FFprobe source and the source and build config for every library built into it
(LAME, mpg123, libogg, libvorbis, libopus, libsoxr).

Older releases stay published. If you are running an older version of AudioRoo, use the version tag
matching that version — library versions may differ between releases.

## Build configuration

The exact FFmpeg commit or release, the full configure line, and the license texts for every
component are in `Contents/Resources/Licensing/` inside the application bundle —
see `Open-Source-Notices.txt`.
