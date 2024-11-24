[![Tests](https://github.com/Bergbok/Scoop-Bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Bergbok/Scoop-Bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/Bergbok/Scoop-Bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Bergbok/Scoop-Bucket/actions/workflows/excavator.yml)

Bucket for [Scoop](https://scoop.sh), the best Windows command-line installer.

Contains manifests for miscellaneous apps not in the [official buckets](https://github.com/ScoopInstaller?q=%F0%9F%93%A6&type=all&language=&sort=stargazers).

```pwsh
scoop bucket add <bucket-alias> https://github.com/Bergbok/Scoop-Bucket
scoop install <bucket-alias>/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
