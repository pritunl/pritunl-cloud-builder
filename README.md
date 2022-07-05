# pritunl-cloud-builder

[![github](https://img.shields.io/badge/github-pritunl-11bdc2.svg?style=flat)](https://github.com/pritunl)
[![twitter](https://img.shields.io/badge/twitter-pritunl-55acee.svg?style=flat)](https://twitter.com/pritunl)

[Pritunl-Cloud-Builder](https://cloud.pritunl.com) is an automated installer
for Pritunl Cloud. Supports Oracle Linux 8, AlmaLinux 8 and Ubuntu 20.04.

# Usage

Run the commands below to download the builder and verify the checksum. Use
the option `--assume-yes` to assume yes to all prompts. Use the option
`--no-start` to not start the Pritunl Cloud service after the builder is
finished and instead start it on next boot.

```bash
wget https://github.com/pritunl/pritunl-cloud-builder/releases/download/1.0.2415.20/pritunl-builder
echo "ff2d9fcbd24b99a0ed3d6dbb92fbedf1331827680c73dbf79b481ba93bd63f46  pritunl-builder" | sha256sum -c -

chmod +x pritunl-builder
sudo ./pritunl-builder
```
