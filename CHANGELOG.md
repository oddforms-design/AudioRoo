# AudioRoo Changelog

What changed in each version of AudioRoo, newest first. Issue numbers link to this repository's [issues](https://github.com/oddforms-design/AudioRoo/issues).

## 2.0.4

- Removed WAV "8-bit Signed" from Advanced Mode. WAV stores 8-bit audio only as unsigned, so this option never produced a file. "8-bit Unsigned" is still there.
- Fixes:
  - A conversion that stopped unexpectedly showed as "Cancelled". It now shows as failed, with the reason.
  - Files added with a format warning were sometimes skipped without being tried. They're now converted.
  - The batch summary could count a failed file twice.

## 2.0.3

- Very large batches no longer crash by running out of open files ([#47](https://github.com/oddforms-design/AudioRoo/issues/47)).
- Faster and smoother with very large queues.

## 2.0.2

- Files with a video track, such as .mov, no longer fail with "artwork could not be attached" ([#28](https://github.com/oddforms-design/AudioRoo/issues/28)).

## 2.0.1

- Show the output folder in Finder from any converted row ([#46](https://github.com/oddforms-design/AudioRoo/issues/46)).
- Choose AAC-LC or HE-AAC ([#37](https://github.com/oddforms-design/AudioRoo/issues/37)).
- New format: OggPCM ([#35](https://github.com/oddforms-design/AudioRoo/issues/35)).
- Removing a folder in Finder removes it from the queue.
- A fuller conversion summary, more detail when a file can't be read, and each file's source codec shown.

## 2.0.0

A redesign: one queue for a single file or thousands, with color-coded formats, progress rings and size estimates.

- Complete UI redesign.
- One look for single files and batches ([#2](https://github.com/oddforms-design/AudioRoo/issues/2), [#20](https://github.com/oddforms-design/AudioRoo/issues/20)).
- Free conversions in every format, and a thank-you after purchase ([#7](https://github.com/oddforms-design/AudioRoo/issues/7)).
- New formats and codecs: A-law and μ-law WAV ([#36](https://github.com/oddforms-design/AudioRoo/issues/36)), WavPack ([#30](https://github.com/oddforms-design/AudioRoo/issues/30)), quad AAC ([#44](https://github.com/oddforms-design/AudioRoo/issues/44)), and bit-depth choices in Advanced Mode.
- Higher-quality resampling with libsoxr ([#13](https://github.com/oddforms-design/AudioRoo/issues/13)).
- FFmpeg with the new AAC encoder ([#45](https://github.com/oddforms-design/AudioRoo/issues/45)) and LAME 4 ([#41](https://github.com/oddforms-design/AudioRoo/issues/41)).
- Flatten or keep folder structure, right from the queue.
- Show in Finder now highlights the file ([#31](https://github.com/oddforms-design/AudioRoo/issues/31)).
- "Save" instead of "Grant Access" when allowing a folder ([#18](https://github.com/oddforms-design/AudioRoo/issues/18)).
- Fixes:
  - Saving to another folder with folders preserved could overwrite source files without a warning ([#42](https://github.com/oddforms-design/AudioRoo/issues/42)).
  - Stopping a conversion left dead items in the queue ([#39](https://github.com/oddforms-design/AudioRoo/issues/39)).
  - Cancelling the folder permission didn't cancel the conversion ([#24](https://github.com/oddforms-design/AudioRoo/issues/24)).
  - Failed conversions left empty folders behind ([#27](https://github.com/oddforms-design/AudioRoo/issues/27)).
  - Files deleted in Finder showed as unreadable instead of deleted ([#22](https://github.com/oddforms-design/AudioRoo/issues/22)).
  - Purchase data no longer uses the keychain, so there are no more keychain prompts ([#38](https://github.com/oddforms-design/AudioRoo/issues/38)).

## 1.1.1

- FFmpeg 8.1 ([#29](https://github.com/oddforms-design/AudioRoo/issues/29)).

## 1.1.0

- Duplicate files that would convert to the same name are greyed out in the queue ([#26](https://github.com/oddforms-design/AudioRoo/issues/26)).
- Choose the MP3 ID3 tag version in Settings ([#9](https://github.com/oddforms-design/AudioRoo/issues/9)).
- Files that fail the format check but may still hold audio can be converted, with a warning ([#23](https://github.com/oddforms-design/AudioRoo/issues/23)).
- Opus 1.6.1 ([#21](https://github.com/oddforms-design/AudioRoo/issues/21)).
- The main window dims while Settings is open ([#11](https://github.com/oddforms-design/AudioRoo/issues/11)).
- Fixes:
  - Adding very large batches no longer hangs ([#10](https://github.com/oddforms-design/AudioRoo/issues/10)).
  - Progress works on files with artwork ([#3](https://github.com/oddforms-design/AudioRoo/issues/3)).
  - Correct file info for AAC files ([#1](https://github.com/oddforms-design/AudioRoo/issues/1)).

## 1.0.3

- Fixed purchases in TestFlight builds ([#17](https://github.com/oddforms-design/AudioRoo/issues/17)).

## 1.0.2

- Fixed an issue restoring a purchase.
- FFmpeg 8.0.1 ([#5](https://github.com/oddforms-design/AudioRoo/issues/5)).

## 1.0.1

- A new App Store subtitle ([#16](https://github.com/oddforms-design/AudioRoo/issues/16)).
- Several small bug fixes.

## 1.0.0

The first release, on January 2, 2026.
