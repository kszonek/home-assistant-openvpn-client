# OpenVPN add-on for Home Assistant

The OpenVPN is an open source Virtual Private Network (VPN) project. It creates secure connections over the Internet using a custom security protocol that utilizes SSL/TLS. This community-supported OSS (Open Source Software) project, using a GPL license, is supported by many OpenVPN Inc. developers and contributors as well as the extended OpenVPN community.

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fkszonek%2Fhome-assistant-openvpn-client)

## Add-ons

This repository contains add-on:

### [OpenVPN Client](./openvpn-client)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

_Example add-on to use as a blueprint for new add-ons._

<!--
Notes to developers after forking or using the github template feature:
  - While developing comment out the 'image' key from 'example/config.yaml' to make the supervisor build the addon
  - Remember to put this back when pushing up your changes.
  - Make sure you adjust the 'version' key in 'example/config.yaml' when you do that.
  - Make sure you update 'example/CHANGELOG.md' when you do that.
  - The first time this runs you might need to adjust the image configuration on github container registry to make it public
  - You may also need to adjust the github Actions configuration (Settings > Actions > General > Workflow > Read & Write)
  - Adjust the 'image' key in 'example/config.yaml' so it points to your username instead of 'home-assistant'.
  - Adjust all keys/url's that points to 'home-assistant' to now point to your user/fork.
  - Share your repository on the forums https://community.home-assistant.io/c/projects/9
-->

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg

root@core-ssh.local.hass.io

