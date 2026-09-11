# Third-Party Sources (License Compliance)

AudioRoo is made possible by open-source software and I am grateful to the developers of these packages.

The app uses FFmpeg, FFprobe, LAME, mpg123, libsoxr, libogg, libvorbis and libopus under various licenses. 

This folder exists so the complete source and licenses for these components is available from the same place.

## Where the source is

A tag is created whenever the bundled libraries change, with the complete and unmodified
source archives attached as release assets. App versions released between those points reuse
the most recent tag, because the binaries they ship are unchanged.

To find the source for a given version of AudioRoo, use the most recent tag that does not
exceed it. Older tags stay published indefinitely.

Each tag includes the FFmpeg and FFprobe source, along with the source and build configuration
for every library built into them: LAME, mpg123, libogg, libvorbis, libopus and libsoxr.

## Build configuration

The license texts for every component are in `Contents/Resources/Licensing/` inside the
application bundle. `Open-Source-Notices.txt`, in that folder and posted here, gives the
exact FFmpeg commit or release and the full configure line for each library. Build details may
vary between versions and are updated under the same tagging system.
