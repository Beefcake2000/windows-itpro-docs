---
ms.localizationpriority: medium
ms.mktglfcycl: plan
description: Learn about which version of the IEAK 11 you should run, based on your license agreement.
author: pashort
ms.author: shortpatti
ms.manager: elizapo
ms.prod: ie11, ieak11
ms.assetid: 69d25451-08af-4db0-9daa-44ab272acc15
title: Determine the licensing version and features to use in IEAK 11 (Internet Explorer Administration Kit 11 for IT Pros)
ms.sitesec: library
ms.date: 05/02/2018
---


# Determine the licensing version and features to use in IEAK 11
In addition to the Software License Terms for the Internet Explorer Administration Kit 11 (IEAK 11) (IEAK 11, the "software"), these Guidelines further define how you may and may not use the software to create versions of Internet Explorer 11 with optional customizations (the "customized browser") for internal use and distribution in accordance with the IEAK 11 Software License Terms. IEAK 11 is for testing purposes only and is not intended to be used in a production environment.

During installation, you must pick a version of IEAK 11, either **External** or **Internal**, based on your license agreement. Your version selection decides the options you can chose, the steps you follow to deploy your Internet Explorer 11 package, and how you manage the browser after deployment.

-   **External Distribution as an Internet Service Provider (ISP), Internet Content Provider (ICP), or Developer.** If you are an ISP or an ICP, your license agreement also states that you must show the Internet Explorer logo on your packaging and promotional goods, as well as on your website.
    >[!IMPORTANT]
    >Original Equipment Manufacturers (OEMs) that install IEAK 11 as part of a Windows product, under an OEM license agreement with Microsoft, must use their appropriate Windows OEM Preinstallation document (OPD) as the guide for allowable customizations.

-   **Internal Distribution via a Corporate Intranet.** This version is for network admins that plan to directly deploy IE11 into a corporate environment.

## Available features by version

|Internal                                  |External                                  |
|------------------------------------------|------------------------------------------|
|Welcome screen                            |Welcome screen                            |
|File locations                            |File locations                            |
|Platform selection                        |Platform selection                        |
|Language selection                        |Language selection                        |
|Package type selection                    |Package type selection                    |
|Feature selection                         |Feature selection                         |
|Automatic Version Synchronization (AVS)   |Automatic Version Synchronization (AVS)   |
|Custom components                         |Custom components                         |
|Internal install                          |Not available                             |
|User experience                           |Not available                             |
|Browser user interface                    |Browser user interface                    |
|Search providers                          |Search providers                          |
|Important URLs – Home page and support    |Important URLs – Home page and support    |
|Accelerators                              |Accelerators                              |
|Favorites, Favorites bar, and feeds       |Favorites, Favorites bar, and feeds       |
|Browsing options                          |Not available                             |
|First Run wizard and Welcome page options |First Run wizard and Welcome page options |
|Connection manager                        |Connection manager                        |
|Connection settings                       |Connection settings                       |
|Automatic configuration                   |Not available                             |
|Proxy settings                            |Proxy settings                            |
|Security and privacy settings             |Not available                             |
|Add a root certificate                    |Not available                             |
|Programs                                  |Programs                                  |
|Additional settings                       |Not available                             |
|Wizard complete                           |Wizard complete                           |

## Customization guidelines

Two installation modes are available to you, depending on how you are planning to use the customized browser created with the software. Each mode requires a separate installation of the software.

-   **External Distribution**  
    This mode is available to anyone who wants to create a customized browser for distribution outside their company (for example, websites, magazines, retailers, non-profit organizations, independent hardware vendors, independent software vendors, Internet service providers, Internet content providers, software developers, and marketers).

-   **Internal Distribution**  
    This mode is available to companies for the creation and distribution of a customized browser only to their employees over a corporate intranet.

The table below identifies which customizations you may or may not perform based on the mode you selected.

| **Feature Name**      | **External Distribution**    | **Internal Distribution**     |
|---------------------------------|----------------------|-------------------|
| **Custom Components**     | Yes       | Yes    |
| **Title Bar**   | Yes   | Yes     |
| **Favorites**   | One folder, containing any number of links.  | Any number of folders/links.   |
| **Search Provider URLs** | Yes   | Yes   |
| **Search Guide URL** | No  | Yes   |
| **Online Support URL** | Yes  | Yes    |
| **Web Slice**  | Suggested maximum five Web Slices.   | Any number of Web Slices.    |
| **Accelerator**  | Search provider Accelerator must be the same as the search provider set for the Search Toolbox. We recommend that Any number of Accelerators/Accelerator Categories. Feature Name External Internal Accelerator category not exceed seven total categories, and each Accelerator category must be unique. We recommend each Accelerator category not have more than two Accelerators. The Accelerator display name should follow the syntax of verb + noun, such as "Map with Bing." | Any number of Accelerators/Accelerator Categories. |
| **Homepage URLs**  | Can add a maximum of three.  | Unlimited.  |
| **First Run Wizard and Welcome Page Options** | Cannot remove Internet Explorer 11 First Run wizard. Can customize **Welcome** page.    | Customizable.   |
| **RSS Feeds** | One folder, containing any number of links.   | Any number of folders/links.  |
| **Browsing Options**   | No    | Yes   |
| **Security and Privacy Settings**  | No  | Can add any number of sites.   |
| **Corporate Options** (Latest Updates, Default Browser, Uninstall Info, Additional Settings) | No   | Yes   |
| **User Experience** (Setup/Restart) | No   | Yes   |
| **User Agent String** | Yes   | Yes  |
| **Compatibility View**  | Yes   | Yes  |
| **Connection Settings and Manage**  | Yes  | Yes  |


Support for some of the Internet Explorer settings on the wizard pages varies depending on your target operating system. For more information, see [Internet Explorer Customization Wizard 11 options](https://docs.microsoft.com/internet-explorer/ie11-ieak/ieak11-wizard-custom-options).

## Distribution guidelines

Two installation modes are available to you, depending on how you are planning to use the customized browser created with the software. Each mode requires a separate installation of the software.

-   **External Distribution**  
    You shall use commercially reasonable efforts to maintain the quality of (i) any non-Microsoft software distributed with Internet Explorer 11, and (ii) any media used for distribution (for example, optical media, flash drives), at a level that meets or exceeds the highest industry standards. If you distribute add-ons with Internet Explorer 11, those add-ons must comply with the [!INCLUDE [microsoft-browser-extension-policy-include](../../edge/microsoft-browser-extension-policy-include.md)].

-   **Internal Distribution - corporate intranet**  
    The software is solely for use by your employees within your company's organization and affiliated companies through your corporate intranet. Neither you nor any of your employees may permit redistribution of the software to or for use by third parties other than for third parties such as consultants, contractors, and temporary staff accessing your corporate intranet.