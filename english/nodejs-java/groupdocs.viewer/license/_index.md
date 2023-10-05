---
title: License
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/license/
---

## License class

 Provides methods to license the component. Learn more about licensing here.
 
| [License](license)() |  |

## Functions

| Name | Description |
| --- | --- |
| [resetLicense](resetlicense)() |  |
| [setLicenseFromStream ](setlicense)(License, ReadStream, Function) | Licenses the component. Note: The following example demonstrates how to set a license passing InputStream of the license file. More about licensing: GroupDocs Licensing FAQ More about GroupDocs.Viewer licensing: Evaluation Limitations and Licensing Example: FileInputStream licenseStream = new FileInputStream("LicenseFile.lic"); License license = new License(); license.setLicense(licenseStream); |
| [setLicense](setlicense)(Path) | Licenses the component. |
| [setLicense](setlicense)(String) | Licenses the component. Example: The following example demonstrates how to set a license passing a path or url to the license file. String licensePath = "GroupDocs.Viewer.lic"; License license = new License(); license.setLicense(licensePath); |
