# Third-Party Sources (License Compliance)

AudioRoo bundles **FFmpeg** and **FFprobe**, which are
licensed under the LGPL v2.1 or later. They ship as separate executables in
`Contents/MacOS/Helpers` and are invoked as external programs. 

This folder exists so the complete source for those components is available from the same
place, for anyone who wants to inspect, rebuild, or replace them.

## Where the source is

Every AudioRoo release has a matching tag here, with the complete and unmodified source
archives attached as release assets.

Each release includes the FFmpeg/FFprobe source and the source and build config for every library built into it
(LAME, mpg123, libogg, libvorbis, libopus, libsoxr).

Older releases stay published. If you are running an older version of AudioRoo, use the version tag
matching that version — library versions may differ between releases.

## Build configuration

The exact FFmpeg commit or release, the full configure line, and the license texts for every
component are in `Contents/Resources/Licensing/` inside the application bundle —
see `Open-Source-Notices.txt`.
