# girlsfrontline-resources-extract

This repo was created to document how to extract the resources of the game **Girls' Front line** used in [girlsfrontline-resources](https://github.com/QZLin/girlsfrontline-resources-extract) , and to share the script used for this.

Please use GitHub Issue for suggestions and bug reports. If possible, we will respond within 24 hours.

PR is always welcome. I also added a lot of comments. I'd be grateful if you could help me since I'm mainly in high school.

## Requirements

`Python 3.6 (64-bit)` or higher. `32-bit` is not guaranteed.

The following additional packages are required to run. For extracting audio [hcapy](https://github.com/krepe-suZette/hcapy) for image extraction and [pyetc](https://github.com/krepe-suZette/pyetc) are not registered in pypi and must be installed manually.

- numpy
- opencv-python
- configparser
- requests
- [unitypack](https://github.com/HearthSim/UnityPack)
- [hcapy](https://github.com/krepe-suZette/hcapy)
- [pyetc](https://github.com/krepe-suZette/pyetc)

## Process

- [x] Register the repo
- [x] Create an AssetBundle description
- [x] Implement ab file processing function
- [x] acb file processing function implementation
- [x] Icon creation function
- [x] logging
- [x] Ability to change file output path without touching code
- [x] Clear descriptions on GitHub Wiki
- [x] Error handling function

## Wiki

We will be writing all the guides on our [GitHub Wiki.](https://github.com/36base/girlsfrontline-resources-extract/wiki) Please refer.
