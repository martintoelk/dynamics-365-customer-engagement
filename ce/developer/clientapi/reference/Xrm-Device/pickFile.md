---
title: "pickFile| MicrosoftDocs"
ms.date: 10/31/2017
ms.service: "crm-online"
ms.topic: "reference"
applies_to: "Dynamics 365 (online)"
ms.assetid: c777a0b8-2b07-458b-8a4f-8938f7a2e696
author: "KumarVivek"
ms.author: "kvivek"
manager: "amyla"
search.audienceType: 
  - developer
search.app: 
  - D365CE
---
# pickFile (Client API reference)

[!INCLUDE[](../../../../includes/cc_applies_to_update_9_0_0.md)]

[!INCLUDE[./includes/pickFile-description.md](./includes/pickFile-description.md)]


## Syntax

`Xrm.Device.pickFile(pickFileOptions).then(successCallback, errorCallback)`

## Parameters

| Parameter Name        | Type           | Required  |Description  |
| ------------- |-------------| -----|-----|
|pickFileOptions |Object | No|An object with the following attributes:<br/>- **accept**: Image file types to select. Valid values are "audio", "video", or "image". String.<br/>- **allowMultipleFiles**: Indicates whether to allow selecting multiple files. Boolean.<br/>- **maximumAllowedFileSize**: Maximum size of the files(s) to be selected. Number.|
|successCallback |Function | Yes|A function to call when selected files are returned. An array of objects with *each* object having the following attributes is passed to the function:<br/>- **fileContent**: Contents of the file. String <br/>- **fileName**: Name of the file. String.<br/>- **fileSize**: Size of the file in KB. Number.<br/>- **mimeType**: File MIME type. String.|
|errorCallback |Function | Yes|A function to call when the operation fails. |
 

## Return Value
On success, returns a promise with array of objects as specified earlier for the **successCallback** function.

### Related topics
[Xrm.Device](../xrm-device.md)

