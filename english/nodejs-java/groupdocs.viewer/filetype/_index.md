---
title: FileType
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/filetype/
---

## FileType class

 Represents file type. Provides methods to obtain list of all file types supported by GroupDocs.Viewer.
 

## Functions

| Name | Description |
| --- | --- |
| [areEquals](areequals)([FileType](../filetype), [FileType](../filetype)) | Determines whether two FileType objects are the same. |
| [areNotEquals](arenotequals)([FileType](../filetype), [FileType](../filetype)) | Determines whether two FileType objects are not the same. |
| [equalsByName](equalsbyname)(String) |  |
| [fromExtension](fromextension)(String) | Maps file extension to file type. |
| [fromFilePath](fromfilepath)(String) | Extracts file extension and maps it to file type. |
| [fromMediaType](frommediatype)(String) | Maps file media type to file type e&#46;g&#46; 'application/pdf' will be mapped to FileType.PDF. |
| [fromStreamFromStream ](fromstream)(FileType, ReadStream, Function) | Detects file type by reading the file signature. |
| [fromStreamFromStream ](fromstream)(FileType, ReadStream, String, Function) | Detects file type by reading the file signature. |
| [fromStreamFromStream ](fromstream)(FileType, ReadStream, ILogger, Function) | Detects file type by reading the file signature. |
| [fromStreamFromStream ](fromstream)(FileType, ReadStream, String, ILogger, Function) | Detects file type by reading the file signature. |
| [getExtension](getextension)() | Filename suffix (including the period ".") e&#46;g&#46; ".doc". |
| [getFileFormat](getfileformat)() | File type name e&#46;g&#46; "Microsoft Word Document". |
| [getSupportedFileTypes](getsupportedfiletypes)() | Retrieves supported file types |
| [toString](tostring)() | Returns a String that represents the current object. |
| [valueOf](valueof)(String) |  |
| [values](values)() |  |
