# pritunl-cloud-builder

[![github](https://img.shields.io/badge/github-pritunl-11bdc2.svg?style=flat)](https://github.com/pritunl)
[![twitter](https://img.shields.io/badge/twitter-pritunl-55acee.svg?style=flat)](https://twitter.com/pritunl)

[Pritunl-Cloud-Builder](https://cloud.pritunl.com) is an automated installer
for Pritunl Cloud

# Usage

Run the commands below to download the builder and verify the checksum.

```bash
wget https://github.com/pritunl/pritunl/releases/download/1.0.2142.34/pritunl-builder
echo "37818a168802f74475a012bfa8a48023723ba6b83126337e59f81fd932cb3d21  pritunl-builder" | sha256sum -c -
sudo ./pritunl-builder
```
