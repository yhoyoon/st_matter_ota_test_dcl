# Smartthings Matter OTA Software Images Repository

Hosts Smartthings OTA matter software images for testing. This repository is being referenced by Hub V3 to download software image artifacts.

## Usage

When testing Matter OTA, it is necessary to provide software images that are to be downloaded to a device.
It is first necessary to enter a new set of software images into the system, as described below.

### Add Model Software Versions using the HLA EP

See [Add Model Software Versions](https://smartthings.atlassian.net/wiki/spaces/CHIP/pages/2710405187/Add+Model+Software+Versions+using+the+HLA+EP)    for detailed information on how to post a set of software versions using the HLA dcl/add_model_sw_versions API.

This interface will trigger a download of software images from this repository.