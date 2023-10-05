---
title: setLicense
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/license/setlicense/
---

## setLicenseFromStream (License license, ReadStream licenseStream, Function callback)  function

 Licenses the component.
 

 Note: 
 The following example demonstrates how to set a license passing InputStream of the license file.
 More about licensing: GroupDocs Licensing FAQ
 More about GroupDocs.Viewer licensing: Evaluation Limitations and Licensing
 

 Example: 
  
 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| license | License  | link to self |
| licenseStream | ReadStream | The license stream. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |


---


## setLicense(Path licensePath)  function

 Licenses the component.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| licensePath | Path | The license path. |


---


## setLicense(String licensePath)  function

 Licenses the component.
 

 Example: 
 The following example demonstrates how to set a license
 passing a path or url to the license file.
  
 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| licensePath | String | The license file path or url. |

### Error

| Error | Condition |
| --- | --- |
 | UnsupportedOperationException | {@code licensePath} is in an invalid format. |


---


