---
title: Wlan Test - Wlan Device Capabilities Check - (WoW64 for ARM64)
description: Wlan Test - Wlan Device Capabilities Check - (WoW64 for ARM64)
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 3bdf4d9d-59d4-42ef-933d-1655a83b58dc
author: sapaetsc
ms.author: sapaetsc
ms.date: 10/15/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-oem
---

# <span id="p_hlk_test.efdacab3-52bc-42a0-81ae-0cad900db51f"></span>Wlan Test - Wlan Device Capabilities Check - (WoW64 for ARM64)


This automated test checks to make sure the WLAN device is properly reporting its capabilities to windows

## Test details
|||
|---|---|
| **Specifications**  | <ul><li>Device.Network.WLAN.SupportConnectionToAP.ConnectionToAP</li></ul> |  
| **Platforms**   | <ul><li>Windows 10, client editions (ARM64)</li><li>Windows 10, mobile edition (ARM64)</li></ul> |
| **Supported Releases** | <ul><li>Windows 10</li><li>Windows 10, version 1511</li><li>Windows 10, version 1607</li><li>Windows 10, version 1703</li><li>Windows 10, version 1709</li></ul> |
|**Expected run time (in minutes)**| 1 |
|**Category**| Development |
|**Timeout (in minutes)**| 5 |
|**Requires reboot**| false |
|**Requires special configuration**| true |
|**Type**| automatic |

 

## <span id="Additional_documentation"></span><span id="additional_documentation"></span><span id="ADDITIONAL_DOCUMENTATION"></span>Additional documentation


Tests in this feature area might have additional documentation, including prerequisites, setup, and troubleshooting information, that can be found in the following topic(s):

-   [Device.Network additional documentation](device-network-additional-documentation.md)

## <span id="Running_the_test"></span><span id="running_the_test"></span><span id="RUNNING_THE_TEST"></span>Running the test


This test is only valid on systems with a Wireless LAN adapter. This test does the following:

-   Queries the system for the adapter capabilities

## <span id="Troubleshooting"></span><span id="troubleshooting"></span><span id="TROUBLESHOOTING"></span>Troubleshooting


For generic troubleshooting of HLK test failures, see [Troubleshooting Windows HLK Test Failures](..\user\troubleshooting-windows-hlk-test-failures.md).


## <span id="More_information"></span><span id="more_information"></span><span id="MORE_INFORMATION"></span>More information


### <span id="Parameters"></span><span id="parameters"></span><span id="PARAMETERS"></span>Parameters

| Parameter name        | Parameter description          |
|-----------------------|--------------------------------|
| **EnableTracing**     | Enable Tracing                 |
| **queryTestDeviceID** | Device id of device under test |

 

 

 






