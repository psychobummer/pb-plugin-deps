# Pinned sources

Unmodified subsets of third-party open-source code, kept so that builds do
not depend on the upstream hosts. Each release holds one set of archives;
the consuming repository pins every archive by SHA-256 and by tree hash.

## Release `recoil-bungee-2.4.39`

| Archive | Upstream | Commit | Licence | Contents |
| --- | --- | --- | --- | --- |
| `bungee-2.4.39.tar.gz` | https://github.com/bungee-audio-stretch/bungee (v2.4.39) | `61f52bf34be577d189d388772ddfa3696dee77d8` | MPL-2.0 (`LICENSE`) | `bungee/Bungee.h`, `bungee/Modes.h`, `src/` |
| `pffft-02fe7715.tar.gz` | https://bitbucket.org/jpommier/pffft | `02fe7715a5bf8bfd914681c53429600f94e0f536` | FFTPACK-style, in `pffft.h` | library sources, no test program |
| `eigen-c29c8001.tar.gz` | https://github.com/eigenteam/eigen-git-mirror | `c29c800126982c561e8d0b9255dc65474cd98de3` | MPL-2.0 and others (`COPYING.*`) | `Eigen/Core`, `Eigen/src/Core`, `plugins`, `misc` |

## Release `tether-signalsmith-stretch-1.3.2`

| Archive | Upstream | Commit | Licence | Contents |
| --- | --- | --- | --- | --- |
| `signalsmith-stretch-1.3.2.tar.gz` | https://github.com/Signalsmith-Audio/signalsmith-stretch (v1.3.2) | `88061fd4eda56a2353c5d65c74aa3f4ccf76f9da` | MIT (`signalsmith-stretch/LICENSE.txt`) | `signalsmith-stretch/signalsmith-stretch.h` |
| same archive | https://github.com/Signalsmith-Audio/linear (tag 0.6.6, the tag Stretch pins) | `7bb1c8f36794d6980080ce817c91f8da8fe56a66` | MIT (`signalsmith-linear/LICENSE.txt`) | `signalsmith-linear/stft.h`, `fft.h`; no accelerated back ends |

Each archive has one root directory named after the archive. Nothing in the
files is changed from upstream; only whole files and directories are left out.
