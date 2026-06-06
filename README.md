## clone and sync
---


```
mkdir -p .repo/local_manifests
```
```
curl -sL "https://raw.githubusercontent.com/zedisspp/android_local_manifests/refs/heads/16.2/default.xml" > .repo/local_manifests/bangkk_tree.xml
```
```
repo sync -c -j$(nproc) --force-sync --no-clone-bundle --no-tags
```
