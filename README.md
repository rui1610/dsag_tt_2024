# DSAG Technologie Tage 2024 Hamburg

This repository provides the code behind the **Terraform demo** for the session **V090: Infrastructure as code in der SAP Business Technology Platform und erste Kundenerfahrungen von Freudenberg** (see [event page](https://dsagtechtage.plazz.net/)).

## The Terraform scripts

The Terraform scripts are split into two folders:

- [sap_build_apps](sap_build_apps): this folder contains the main Terraform script to setup the SAP Build Apps used in the demo. The script is using some additional resources, that are in the [modules](modules) folder.
- [modules](modules): this folder contains modules used by the [sap_build_apps](sap_build_apps script).

## Start today

| [Get started with a tutorial](https://developers.sap.com/tutorials/btp-terraform-get-started.html) |  [Try out sample use cases](https://github.com/SAP-samples/btp-terraform-samples) | [Read the documentation](https://registry.terraform.io/providers/SAP/btp/latest/docs) |
| --------------------------- | ------------------------ | --------------------- |
| ![Tutorial at developers.sap.com](pictures/qrcode1.svg) | ![Try out sample use cases](pictures/qrcode2.svg) | ![TRead the documentation](pictures/qrcode3.svg) |
