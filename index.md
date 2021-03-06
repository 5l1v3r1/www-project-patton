---

layout: col-sidebar
title: OWASP Patton
tags: examples
type: tool
level: 2

---
![Patton](/assets/images/patton-logo.png)

[![GitHub Releases](https://img.shields.io/github/v/release/BBVA/kapow?include_prereleases)](https://github.com/BBVA/patton/releases)

## Patton - The vulnerability knowledge base

Patton is a set of tools for helping admins and security auditors to search for
vulnerabilities in software components and computer systems.

Patton contains, at this moment, the tools needed to analyze vulnerabilities on
Ubuntu and Debian systems and we are currently working on increasing the
targets to include Redhat systems and Python dependencies.

## Description

Searching for vulnerabilities is a really hard task. Vulnerabilities databases
have they own format and they index vulnerabilities in a way that makes
difficult to match with the package names you install in your systems or with
the libraries your software depends on.

Patton pre-cooks a vulnerabilities database, this database is really small to
ease downloading and contains only the needed data to allow the match of the
vulnerable component.

Patton contains a series of small epecialized tools that are able of making the
match between the vulnerability and the software package or library and offers
a single interface to invoke all the tools in a consistent way.

## Contribution

Everyone is welcome and encouraged to participate in our [Project](https://github.com/BBVA/patton).

## Licensing

This project is distributed under [Apache 2 license](https://github.com/bbva/patton/raw/master/LICENSE).
