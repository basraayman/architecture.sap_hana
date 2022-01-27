# Platform Specific Architecture for Nutanix

Description

<!-- TOC -->

- [Platform Specific Architecture for Nutanix](#platform-specific-architecture-for-nutanix)
  - [Nutanix: Overall Architecture](#nutanix-cloud-overall-architecture)
  - [Nutanix: Basic Architecture](#nutanix-cloud-basic-architecture)
    - [Nutanix: Storage Configurations](#nutanix-cloud-storage-configurations)
  - [Nutanix: Virtual Hostname/IP](#nutanix-cloud-virtual-hostnameip)
  - [Nutanix: High Availability](#nutanix-cloud-high-availability)
  - [Nutanix: Disaster Recovery](#nutanix-cloud-disaster-recovery)
  - [Nutanix: Data Tiering Options](#nutanix-cloud-data-tiering-options)
  - [Nutanix: XSA](#nutanix-cloud-xsa)

<!-- /TOC -->

## Nutanix: Overall Architecture

- need picture here

- some general text
  - some basic links to Nutanix reference architectures and documentation

## Nutanix: Basic Architecture

Link to generic content: [Module: Basic Architecture](../generic_architecture/module_basic_architecture.md#module-basic-architecture)

- supported instance types
- description of single node implementation (storage) + picture
- description of scale-out implementations (storage) + picture
- are subnets are stretched across AZs?
- links to Nutanix documentation

### Nutanix: Storage Configurations

- visualization of storage for Nutanix

## Nutanix: Virtual Hostname/IP

Link to generic content: [Module: Virtual Hostname/IP](../generic_architecture/module_virtual_hostname.md#module-virtual-hostnameip)

- how to implement virtual IP - maybe additional network interface?
- reference to Instance Move and how to execute Nutanix specific steps (move network interface?)

## Nutanix: High Availability

Link to generic content: [Module: High Availability](../generic_architecture/module_high_availability.md#module-high-availability)

- link to list of Availability Zones in Nutanix
- comment that it is important to measure AZ latency via niping (I will add this as new section in general part)
- fencing mechanism (options, recommendation)
- how to implement cluster IP ?
  - provide some details
- links to Nutanix/SUSE/RHEL documentation
- how to modify cluster to have active/active
- how to modify cluster to have tenant specific cluster IPs
- anything else?

## Nutanix: Disaster Recovery

Link to generic content: [Module: Disaster Recovery](../generic_architecture/module_disaster_recovery.md#module-disaster-recovery)

- anything to consider? bandwidth?

## Nutanix: Data Tiering Options

Link to generic content: [Module: Data Tiering Options](../generic_architecture/module_data_tiering.md#module-data-tiering-options)

- what is supported what is not (matrix)
- links to Nutanix documentation
- modified pictures of storage setup (if required)

## Nutanix: XSA

Link to generic content: [Module: SAP XSA](../generic_architecture/module_xsa.md#module-sap-xsa)

- I think there is nothing infrastructure specific
