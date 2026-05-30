# Security Policy


## Purpose
This repository is public. This policy defines what information is permitted in this repository, the standards applied before any commit, and the process for handling exposures.


## Sensitive Information
The following are never committed to this repository under any circumstances:

- Passwords, passphrases, or any authentication credentials
- API keys, tokens, or secrets of any kind
- Private keys or certificates
- The WAN IP address assigned to the pfSense firewall by the host's ISP, as this maps to a physical location

All other IP addresses in this lab are private, non-routable RFC 1918 space and may appear freely in documentation, diagrams, and screenshots.


## Pre-Commit Reviewing
Every commit is manually reviewed before being pushed. This review confirms:

- The affected files are read in full
- No credentials, keys, or tokens are present in any affected file
- No WAN IP address appears in any staged file
- Screenshots contain no sensitive values


## Reporting Exposures
If a sensitive value is found in this repository, open a GitHub Issue labeled
`security`. Identify the file and line number. Do not include the sensitive
value in the issue body. The issue will be addressed as a priority above all
other lab work.
