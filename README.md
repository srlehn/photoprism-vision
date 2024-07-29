PhotoPrism: Computer Vision Models
==================================

[![License: Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-454377.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Documentation](https://img.shields.io/badge/read-the%20docs-4d6a91.svg)](https://docs.photoprism.app/developer-guide/)
[![Community Chat](https://img.shields.io/badge/chat-on%20gitter-4d6a91.svg)](https://link.photoprism.app/chat)
[![GitHub Discussions](https://img.shields.io/badge/ask-%20on%20github-4d6a91.svg)](https://link.photoprism.app/discussions)
[![Bluesky Social](https://dl.photoprism.app/img/badges/badge-bluesky.svg)](https://bsky.app/profile/photoprism.app)
[![Mastodon](https://dl.photoprism.app/img/badges/badge-floss-social.svg)](https://floss.social/@photoprism)

This repository contains supplementary computer vision models that can be used with PhotoPrism. The services provide a REST API that accepts either a POST or GET request with an image URL and returns a matching caption in response. The currently integrated models for this, each with its own endpoint, are *kosmos-2*, *blip-image-captioning large* and *vit-gpt2-image-captioning*.

## Installing Build Dependencies

Before installing the Python dependencies, please make sure that you have [Git](https://git-scm.com/downloads) and [Python 3.12+ (incl. pip)](https://www.python.org/downloads/) installed on your system, e.g. by running the following command on Ubuntu/Debian Linux:

```
sudo apt-get install -y git python3 python3-pip python3-venv python3-wheel
```

You can then install the required libraries in a virtual environment by either using the Makefiles we provide (i.e. run `make` in the main project directory or a subdirectory) or by manually running the following commands in a service directory, for example:

```bash
cd describe
python3 -m venv ./venv
. ./venv/bin/activate
./venv/bin/pip install --disable-pip-version-check --upgrade pip
./venv/bin/pip install --disable-pip-version-check -r requirements.txt
```

## Contributors

We would like to thank everyone involved, especially [Aatif Dawawala](https://github.com/Aatif-Dawawala) who got things rolling and contributed much of the initial code:

- [Aatif Dawawala](https://github.com/Aatif-Dawawala)
- [Niaz Faridani-Rad](https://github.com/derneuere)

[Learn more ›](https://github.com/photoprism/photoprism-vision/graphs/contributors)
 
## Submitting Pull Requests

Follow our [step-by-step guide](https://docs.photoprism.app/developer-guide/pull-requests) to learn how to submit new features, bug fixes, and documentation enhancements.

[Learn more ›](https://docs.photoprism.app/developer-guide/pull-requests)

## License and Disclaimer

The files in this repository are licensed under the [Apache License, Version 2.0](https://docs.photoprism.app/license/apache/) (the “License”).

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

[Learn more ›](https://docs.photoprism.app/license/apache/)

----

*Copyright © 2024 [PhotoPrism UG](https://www.photoprism.app/contact). By using the software and services we provide, you agree to our [Terms of Service](https://www.photoprism.app/terms), [Privacy Policy](https://www.photoprism.app/privacy), and [Code of Conduct](https://www.photoprism.app/code-of-conduct). PhotoPrism® is a [registered trademark](https://www.photoprism.app/trademark).*
