# Zoom Windows SDK C# Wrapper <span align="center"><img src="https://s3-us-west-1.amazonaws.com/sdk.zoom.us/Community-Project.png" width="200px" max-height="100px" style="margin:auto;"/></span>

**Note: Zoom does not actively enhance the interfaces in the C# wrapper. This wrapper is provided as a reference and will not be actively supported by Zoom.**

<div align="center">
<img src="https://s3.amazonaws.com/user-content.stoplight.io/8987/1541013063688" width="400px" max-height="400px" style="margin:auto;"/>
</div>

## Table of Contents
- [:rotating_light: Announcement :rotating_light:](#rotating_light-announcement-rotating_light)   
- [Latest SDK Notifications](#latest-sdk-notifications)   
- [Full Documentation && Community Support](#full-documentation-community-support)   
- [Disclaimer](#disclaimer)   
- [Getting Started](#getting-started)   
  - [Prerequisites](#prerequisites)   
  - [Installing](#installing)   
- [Documentation](#documentation)   
- [Versioning](#versioning)   
- [Change log](#change-log)   
- [Frequently Asked Questions (FAQ)](#frequently-asked-questions-faq)   
- [Support](#support)   
- [License](#license)   
- [Contributiors](#contributiors)   
- [Acknowledgments](#acknowledgments)   

## :rotating_light: Announcement :rotating_light:
To align with Zoom’s [recent announcement](https://blog.zoom.us/wordpress/2020/04/22/zoom-hits-milestone-on-90-day-security-plan-releases-zoom-5-0/) pertaining to our security initiative, Zoom Client SDKs have added **AES 256-bit GCM encryption** support, which provides more protection for meeting data and greater resistance to tampering. **The system-wide account enablement of AES 256-bit GCM encryption will take place on June 01, 2020.** You are **strongly recommended** to start the required upgrade to this latest version 4.6.21666.0428 at your earliest convenience. Please note that any Client SDK versions below 4.6.21666.0428 will **no longer be operational** from June 01.

> If you would like to test the latest SDK with AES 256-bit GCM encryption meeting before 05/30, you may:
> 1. Download the latest version of Zoom client: https://zoom.us/download
> 2. Visit https://zoom.us/testgcm and launch a GCM enabled meeting with your Zoom client, you will see a Green Shield icon that indicates the GCM encryption is enabled
> 3. Use SDK to join this meeting


## Latest SDK Notifications
1. Our brand new [Zoom Developer Community Forum](https://devforum.zoom.us/) is now online!!! Check it out! We are here to help! :D

## Full Documentation && Community Support
You can find the full Zoom Windows SDK C# wrapper documentation and the community support forum here:
<div align="center">
   <a target="_blank" href="https://marketplace.zoom.us/docs/sdk/native-sdks/windows/c-sharp-wrapper" style="text-decoration:none">
   <img src="https://s3-us-west-1.amazonaws.com/sdk.zoom.us/Doc-button.png" width="350px" max-height="350px" style="margin:1vh 1vw;"/>
   </a>
   <a target="_blank" href="https://devforum.zoom.us/c/desktop-sdk" style="text-decoration:none">
   <img src="https://s3-us-west-1.amazonaws.com/sdk.zoom.us/Forum-button.png" width="350px" max-height="350px" style="margin:1vh 1vw;"/>
   </a>
</div>

## Disclaimer

**Please be aware that all hard-coded variables and constants shown in the documentation and in the demo, such as Zoom Token, Zoom Access, Token, etc., are ONLY FOR DEMO AND TESTING PURPOSES. We STRONGLY DISCOURAGE the way of HARDCODING any Zoom Credentials (username, password, API Keys & secrets, SDK keys & secrets, etc.) or any Personal Identifiable Information (PII) inside your application. WE DON’T MAKE ANY COMMITMENTS ABOUT ANY LOSS CAUSED BY HARD-CODING CREDENTIALS OR SENSITIVE INFORMATION INSIDE YOUR APP WHEN DEVELOPING WITH OUR SDK**.

## Getting Started

The following instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
* For detailed instructions, please refer to our documentation website: [https://marketplace.zoom.us/docs/sdk/native-sdks/windows/c-sharp-wrapper](https://marketplace.zoom.us/docs/sdk/native-sdks/windows/c-sharp-wrapper);
* If you need support or assistance, please visit our [Zoom Developer Community Forum](https://devforum.zoom.us/);

### Prerequisites

Before you try out our SDK, you would need the following to get started:

* **A Zoom Account**: If you do not have one, you can sign up at [https://zoom.us/signup](https://zoom.us/signup).
  * Once you have your Zoom Account, sign up for a 60-days free trial at [https://marketplace.zoom.us/](https://marketplace.zoom.us/)
* **A device with Windows OS**:
  * OS: Windows XP or later. Currently Windows 10 UWP is not supported.
  * CPU: Zoom C# wrapper currently only supports x86


### Installing

Clone or download a copy of our SDK files from GitHub. After you unzipped the file, you should have the following folders:

```
.
├── bin
├── zoom_sdk_c_sharp_wrap
└── zoom_sdk_demo
```
Please follow the below steps to get started:

1.The wrap `Dll` locate at `zoom_sdk_csharp_wrap_github\bin\zoom_sdk_dotnet_wrap.dll`.

2.Run the demo project,

a>`zoom_sdk_csharp_wrap_github\zoom_sdk_demo\zoom_sdk_demo.csproj`

b>change vs project's solution configuration to "release"

c>change vs project's solution platform to "x86"

d>build and run.


## Documentation

Please visit [https://marketplace.zoom.us/docs/sdk/native-sdks/windows/c-sharp-wrapper](https://marketplace.zoom.us/docs/sdk/native-sdks/windows/c-sharp-wrapper)] for details of each features and functions.

## Versioning

For the versions available, see the [tags on this repository](https://github.com/zoom/zoom-sdk-windows/tags).

## Change log

Please refer to our [CHANGELOG](https://github.com/zoom/zoom-c-sharp-wrapper/blob/master/CHANGELOG.md) for all changes.

## Frequently Asked Questions (FAQ)

* Please visit our [Zoom Developer Community Forum](https://devforum.zoom.us/) for further assistance.

## Support

For any issues regarding our SDK, please visit our new Community Support Forum at https://devforum.zoom.us/.

## License

Use of this software is subject to important terms and conditions as set forth in the License file

Please refer to [LICENSE.md](https://github.com/zoom/zoom-c-sharp-wrapper/blob/master/LICENSE) file for details

## Contributiors

This project is a Zoom Community Project that is initialized by Zoom and welcoming the community developers to contribute.

Please see [CONTRIBUTORS](https://github.com/zoom/zoom-c-sharp-wrapper/blob/master/CONTRIBUTORS.md) for the project contributors.

## Acknowledgments

* :star: If you like our SDK, please give us a "Star". Your support is what keeps us moving forward and delivering happiness to you! Thanks a million! :smiley:
* If you need any support or assistance, we are here to help you: [Zoom Developer Community Forum](https://devforum.zoom.us/);

---
Copyright ©2020 Zoom Video Communications, Inc. All rights reserved.
