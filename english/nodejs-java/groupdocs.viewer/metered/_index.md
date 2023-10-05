---
title: Metered
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/metered/
---

## Metered class

 Provides methods for applying Metered license.
 More about licensing: GroupDocs Licensing FAQ
 More about GroupDocs.Viewer licensing: Evaluation Limitations and Licensing
 
| [Metered](metered)() |  |

## Functions

| Name | Description |
| --- | --- |
| [getConsumptionCredit](getconsumptioncredit)() | Retrieves count of credits consumed. Example: Following example demonstrates how to retrieve count of credits consumed. String publicKey = "Public Key"; String privateKey = "Private Key"; Metered metered = new Metered(); metered.setMeteredKey(publicKey, privateKey); double creditsConsumed = Metered.getConsumptionCredit(); |
| [getConsumptionQuantity](getconsumptionquantity)() | Retrieves amount of MBs processed. Example: Following example demonstrates how to retrieve amount of MBs processed. String publicKey = "Public Key"; String privateKey = "Private Key"; Metered metered = new Metered(); metered.setMeteredKey(publicKey, privateKey); double mbProcessed = Metered.getConsumptionQuantity(); |
| [setMeteredKey](setmeteredkey)(String, String) | Activates product with Metered keys. Following example demonstrates how to activate product with Metered keys. String publicKey = "Public Key"; String privateKey = "Private Key"; Metered metered = new Metered(); metered.setMeteredKey(publicKey, privateKey); |
