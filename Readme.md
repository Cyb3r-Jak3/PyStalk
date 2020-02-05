# PyStalk

[![GitHub](https://img.shields.io/github/license/Cyb3r-Jak3/pystalk?style=flat)](https://github.com/Cyb3r-Jak3/PyStalk/blob/master/LICENSE) ![Gitlab pipeline status (branch)](https://img.shields.io/gitlab/pipeline/Cyb3r-Jak3/pystalk/master?label=Build&style=flat)  

[![Test Coverage](https://api.codeclimate.com/v1/badges/896b338971314c13a56e/test_coverage)](https://codeclimate.com/github/Cyb3r-Jak3/PyStalk/test_coverage) [![Maintainability](https://api.codeclimate.com/v1/badges/896b338971314c13a56e/maintainability)](https://codeclimate.com/github/Cyb3r-Jak3/PyStalk/maintainability)  
[![CodeFactor](https://www.codefactor.io/repository/github/cyb3r-jak3/pystalk/badge)](https://www.codefactor.io/repository/github/cyb3r-jak3/pystalk)

## About

PyStalk is a tool that can be used to generate graphs from the metadata of JPEG, TIFF images. More formats are supported but untested.
It currently creates graphs for:

- GPS coordinates (map)
- Focal Length, Camera model, Camera manufacturer, Producer information (Pie Chart)
- Timestamp information (Chart)

Examples photos from [ianare/exif-samples](https://github.com/ianare/exif-samples/tree/master/jpg/gps), [exiftool](https://owl.phy.queensu.ca/~phil/exiftool/sample_images.html), [drewmpales/metadata-extractor-images](https://github.com/drewnoakes/metadata-extractor-images).

All development is done on GitLab and pushed to GitHub.
Please open issues on [GitLab](https://gitlab.com/Cyb3r-Jak3/PyStalk/issues) or if you do not have a GitLab account, send me an email and I will open an issue.

## How to use

```bash
git clone https://github.com/Cyb3r-Jak3/pystalk
cd pystalk
pip install -r requirements.txt
python PyStalk.py <Path to files>
#i.e. python PyStalk.py tests/ExamplePhotos/
```

### TODO

- Better web layout
  - Better sized graphs
- Ability to choose the graphs used
- Possible PyPi package (??)
- Possible web scrapper for images
  - Or import from a current one

## Disclaimer

This is for educational/proof of concept purposes only. What you do with this program is **your** responsibility.

[![DeepSource](https://static.deepsource.io/deepsource-badge-light.svg)](https://deepsource.io/gl/Cyb3r-Jak3/PyStalk/?ref=repository-badge)
