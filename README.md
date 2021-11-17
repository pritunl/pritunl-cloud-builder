# pritunl-cloud-builder

[![github](https://img.shields.io/badge/github-pritunl-11bdc2.svg?style=flat)](https://github.com/pritunl)
[![twitter](https://img.shields.io/badge/twitter-pritunl-55acee.svg?style=flat)](https://twitter.com/pritunl)

[Pritunl-Cloud-Builder](https://cloud.pritunl.com) is an automated installer
for Pritunl Cloud

# Usage

Run the commands below to download the builder and verify the checksum. Use
the option `--assume-yes` to assume yes to all prompts. Use the option
`--no-start` to not start the Pritunl Cloud service after the builder is
finished and instead start it on next boot.

```bash
wget https://github.com/pritunl/pritunl-cloud-builder/releases/download/1.0.2185.86/pritunl-builder
echo "f253812750e34acec1289f4b23d8d9e933c3d1664df1c667c76c5b0e6f88a8ba  pritunl-builder" | sha256sum -c -
chmod +x pritunl-builder
sudo ./pritunl-builder
```
