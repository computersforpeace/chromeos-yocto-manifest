# chromeos-yocto-manifest

The [Repo tool] manages our local checkouts.  See the
[CrOS Source Layout documentation] for much more detailed information about
the upstream ChromeOS sources.

See the [upstream repo manifest format documentation] for general info on
manifests and its specification.

## Quick Start

```shell
$ repo init -b kirkstone -u https://github.com/konsulko/chromeos-yocto-manifest.git
$ repo sync -j4
$ source ./meta-chromeos/cros-init-build-env [build-directory]
```

[CrOS Source Layout documentation]: https://chromium.googlesource.com/chromiumos/docs/+/HEAD/source_layout.md
[Repo tool]: https://gerrit.googlesource.com/git-repo/
[upstream repo manifest format documentation]: https://gerrit.googlesource.com/git-repo/+/HEAD/docs/manifest-format.md
