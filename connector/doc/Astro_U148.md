---
uid: Connector_help_Astro_U148
---

# Astro U148

## About

This connector can be used with the following devices: **Astro U144**, **U148** and **U149**. It allows you to gather and view information from these devices as well as configure them.

This connector uses **HTTP** to monitor the device. It also uses an **SNMP** interface to receive traps from the device.

## Key Features

- **Multiplexer Matrices**: Crosspoints can be made on matrices for CAM MUX and TX MUX.

- **Controller Alarm Forwarding**: Elements can be configured to enable or disable alarm forwarding to the Astro U100 Controller.

- **Service Selection**: It's possible to assign a service to a multiplexer and to remove a service from a multiplexer.

- **Software Updates**: The connector allows to upload a firmware archive from the local disk of the DMA.

## Use Cases

### Astro U100 Controller

**Challenge**: Communication through Astro U100 Controller proxy.

**Solution**: A Communication Type parameter set to U100C Proxy allows to send the requests to the Astro U100 Controller, which will forward them to the correct Astro module.

**Benefit**: Minimal DataMiner element configuration required to monitor multiple modules.

## Technical Reference

### Prerequisites

- **DataMiner Main Release 10.4.0** or higher.

- **Astro API access**: web interface credentials are required for authentication.

> [!NOTE]
> For detailed technical information, refer to our [technical documentation](xref:Connector_help_Astro_U148_Technical).