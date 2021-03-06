[![Build status](https://ci.appveyor.com/api/projects/status/1f1iyhlpqph68na2?svg=true)](https://ci.appveyor.com/project/MSFTCoreNet/msftnetworking-tools)
[![downloads](https://img.shields.io/powershellgallery/dt/Convert-LBFO2SET.svg?label=downloads)](https://www.powershellgallery.com/packages/MSFT.Network.Tools)


# MSFT.Network.Tools

Top-level manifest module containing network configuration tools by the Microsoft Core Networking Product Group at Microsoft

## :star: More by the Microsoft Core Networking team

Find more from the Core Networking team using the [MSFTNet](https://github.com/topics/msftnet) topic

# Installation

This module is part of MSFT.Network.Tools which can be installed using this command:
```Install-Module MSFT.Network.Tools```

To see all modules from the Microsoft Core Networking team, please use:
```Find-Module -Tag MSFTNet```

## Tools included in this module

### SoftwareTimestamping (MSFT.Network.Tools v0.0.0.10)

This module provides a powershell module and DSC Resource to enable software timestamping

### Data Center Bridging (MSFT.Network.Tools v0.0.0.1)

DSC PowerShell module intended to deploy Data Center Bridging settings using https://aka.ms/Validate-DCB

### VMNetworkAdapter (MSFT.Network.Tools v0.0.0.1)

DSC PowerShell module intended to deploy virtual NIC settings using https://aka.ms/Validate-DCB

### Start-CPUBurn (MSFT.Network.Tools v0.0.0.14)

Start-CPUBurn is a tool used to burn CPU cores.  This was originally used to test the dynamic queue scheduling algorithm that updates the RSSv2 indirection table for Dynamic VMMQ which was first shipped in Windows Server 2019.

### Convert-LBFO2SET (MSFT.Network.Tools v0.0.0.30)

Convert-LBFO2SET is a tool used to convert LBFO teams into a Switch Embedded Team.  For more information, please see [this blog](https://aka.ms/DownWithLBFO).

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
