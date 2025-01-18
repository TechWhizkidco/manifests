# Manifest

## Usage Example

```shell
repo init -u https://github.com/TechWhizkidco/manifests.git -b main -m default.xml
repo sync
cd poky
source oe-init-build-env
bitbake core-image-full-cmdline
```
