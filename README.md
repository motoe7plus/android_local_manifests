## clone and sync
---

```
mkdir -p .repo/local_manifests
curl -sL "https://raw.githubusercontent.com/motoe7plus/android_local_manifests/refs/heads/main/default.xml" > .repo/local_manifests/guam_tree_manifest_git.xml
repo sync -c -j$(nproc) --force-sync --no-clone-bundle --no-tags
```
