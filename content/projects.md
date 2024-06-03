+++
title = 'Projects'
date = 2024-06-02T00:00:00+00:00
draft = false
+++

___

Table of contents

- [Sherlock](#sherlock)
- [svcman](#svcman)
- [Windex](#windex)

## Sherlock

https://github.com/sherlock-project/sherlock

Sherlock is the **#1** most starred, trafficked, and forked OSINT tool available on GitHub, allowing researchers and investigators to hunt down social media accounts by username across 400+ curated platforms and websites.

Sherlock has been packaged for penetration testing distributions [Kali][ext-kali] and [BlackArch][ext-blackarch], along with brand new officially supported images on [DockerHub][ext-dockerhub] and [PyPI][ext-pypi]. We have community-supported packaged available for [Debian][ext-debian], [Homebrew][ext-homebrew], PureOS, Raspbian, NixOS, and others.

_[Siddharth Dushantha][ext-sdushantha] is the original author of the project, where I am now a primary maintainer and developer alongside._

**Focal points:** Python / Regression / Bot-detection circumvention / Packaging


## svcman

https://github.com/svcman/svcman

svcman (Service Manager) is a current work in progress.

Working to develop the first truly user friendly graphical service monitor + manager for systemd to be available via the official respositories.

**Focal points:** C++ / Qt / CMake / Linux kernel / systemd / dbus


## Windex

https://github.com/ppfeister/Windex

Windex can be used to clean Windows of as much bloat and telemetry as possible without impeding normal function. Windex was built with **stable** and **easily auditable** virtualization in mind, and we're beginning to expand use internally to workstations as well, with a noticeable quality of life improvement for those users.

While other tools exist to perform similar jobs... none met the auditability and transparency needs of our environment. Windex has been written in a way to favor native playbooks and modules, allowing for easy review and extension by sysadmins.

Windex has **zero** dependency on additional software (unlike Atlas and others), and can be ran through most PSA and RMM solutions without issue. Being written in PowerShell, it can be ran on fresh builds without any additional configuration at the endpoint.

Despite PowerShell not having native support for YAML, Windex can be used to parse and execute Ansible-style playbooks, allowing for unbelievably easy extension and customization.

**Focal points:** PowerShell / Automation / Windows kernel


<!-- Outbound -->

[ext-kali]: https://www.kali.org/
[ext-blackarch]: https://blackarch.org/
[ext-dockerhub]: https://hub.docker.com/r/sherlock/sherlock
[ext-pypi]: https://pypi.org/project/sherlock-project/
[ext-debian]: https://packages.debian.org/sid/sherlock
[ext-homebrew]: https://formulae.brew.sh/formula/sherlock
[ext-sdushantha]: https://sdushantha.github.io/