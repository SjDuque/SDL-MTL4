This is a minimal downstream fork of [libsdl-org/SDL](https://github.com/libsdl-org/SDL)
that applies a light patch replacing the `SDL_gpu` Metal backend with Metal 4.

- **Apple OS & hardware requirements:** Requires **Apple OS 26.0+** and
  [Metal 4 devices](https://support.apple.com/en-us/102894). Older Apple OS
  versions and non-Metal 4 hardware are not supported by the Metal GPU backend
  in this fork.
- **Branch naming & upstream sync:** Branches mirror upstream SDL's naming
  (`main` and the latest `release-*` branch such as `release-3.4.x`) and are
  automatically synced with upstream while keeping the Metal 4 patch applied.

---

Simple DirectMedia Layer (SDL for short) is a cross-platform library
designed to make it easy to write multi-media software, such as games
and emulators.

You can find the latest release and additional information at:
https://www.libsdl.org/

Installation instructions and a quick introduction is available in
[INSTALL.md](INSTALL.md)

This library is distributed under the terms of the zlib license,
available in [LICENSE.txt](LICENSE.txt).

Enjoy!

Sam Lantinga (slouken@libsdl.org)
