# FileSystem wrap

Added meson wrap for [filesystem](https://github.com/gulrak/filesystem).

## Usage

Create `<root-project>/subprojects/filesystem.wrap`, containing:
```
[wrap-file]
directory = filesystem-1.5.12

source_url = https://github.com/gulrak/filesystem/archive/refs/tags/v1.5.12.zip
source_filename = v1.5.12.zip
source_hash = 94c634d499558a76fa649edb13721dce6e98fb1e7018dfaeba3cd7a083945e91

patch_url = https://github.com/Sebastiaan-Alvarez-Rodriguez/filesystem/archive/refs/tabs/v1.5.12.zip
patch_filename = 1.5.12.zip
patch_hash = 04ff14e8880e4e465f6260221e9dfd56fea6bc7cce4c4aff0dc528e4a2c8f514
```