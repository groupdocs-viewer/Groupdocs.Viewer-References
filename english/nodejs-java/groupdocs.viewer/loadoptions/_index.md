---
title: LoadOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/loadoptions/
---

## LoadOptions class

 Provides options that used to open the file.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
| DEFAULT_URL_CONNECT_TIMEOUT | 5000 |  |
| DEFAULT_URL_READ_TIMEOUT | 30000 |  |

| [LoadOptions](loadoptions)() | Initializes new instance of LoadOptions class. |
| [LoadOptions](loadoptions)([FileType](../filetype)) | Initializes new instance of LoadOptions class. |

## Functions

| Name | Description |
| --- | --- |
| [getArchiveSecurityOptions](getarchivesecurityoptions)() | Security options to control the process of extracting archives. Not each archive type supports all options. |
| [getCharset](getcharset)() | The Charset used when opening text-based files or email messages such as FileType#CSV, FileType#TXT, and FileType#MSG. Default value is ( Charset#defaultCharset()}). |
| [getFileType](getfiletype)() | The type of the file to open. |
| [getPassword](getpassword)() | The password for opening encrypted file. |
| [getResourceLoadingTimeout](getresourceloadingtimeout)() | The external resources e&#46;g&#46; graphics loading timeout. The default value is 30 seconds. This option is supported for Word Processing documents that contain external resources. |
| [getUrlConnectTimeout](geturlconnecttimeout)() | Connect timeout to create com.groupdocs.viewer.Viewer using java.net.URL to load document, default value is 5 seconds |
| [getUrlReadTimeout](geturlreadtimeout)() | Read timeout to create com.groupdocs.viewer.Viewer using java.net.URL to load document, default value is 30 seconds |
| [setArchiveSecurityOptions](setarchivesecurityoptions)(ArchiveSecurityOptions) | Security options to control the process of extracting archives. Not each archive type supports all options. |
| [setCharset](setcharset)(Charset) | The Charset used when opening text-based files or email messages such as FileType#CSV, FileType#TXT, and FileType#MSG. Default value is ( Charset#defaultCharset()). |
| [setFileType](setfiletype)([FileType](../filetype)) | The type of the file to open. |
| [setPassword](setpassword)(String) | The password for opening encrypted file. |
| [setResourceLoadingTimeout](setresourceloadingtimeout)(int) | The external resources e&#46;g&#46; graphics loading timeout. The default value is 30 seconds. This option is supported for Word Processing documents that contain external resources. |
| [setUrlConnectTimeout](seturlconnecttimeout)(int) | Connect timeout to create com.groupdocs.viewer.Viewer using java.net.URL to load document, default value is 5 seconds |
| [setUrlReadTimeout](seturlreadtimeout)(int) | Read timeout to create com.groupdocs.viewer.Viewer using java.net.URL to load document, default value is 30 seconds |
