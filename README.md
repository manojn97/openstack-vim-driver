[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Build Status](https://travis-ci.com/accanto-systems/openstack-vim-driver.svg?branch=master)](https://travis-ci.com/accanto-systems/openstack-vim-driver)

# Openstack VIM Driver

A VIM driver implementation that manages infrastructure with Openstack. Create/delete operations are managed with Heat, by first translating the TOSCA template for the infrastructure into a Heat template.

Currently the only external infrastructure that can be returned by the "find infrastructure" API is Networks.

Please read the following guides to get started with the VIM Driver:

## Developer

- [Developer Docs](./developer_docs/index.md) - docs for developers to install the driver from source or run the unit tests

## User

- [Kubernetes Install](./docs/install_with_helm.md) - Install the driver on Kubernetes with Helm
- [Deployment Locations](./docs/deployment_locations.md) - details the properties expected by this driver on a Deployment Location
- [Supported Tosca](./docs/supported_tosca.md) - details on supported infrastructure types
- [APIs](./docs/apis.md) - details additional APIs on this driver not expected by a VIM driver
