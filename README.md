# Main Index Repo for Linking to PoC Repos


[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)](#contributing)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/Dell-Networking/PoC-Index/blob/main/LICENSE.md)
[![GitHub issues](https://img.shields.io/github/issues/Dell-Networking/PoC-Index)](https://github.com/Dell-Networking/PoC-Index/issues)

Built and maintained by [Ben Goldstone](https://github.com/benjamingoldstone/) and [Contributors](https://github.com/Dell-Networking/PoC-Index/graphs/contributors)

------------------

## Description

This repo is simply for linking to all the proof-of-concept repos built out pertaining to SONiC and Dell Enterprise SONiC. See links below.

Note that the 'status' field should be one of the following:
  * Planning - in planning stage, no code ready to share
  * In Progress - being implemented, some code available but not complete or validated
  * Complete, not validated - Code complete but not yet validated
  * Complete, validated - Code complete for at least one release and has been validated to be reproducible per requirements section

## Accessing Dell Enterprise SONiC

Note that to gain access to a virtual version of Dell Enterprise SONiC (if required for a PoC), you'll need to reach out to your Dell sales rep. who can provide access as required.

## Proof-of-Concept Repos

| Name                      | Description                                                                                                       | Status                  | Note                             | Repo Link                                                                                                          |                
|---------------------------|-------------------------------------------------------------------------------------------------------------------|-------------------------|----------------------------------|--------------------------------------------------------------------------------------------------------------------|
| Template                  | Template repo to get folks started building out PoC repos                                                         | In Progress             | No validation currently required | [PoC SONiC Template](https://github.com/Dell-Networking/PoC-SONiC-template)                                        |
| AWS SM                    | How to use AWS Secrets Manager for securing creds + create VLAN with creds & API calls                            | Complete, Not Validated |                                  | [PoC DES Python AWS SM Automation](https://github.com/Dell-Networking/PoC-DES-Python-AWS-SM-Automation)            |
| ZTP Intro                 | How to use ZTP within Dell Enterprise SONiC                                                                       | In Progress             |                                  | [PoC DES ZTP](https://github.com/Dell-Networking/PoC-DES-ZTP)                                                      |
| EVE-NG                    | Get Dell Enterprise SONiC up and running within an EVE-NG environment                                             | In Progress             |                                  | [PoC DES EVE-NG](https://github.com/Dell-Networking/PoC-DES-EVE-NG)                                                |
| DCI Multisite             | How to leverage DCI Multisite with Dell Enterprise SONiC                                                          | In Progress             |                                  | [PoC DCI Multisite](https://github.com/Dell-Networking/PoC-DCI-Multisite-DES)                                      |
| Automated Backup          | Automate backups of config_db.json files with Dell Enterprise SONiC                                               | In Progress             |                                  | [PoC Automated Backup](https://github.com/Dell-Networking/PoC-DES-Automated-Backup)                                |
| Elastic with DES          | Set up Elastic tools to support monitoring of Dell Enterprise SONiC devices                                       | In Progress             |                                  | [PoC Elastic with DES](https://github.com/Dell-Networking/PoC-Elastic-with-DES)                                    |
| Config replace with DES   | Atomic config replace with Dell Enterprise SONiC via API and gNMI                                                 | In Progress             |                                  | [PoC Config Replace](https://github.com/Dell-Networking/PoC-DES-Config-Replace)                                    |
| ONIE to DES               | Automate installation of Dell Enterprise SONiC for devices running ONIE or OS10                                   | In Progress             |                                  | [PoC ONIE to DES](https://github.com/Dell-Networking/PoC-ONIE-to-DES)                                              |
| Network Function Chaining | Network function chaining with Dell Enterprise SONiC as supporting fabric                                         | In Progress             |                                  | [PoC Network Function Chaining](https://github.com/Dell-Networking/PoC-Network-Function-Chaining-with-DES)         |
| Telegraf-Grafana          | How to leverage InfluxDB + Grafana + Telegraf for streaming telemetry out of Dell Enterprise SONiC switches       | In Progress             |                                  | [PoC DES Grafana + Telegraf](https://github.com/Dell-Networking/PoC-DES-plus-InfluxDB-Grafana-Telegraf-Monitoring) |
| CI/CD Intro               | Basics around getting started with CI/CD tooling to build a pipeline for automating against Dell Enterprise SONiC | In Progress             |                                  | [PoC DES CI/CD Intro](https://github.com/Dell-Networking/PoC-DES-CICD-Intro)                                       |
| USB ZTP                   | How to utilize a USB stick + ZTP to provision switches                                                            | In Progress             |                                  | [PoC USB ZTP](https://github.com/Dell-Networking/PoC-DES-ZTP-USB)                                                  |
| TPCM Intro                | Run third-party containers on Dell Enterprise SONiC with Third Party Container Manager                            | Planning                |                                  | [PoC TPCM Intro](https://github.com/Dell-Networking/PoC-DES-TPCM-Intro)                                            |
| ZTP + Nautobot            | How to leverage the Dell Enterprise SONiC ZTP process to auto-register devices in Netbox / Nautobot               | Planning                |                                  | [PoC ZTP Nautobot Autoregister](https://github.com/Dell-Networking/PoC-DES-ZTP-Nautobot)                           |

## Contributing

We welcome contributions to this library of proof-of-concepts. If you'd like to contribute, please reference our [CONTRIBUTING](https://github.com/Dell-Networking/PoC-Index/blob/main/CONTRIBUTING.md) guide