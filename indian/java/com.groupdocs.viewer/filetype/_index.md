---
title: "FileType"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "फ़ाइल प्रकार का प्रतिनिधित्व करता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

फ़ाइल प्रकार का प्रतिनिधित्व करता है। GroupDocs.Viewer घटक द्वारा समर्थित सभी फ़ाइल प्रकारों की सूची प्राप्त करने के लिए मेथड प्रदान करता है।


FileType एनीम उन विभिन्न फ़ाइल प्रकारों के स्थिरांक प्रदान करता है जो GroupDocs.Viewer घटक द्वारा समर्थित हैं।
आप इस एनीम के मेथड का उपयोग करके सभी समर्थित फ़ाइल प्रकारों की सूची प्राप्त कर सकते हैं या यह जांच सकते हैं कि कोई विशिष्ट फ़ाइल प्रकार समर्थित है या नहीं।


उदाहरण उपयोग:

````

 // Try to detect file type using stream
 final FileType fileTypeFromStream = FileType.fromStream(new FileInputStream("document.pdf"));
 // Detect file type by extension
 final FileType fileTypeFromExtension = FileType.fromExtension(".png");
 // Iterate all supported file types
 for (FileType supportedFileType : FileType.getSupportedFileTypes()) {
     System.out.println("File type: " + supportedFileType);
 }
 final LoadOptions loadOptions = new LoadOptions(fileTypeFromExtension);
 // Usage of loadOptions
 
````


## Fields

| Field | विवरण |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | अज्ञात फ़ाइल प्रकार का प्रतिनिधित्व करता है। |
|
|  | [ZIP](#ZIP) | ज़िप्ड फ़ाइल (.zip) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों या निर्देशिकाओं को रख सकती है। |
|
|  | [TAR](#TAR) | एक या अधिक फ़ाइलों को एकत्र करने के लिए बनाई गई समेकित Unix फ़ाइल संग्रह (.tar) का प्रतिनिधित्व करता है। |
|
|  | [XZ](#XZ) | LZMA एल्गोरिदम पर आधारित उच्च अनुपात संपीड़न एल्गोरिदम का उपयोग करके संकुचित XZ फ़ाइल (.xz) का प्रतिनिधित्व करता है। |
|
|  | [TXZ](#TXZ) | एकीकृत Unix फ़ाइल अभिलेख (.txz, .tar.xz) का प्रतिनिधित्व करता है, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए बनाया गया है। |
|
|  | [TARXZ](#TARXZ) | एकीकृत Unix फ़ाइल अभिलेख (.txz, .tar.xz) का प्रतिनिधित्व करता है, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए बनाया गया है। |
|
|  | [TGZ](#TGZ) | एकीकृत Unix फ़ाइल अभिलेख (.tgz, .tar.gz) का प्रतिनिधित्व करता है, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए बनाया गया है। |
|
|  | [TARGZ](#TARGZ) | एकीकृत Unix फ़ाइल अभिलेख (.tgz, .tar.gz) का प्रतिनिधित्व करता है, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए बनाया गया है। |
|
|  | [BZ_2](#BZ-2) | BZIP2 ओपन-सोर्स संपीड़न विधि का उपयोग करके उत्पन्न Bzip2 संकुचित फ़ाइल (.bz2) का प्रतिनिधित्व करता है। |
|
|  | [RAR](#RAR) | RAR (WINRAR संस्करण 4) संपीड़न विधि का उपयोग करके उत्पन्न Roshal Archive (.rar) संकुचित फ़ाइल का प्रतिनिधित्व करता है। |
|
|  | [GZ](#GZ) | gzip संपीड़न अनुप्रयोग के साथ बनाई गई Gnu Zipped फ़ाइल (.gz) संकुचित फ़ाइल का प्रतिनिधित्व करता है। |
|
|  | [GZIP](#GZIP) | Unix सिस्टम में उपयोग किए जाने वाले Compress प्रोग्राम को बदलने के लिए एक मुफ्त उपयोगिता के रूप में प्रस्तुत Gnu Zipped फ़ाइल (.gzip) संकुचित फ़ाइल का प्रतिनिधित्व करता है। |
|
|  | [SEVEN_ZIP](#SEVEN-ZIP) | 7Zip (.7z, .7zip) फ़ाइल का प्रतिनिधित्व करता है, जो LZMA और LZMA2 संपीड़न के साथ एक मुफ्त ओपन-सोर्स आर्काइवर है। |
|
|  | [CPIO](#CPIO) | Cpio एक सामान्य फ़ाइल आर्काइवर उपयोगिता और उसका संबंधित फ़ाइल स्वरूप है। |
|
|  | [ZSTANDARD](#ZSTANDARD) | ZST फ़ाइल एक संकुचित फ़ाइल है जो Zstandard (zstd) संपीड़न एल्गोरिद्म के साथ उत्पन्न होती है। |
|
|  | [TZST](#TZST) | TZST फ़ाइलें (.tar.zst, .tzst) Zstandard अभिलेख (ZST) हैं, जो आंतरिक रूप से एक एकीकृत Unix फ़ाइल अभिलेख (Tar) शामिल करती हैं, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए Unix-आधारित उपयोगिता के साथ बनाई गई हैं। |
|
|  | [TAR_ZST](#TAR-ZST) | TZST फ़ाइलें (.tar.zst, .tzst) Zstandard अभिलेख (ZST) हैं, जो आंतरिक रूप से एक एकीकृत Unix फ़ाइल अभिलेख (Tar) शामिल करती हैं, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए Unix-आधारित उपयोगिता के साथ बनाई गई हैं। |
|
|  | [ISO](#ISO) | ISO ऑप्टिकल डिस्क इमेज एक अनकम्प्रेस्ड अभिलेख डिस्क इमेज फ़ाइल है जो CD या DVD जैसे ऑप्टिकल डिस्क पर संपूर्ण डेटा की सामग्री को दर्शाती है, ISO-9660 मानक पर आधारित। |
|
|  | [LHA](#LHA) | LHA या LZH एक फ्रीवेयर संपीड़न उपयोगिता और संबंधित फ़ाइल स्वरूप है। |
|
|  | [CAB](#CAB) | Cabinet (या CAB) माइक्रोसॉफ्ट विंडोज़ के लिए एक अभिलेख-फ़ाइल स्वरूप है। |
|
|  | [DXF](#DXF) | Drawing Exchange Format फ़ाइल (.dxf) का प्रतिनिधित्व करता है, जो AutoCAD ड्रॉइंग फ़ाइल का टैग्ड डेटा प्रतिनिधित्व है। |
|
|  | [DWG](#DWG) | AutoCAD Drawing Database फ़ाइल (.dwg) का प्रतिनिधित्व करता है, जो 2D और 3D डिज़ाइन डेटा रखने के लिए उपयोग की जाने वाली स्वामित्व बाइनरी फ़ाइलों को दर्शाती है। |
|
|  | [DWT](#DWT) | AutoCAD Drawing Template (.dwt) का प्रतिनिधित्व करता है, जो ड्रॉइंग बनाने के लिए प्रारंभिक बिंदु के रूप में उपयोग की जाने वाली AutoCAD ड्रॉइंग टेम्पलेट फ़ाइल है, जिसे DWG फ़ाइलों के रूप में सहेजा जा सकता है। |
|
|  | [STL](#STL) | Stereolithography फ़ाइल (.stl) का प्रतिनिधित्व करता है, जो 3-आयामी सतह ज्यामिति को दर्शाने वाला एक अदलाबदल योग्य फ़ाइल स्वरूप है। |
|
|  | [IFC](#IFC) | Industry Foundation Classes फ़ाइल (.ifc) का प्रतिनिधित्व करता है, जो भवन वस्तुओं और उनकी विशेषताओं के आयात और निर्यात के लिए अंतरराष्ट्रीय मानक स्थापित करने वाला फ़ाइल स्वरूप है। |
|
|  | [DWF](#DWF) | Design Web Format फ़ाइल (.dwf) का प्रतिनिधित्व करता है, जो 2D/3D ड्रॉइंग को देखने, समीक्षा करने या प्रिंट करने के लिए संकुचित फ़ाइल स्वरूप है। |
|
|  | [FBX](#FBX) | Autodesk FBX Interchange फ़ाइल (FilmBoX) (.fbx) का प्रतिनिधित्व करता है, जो एक 3D मॉडल स्वरूप है। |
|
|  | [DWFX](#DWFX) | Design Web Format फ़ाइल XPS (.dwfx) का प्रतिनिधित्व करता है, जो 2D/3D ड्रॉइंग को XPS दस्तावेज़ के रूप में देखने, समीक्षा करने या प्रिंट करने के लिए संकुचित स्वरूप है। |
|
|  | [DGN](#DGN) | MicroStation Design फ़ाइल (.dgn) का प्रतिनिधित्व करता है, जो MicroStation और Intergraph Interactive Graphics Design System जैसे CAD अनुप्रयोगों द्वारा बनाई और समर्थित ड्रॉइंग हैं। |
|
|  | [PLT](#PLT) | PLT (HPGL) फ़ाइल (.plt) का प्रतिनिधित्व करता है, जो Autodesk, Inc. द्वारा प्रस्तुत एक वेक्टर-आधारित प्लॉटर फ़ाइल है। |
|
|  | [CF2](#CF2) | Common File Format फ़ाइल (.cf2) का प्रतिनिधित्व करता है। |
|
|  | [OBJ](#OBJ) | Wavefront 3D ऑब्जेक्ट फ़ाइल (.obj) का प्रतिनिधित्व करता है, जो Wavefront Technologies द्वारा प्रस्तुत 3D इमेज फ़ाइल है। |
|
|  | [HPG](#HPG) | एक PLT (HPGL) फ़ाइल (.hpg) का प्रतिनिधित्व करता है। |
|
|  | [IGS](#IGS) | एक Initial Graphics Exchange Specification (IGES) फ़ाइल (.igs) का प्रतिनिधित्व करता है। |
|
|  | [VSD](#VSD) | एक Visio Drawing फ़ाइल (.vsd) का प्रतिनिधित्व करता है, जो Microsoft Visio एप्लिकेशन से बनाई गई ड्रॉइंग्स हैं, जो विभिन्न ग्राफ़िकल ऑब्जेक्ट्स और उनके अंतरसंबंधों को दर्शाती हैं। |
|
|  | [VSDX](#VSDX) | एक Visio Drawing फ़ाइल (.vsdx) का प्रतिनिधित्व करता है, जो Microsoft Office 2013 से आगे के संस्करणों में पेश किए गए Microsoft Visio फ़ाइल फ़ॉर्मेट को दर्शाता है। |
|
|  | [VSS](#VSS) | एक Visio Stencil फ़ाइल (.vss) का प्रतिनिधित्व करता है, जो Microsoft Visio 2007 और उससे पहले के संस्करणों से बनाई गई स्टेंसिल फ़ाइलें हैं। |
|
|  | [VSSX](#VSSX) | एक Visio Stencil फ़ाइल (.vssx) का प्रतिनिधित्व करता है, जो Microsoft Visio 2013 और उसके बाद के संस्करणों से बनाई गई ड्रॉइंग स्टेंसिल हैं। |
|
|  | [VSDM](#VSDM) | एक Visio Macro-Enabled Drawing (.vsdm) का प्रतिनिधित्व करता है, जो Microsoft Visio एप्लिकेशन से बनाई गई ड्रॉइंग फ़ाइलें हैं, जो मैक्रो का समर्थन करती हैं। |
|
|  | [VST](#VST) | एक Visio Drawing Template (.vst) का प्रतिनिधित्व करता है, जो Microsoft Visio से बनाई गई वेक्टर इमेज फ़ाइलें हैं। |
|
|  | [VSTX](#VSTX) | एक Visio Drawing Template (.vstx) का प्रतिनिधित्व करता है, जो Microsoft Visio 2013 और उसके बाद के संस्करणों से बनाई गई ड्रॉइंग टेम्पलेट फ़ाइलें हैं। |
|
|  | [VSTM](#VSTM) | एक Visio Macro-Enabled Drawing Template (.vstm) का प्रतिनिधित्व करता है, जो Microsoft Visio से बनाई गई टेम्पलेट फ़ाइलें हैं, जो मैक्रो का समर्थन करती हैं। |
|
|  | [VSSM](#VSSM) | एक Visio Macro-Enabled Stencil फ़ाइल (.vssm) का प्रतिनिधित्व करता है, जो Microsoft Visio Stencil फ़ाइलें हैं, जो मैक्रो का समर्थन करती हैं। |
|
|  | [VSX](#VSX) | एक Visio Stencil XML फ़ाइल (.vsx) का प्रतिनिधित्व करता है, जो उन स्टेंसिल्स को दर्शाता है जिनमें ड्रॉइंग्स और आकार होते हैं, जो Microsoft Visio में डायग्राम बनाने के लिए उपयोग होते हैं। |
|
|  | [VTX](#VTX) | एक Visio Template XML फ़ाइल (.vtx) का प्रतिनिधित्व करता है, जो XML फ़ाइल फ़ॉर्मेट में डिस्क पर सहेजा गया Microsoft Visio ड्रॉइंग टेम्पलेट है। |
|
|  | [VDW](#VDW) | एक Visio Web Drawing (.vdw) का प्रतिनिधित्व करता है, जो वेब ड्रॉइंग को रेंडर करने के लिए आवश्यक स्ट्रीम्स और स्टोरेज को निर्दिष्ट करता है। |
|
|  | [VDX](#VDX) | एक Visio Drawing XML फ़ाइल (.vdx) का प्रतिनिधित्व करता है, जो Microsoft Visio में बनाई गई किसी भी ड्रॉइंग या चार्ट को दर्शाता है, लेकिन .VDX एक्सटेंशन के साथ XML फ़ॉर्मेट में सहेजा गया है। |
|
|  | [EPUB](#EPUB) | एक Open eBook फ़ाइल (.epub) का प्रतिनिधित्व करता है, जो एक ई-बुक फ़ाइल फ़ॉर्मेट है जो प्रकाशकों और उपभोक्ताओं के लिए एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। |
|
|  | [MOBI](#MOBI) | एक Mobipocket eBook (.mobi) का प्रतिनिधित्व करता है, जो सबसे अधिक उपयोग किए जाने वाले ईबुक फ़ाइल फ़ॉर्मेट्स में से एक है। |
|
|  | [AZW_3](#AZW-3) | Amazon Kindle Format 8 (KF8) ईबुक Amazon Kindle डिवाइसों के लिए विकसित किया गया डिजिटल फ़ाइल फ़ॉर्मेट है। |
|
|  | [MSG](#MSG) | एक Outlook Mail Message (.msg) का प्रतिनिधित्व करता है, जो Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, अपॉइंटमेंट या अन्य कार्यों को संग्रहीत करने के लिए उपयोग किया जाने वाला फ़ाइल फ़ॉर्मेट है। |
|
|  | [EML](#EML) | एक E-Mail Message (.eml) का प्रतिनिधित्व करता है, जो Outlook और अन्य संबंधित अनुप्रयोगों का उपयोग करके सहेजे गए ईमेल संदेशों को दर्शाता है। |
|
|  | [EMLX](#EMLX) | एक Apple Mail Message (.emlx) का प्रतिनिधित्व करता है, जिसे Apple ने लागू और विकसित किया है। |
|
|  | [PST](#PST) | एक Outlook Personal Information Store फ़ाइल (.pst) का प्रतिनिधित्व करता है, जो Outlook Personal Storage Files (जिन्हें Personal Storage Table भी कहा जाता है) को दर्शाता है, जो विभिन्न उपयोगकर्ता जानकारी संग्रहीत करती हैं। |
|
|  | [OST](#OST) | एक Outlook Offline Data फ़ाइल (.ost) का प्रतिनिधित्व करता है, जो उपयोगकर्ता के मेलबॉक्स डेटा को ऑफ़लाइन मोड में स्थानीय मशीन पर, Exchange Server के साथ Microsoft Outlook के पंजीकरण के बाद, संग्रहीत करता है। |
|
|  | [TIF](#TIF) | एक Tagged Image File (.tif) का प्रतिनिधित्व करता है, जो रास्टर इमेजेज को दर्शाता है, जिन्हें विभिन्न उपकरणों पर उपयोग के लिए बनाया गया है जो इस फ़ाइल फ़ॉर्मेट मानक का पालन करते हैं। |
|
|  | [TIFF](#TIFF) | एक Tagged Image File Format (.tiff) का प्रतिनिधित्व करता है, जो रास्टर इमेजेज को दर्शाता है, जिन्हें विभिन्न उपकरणों पर उपयोग के लिए बनाया गया है जो इस फ़ाइल फ़ॉर्मेट मानक का पालन करते हैं। |
|
|  | [JPG](#JPG) | JPEG इमेज (.jpg) का प्रतिनिधित्व करता है, जो एक प्रकार का इमेज फ़ॉर्मेट है जिसे लॉसी कम्प्रेशन विधि का उपयोग करके सहेजा जाता है। |
|
|  | [JPEG](#JPEG) | JPEG इमेज (.jpeg) का प्रतिनिधित्व करता है, जो एक प्रकार का इमेज फ़ॉर्मेट है जिसे लॉसी कम्प्रेशन विधि का उपयोग करके सहेजा जाता है। |
|
|  | [JFIF](#JFIF) | JPEG फ़ाइल इंटरचेंज फ़ॉर्मेट (.jfif) एक इमेज है जो प्लेटफ़ॉर्मों के बीच तेज़ आदान‑प्रदान के लिए विकसित किया गया था। |
|
|  | [PNG](#PNG) | Portable Network Graphic (.png) का प्रतिनिधित्व करता है, जो एक प्रकार का रास्टर इमेज फ़ाइल फ़ॉर्मेट है जो लॉसलेस कम्प्रेशन का उपयोग करता है। |
|
|  | [GIF](#GIF) | Graphical Interchange Format फ़ाइल (.gif) का प्रतिनिधित्व करता है, जो अत्यधिक संकुचित इमेज का एक प्रकार है। |
|
|  | [APNG](#APNG) | Animated Portable Network Graphic (.apng) का प्रतिनिधित्व करता है, जो PNG फ़ॉर्मेट का एक विस्तार है जो एनीमेशन का समर्थन करता है। |
|
|  | [BMP](#BMP) | Bitmap इमेज फ़ाइल (.bmp) का प्रतिनिधित्व करता है, जिसका उपयोग बिटमैप डिजिटल इमेज को संग्रहीत करने के लिए किया जाता है। |
|
|  | [ICO](#ICO) | Icon फ़ाइल (.ico) का प्रतिनिधित्व करता है, जो माइक्रोसॉफ्ट विंडोज पर एप्लिकेशन के प्रतिनिधित्व के लिए आइकन के रूप में उपयोग की जाने वाली इमेज फ़ाइल प्रकार है। |
|
|  | [TGA](#TGA) | Truevision TGA (TARGA) फ़ाइल का प्रतिनिधित्व करता है, जिसका उपयोग TRUEVISION द्वारा विकसित बिटमैप डिजिटल इमेज को संग्रहीत करने के लिए किया जाता है। |
|
|  | [JP_2](#JP-2) | JPEG 2000 कोर इमेज फ़ाइल (.jp2) का प्रतिनिधित्व करता है, जो एक इमेज कोडिंग सिस्टम और अत्याधुनिक इमेज कम्प्रेशन मानक है। |
|
|  | [JPF](#JPF) | JPEG 2000 इमेज फ़ाइल (.jpf) का प्रतिनिधित्व करता है। |
|
|  | [JPX](#JPX) | JPEG 2000 इमेज फ़ाइल (.jpx) का प्रतिनिधित्व करता है। |
|
|  | [JPM](#JPM) | JPEG 2000 इमेज फ़ाइल (.jpm) का प्रतिनिधित्व करता है। |
|
|  | [J2C](#J2C) | JPEG 2000 कोड InputStream (.j2c) का प्रतिनिधित्व करता है। |
|
|  | [J2K](#J2K) | JPEG 2000 कोड स्ट्रीम (.j2k) का प्रतिनिधित्व करता है, जो DCT कम्प्रेशन के बजाय वेवलेट कम्प्रेशन का उपयोग करके संकुचित इमेज है। |
|
|  | [JPC](#JPC) | JPEG 2000 कोड स्ट्रीम (.jpc) का प्रतिनिधित्व करता है। |
|
|  | [JLS](#JLS) | JPEG-LS (JLS) फ़ाइल (.jls) का प्रतिनिधित्व करता है। |
|
|  | [DIB](#DIB) | Device Independent Bitmap फ़ाइल (.dib) का प्रतिनिधित्व करता है। |
|
|  | [WMF](#WMF) | Windows Metafile (.wmf) का प्रतिनिधित्व करता है, जो वेक्टर और बिटमैप-फ़ॉर्मेट इमेज डेटा को संग्रहीत करने के लिए Microsoft Windows Metafile (WMF) को दर्शाता है। |
|
|  | [WMZ](#WMZ) | Compressed Windows Metafile (.wmz) का प्रतिनिधित्व करता है, जो वेक्टर और बिटमैप-फ़ॉर्मेट इमेज डेटा को संग्रहीत करने के लिए GZIP आर्काइव में संकुचित Microsoft Windows Metafile (WMF) को दर्शाता है। |
|
|  | [EMF](#EMF) | Enhanced Windows Metafile (.emf) का प्रतिनिधित्व करता है, जो ग्राफ़िकल इमेज को डिवाइस-स्वतंत्र रूप से दर्शाता है। |
|
|  | [EMZ](#EMZ) | Windows Compressed Enhanced Metafile (.emz) का प्रतिनिधित्व करता है, जो GZIP द्वारा संकुचित डिवाइस-स्वतंत्र ग्राफ़िकल इमेज को दर्शाता है। |
|
|  | [WEBP](#WEBP) | WebP इमेज (.webp) का प्रतिनिधित्व करता है, जो लॉसलेस और लॉसी कम्प्रेशन पर आधारित एक आधुनिक रास्टर वेब इमेज फ़ाइल फ़ॉर्मेट है। |
|
|  | [DNG](#DNG) | Digital Negative Specification (.dng) का प्रतिनिधित्व करता है, जो कच्ची फ़ाइलों के भंडारण के लिए उपयोग किया जाने वाला डिजिटल कैमरा इमेज फ़ॉर्मेट है। |
|
|  | [CDR](#CDR) | CorelDraw Vector Graphic Drawing (.cdr) का प्रतिनिधित्व करता है, जो CorelDRAW के साथ मूल रूप से निर्मित एक वेक्टर ड्रॉइंग इमेज फ़ाइल है, जो डिजिटल रूप से एन्कोडेड और संकुचित इमेज को संग्रहीत करने के लिए उपयोग होती है। |
|
|  | [CMX](#CMX) | Corel Exchange (.cmx) को दर्शाता है, जो एक ड्राइंग इमेज फ़ाइल है जिसमें वेक्टर ग्राफ़िक्स और बिटमैप ग्राफ़िक्स दोनों हो सकते हैं। |
|
|  | [DJVU](#DJVU) | DjVu Image (.djvu) को दर्शाता है, जो स्कैन किए गए दस्तावेज़ों और पुस्तकों के लिए अभिप्रेत एक ग्राफ़िक्स फ़ाइल फ़ॉर्मेट है, विशेष रूप से उन फ़ाइलों के लिए जिनमें पाठ, चित्र, इमेज और फ़ोटोग्राफ़ का संयोजन होता है। |
|
|  | [CGM](#CGM) | Computer Graphics Metafile (.cgm) को दर्शाता है, जो एक मुफ्त, प्लेटफ़ॉर्म-स्वतंत्र, अंतरराष्ट्रीय मानक मेटाफाइल फ़ॉर्मेट है जो वेक्टर ग्राफ़िक्स (2D), रास्टर ग्राफ़िक्स और टेक्स्ट को संग्रहीत और विनिमय करने के लिए उपयोग होता है। |
|
|  | [PCL](#PCL) | Printer Command Language Document (.pcl) को दर्शाता है। |
|
|  | [PSD](#PSD) | Adobe Photoshop Document (.psd) को दर्शाता है, जो Adobe Photoshop का मूल फ़ाइल फ़ॉर्मेट है जो ग्राफ़िक्स डिज़ाइनिंग और विकास के लिए उपयोग होता है। |
|
|  | [PSB](#PSB) | Photoshop Large Document Format (.psb) को दर्शाता है, जो Adobe Photoshop में ग्राफ़िक्स डिज़ाइनिंग और विकास के लिए उपयोग होता है। |
|
|  | [DCM](#DCM) | DICOM Image (.dcm) को दर्शाता है, जो एक डिजिटल इमेज है जो रोगियों की चिकित्सा जानकारी जैसे MRI, CT स्कैन और अल्ट्रासाउंड इमेज को संग्रहीत करता है। |
|
|  | [PS](#PS) | PostScript File (.ps) को दर्शाता है। |
|
|  | [EPS](#EPS) | Encapsulated PostScript File (.eps) को दर्शाता है, जो एक Encapsulated PostScript भाषा प्रोग्राम का वर्णन करता है जो एक पृष्ठ की उपस्थिति को परिभाषित करता है। |
|
|  | [ODG](#ODG) | OpenDocument Graphic File (.odg) को दर्शाता है, जो Apache OpenOffice के Draw एप्लिकेशन द्वारा ड्राइंग तत्वों को वेक्टर इमेज के रूप में संग्रहीत करने के लिए उपयोग होता है। |
|
|  | [FODG](#FODG) | Flat XML ODF Template (.fodg) को दर्शाता है, जो Apache OpenOffice के Draw एप्लिकेशन द्वारा ड्राइंग तत्वों को वेक्टर इमेज के रूप में संग्रहीत करने के लिए उपयोग होता है। |
|
|  | [SVG](#SVG) | Scalable Vector Graphics File (.svg) को दर्शाता है, जो एक Scalable Vector Graphics फ़ाइल है जो इमेज की उपस्थिति का वर्णन करने के लिए XML-आधारित टेक्स्ट फ़ॉर्मेट का उपयोग करती है। |
|
|  | [SVGZ](#SVGZ) | Compressed Scalable Vector Graphics File (.svgz) को दर्शाता है, जो एक Scalable Vector Graphics फ़ाइल है जो XML-आधारित टेक्स्ट फ़ॉर्मेट, GZIP द्वारा संकुचित, का उपयोग करके इमेज की उपस्थिति का वर्णन करती है। |
|
|  | [OTG](#OTG) | OpenDocument Graphic Template (.otg) को दर्शाता है। |
|
|  | [HTM](#HTM) | Hypertext Markup Language File (.htm) को दर्शाता है, जो ब्राउज़र में प्रदर्शित होने वाले वेब पेजों के लिए उपयोग किया जाने वाला एक्सटेंशन है। |
|
|  | [HTML](#HTML) | Hypertext Markup Language File (.html) को दर्शाता है, जो ब्राउज़र में प्रदर्शित होने वाले वेब पेजों के लिए उपयोग किया जाने वाला एक्सटेंशन है। |
|
|  | [MHT](#MHT) | MHTML Web Archive (.mht) को दर्शाता है। |
|
|  | [NSF](#NSF) | Lotus Notes Database (.nsf) को दर्शाता है। |
|
|  | [MBOX](#MBOX) | Email Mailbox File (.mbox) को दर्शाता है। |
|
|  | [MHTML](#MHTML) | MIME HTML File (.mhtml) को दर्शाता है। |
|
|  | [XML](#XML) | XML File (.xml) को दर्शाता है। |
|
|  | [ONE](#ONE) | OneNote Document (.one) को दर्शाता है, जो Microsoft OneNote एप्लिकेशन द्वारा बनाया गया है। |
|
|  | [PDF](#PDF) | Portable Document Format File (.pdf) को दर्शाता है, जो 1990 के दशक में Adobe द्वारा बनाया गया एक दस्तावेज़ प्रकार है। |
|
|  | [XPS](#XPS) | XML Paper Specification File (.xps) को दर्शाता है, जो Microsoft द्वारा बनाई गई XML Paper Specifications पर आधारित पेज लेआउट फ़ाइलों को दर्शाता है। |
|
|  | [OXPS](#OXPS) | OpenXPS File (.oxps) को दर्शाता है। |
|
|  | [TEX](#TEX) | LaTeX स्रोत दस्तावेज़ (.tex) को दर्शाता है, जो एक भाषा है जिसमें प्रोग्रामिंग और मार्क‑अप सुविधाएँ शामिल हैं और जिसका उपयोग दस्तावेज़ टाइपसेट करने के लिए किया जाता है। |
|
|  | [OFD](#OFD) | GB/T 33190-2016 द्वारा परिभाषित Open Fixed-layout Document (OFD) फ़ॉर्मेट का लक्ष्य चीनी सार्वजनिक संस्थानों में PDF को बदलना है। |
|
|  | [PPT](#PPT) | PowerPoint प्रस्तुति (.ppt) को दर्शाता है, जो एक PowerPoint फ़ाइल है जिसमें स्लाइडों का संग्रह होता है जिसे स्लाइडशो के रूप में प्रदर्शित किया जाता है। |
|
|  | [PPTX](#PPTX) | PowerPoint Open XML प्रस्तुति (.pptx) को दर्शाता है, जो लोकप्रिय Microsoft PowerPoint एप्लिकेशन से बनाई गई प्रस्तुति फ़ाइलें हैं। |
|
|  | [PPS](#PPS) | PowerPoint स्लाइड शो (.pps) को दर्शाता है, जो स्लाइड शो उद्देश्यों के लिए Microsoft PowerPoint का उपयोग करके बनाया जाता है। |
|
|  | [PPSX](#PPSX) | PowerPoint Open XML स्लाइड शो (.ppsx) फ़ाइलों को दर्शाता है, जो स्लाइड शो उद्देश्यों के लिए Microsoft PowerPoint 2007 और उसके बाद के संस्करणों से बनाई गई हैं। |
|
|  | [ODP](#ODP) | OpenDocument प्रस्तुति (.odp) को दर्शाता है, जो OpenOffice.org द्वारा OASISOpen मानक में उपयोग किए जाने वाले प्रस्तुति फ़ाइल फ़ॉर्मेट को दर्शाता है। |
|
|  | [FODP](#FODP) | OpenDocument प्रस्तुति (.fodp) को दर्शाता है, जो OpenDocument फ्लैट XML प्रस्तुति को दर्शाता है। |
|
|  | [POT](#POT) | PowerPoint टेम्पलेट (.pot) को दर्शाता है, जो PowerPoint 97-2003 संस्करणों द्वारा बनाई गई Microsoft PowerPoint टेम्पलेट फ़ाइलें हैं। |
|
|  | [PPTM](#PPTM) | PowerPoint Open XML मैक्रो‑सक्षम प्रस्तुति (.pptm) को दर्शाता है, जो Microsoft PowerPoint 2007 या उसके बाद के संस्करणों से बनाई गई मैक्रो‑सक्षम प्रस्तुति फ़ाइलें हैं। |
|
|  | [POTX](#POTX) | PowerPoint Open XML प्रस्तुति टेम्पलेट (.potx) को दर्शाता है, जो Microsoft PowerPoint 2007 और उसके बाद के संस्करणों से बनाई गई Microsoft PowerPoint टेम्पलेट प्रस्तुतियों को दर्शाता है। |
|
|  | [POTM](#POTM) | PowerPoint Open XML मैक्रो‑सक्षम प्रस्तुति टेम्पलेट (.potm) को दर्शाता है, जो मैक्रो समर्थन वाली Microsoft PowerPoint टेम्पलेट फ़ाइलें हैं। |
|
|  | [PPSM](#PPSM) | PowerPoint Open XML मैक्रो‑सक्षम स्लाइड (.ppsm) को दर्शाता है, जो Microsoft PowerPoint 2007 या उसके बाद के संस्करणों से बनाई गई मैक्रो‑सक्षम स्लाइड शो फ़ाइल फ़ॉर्मेट को दर्शाता है। |
|
|  | [OTP](#OTP) | OpenDocument प्रस्तुति टेम्पलेट (.otp) को दर्शाता है, जो OASIS OpenDocument मानक फ़ॉर्मेट में अनुप्रयोगों द्वारा बनाई गई प्रस्तुति टेम्पलेट फ़ाइलें हैं। |
|
|  | [XLS](#XLS) | Excel स्प्रेडशीट (.xls) को दर्शाता है, जो Excel बाइनरी फ़ाइल फ़ॉर्मेट को दर्शाता है। |
|
|  | [EXCEL_2003_XML](#EXCEL-2003-XML) | Excel 2003 XML (SpreadsheetML) (.xml) को दर्शाता है, जो Excel बाइनरी फ़ाइल फ़ॉर्मेट को दर्शाता है। |
|
|  | [NUMBERS](#NUMBERS) | Apple Numbers (.numbers) को दर्शाता है, जो Excel‑समान बाइनरी फ़ाइल फ़ॉर्मेट को दर्शाता है। |
|
|  | [XLSX](#XLSX) | Microsoft Excel Open XML स्प्रेडशीट (.xlsx) को दर्शाता है, जो Microsoft Excel दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है जिसे Microsoft ने Microsoft Office 2007 के रिलीज़ के साथ पेश किया था। |
|
|  | [XLSM](#XLSM) | Excel Open XML मैक्रो‑सक्षम स्प्रेडशीट (.xlsm) को दर्शाता है, जो मैक्रो का समर्थन करने वाली स्प्रेडशीट फ़ाइल का प्रकार है। |
|
|  | [XLSB](#XLSB) | Excel बाइनरी स्प्रेडशीट (.xlsb) को दर्शाता है, जो Excel बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है। |
|
|  | [CSV](#CSV) | कॉमा सेपरेटेड वैल्यूज़ फ़ाइल (.csv) को दर्शाता है, जो साधारण टेक्स्ट फ़ाइलें हैं जिनमें कॉमा‑सेपरेटेड डेटा रिकॉर्ड होते हैं। |
|
|  | [TSV](#TSV) | टैब सेपरेटेड वैल्यूज़ फ़ाइल (.tsv) को दर्शाता है, जो साधारण टेक्स्ट फ़ॉर्मेट में टैब द्वारा अलग किए गए डेटा को दर्शाती है। |
|
|  | [ODS](#ODS) | OpenDocument स्प्रेडशीट (.ods) को दर्शाता है, जो उपयोगकर्ता द्वारा संपादन योग्य OpenDocument स्प्रेडशीट दस्तावेज़ फ़ॉर्मेट को दर्शाता है। |
|
|  | [FODS](#FODS) | OpenDocument फ्लैट XML स्प्रेडशीट (.fods) को दर्शाता है। |
|
|  | [OTS](#OTS) | OpenDocument स्प्रेडशीट टेम्पलेट (.ots) को दर्शाता है। |
|
|  | [XLAM](#XLAM) | Microsoft Excel ऐड-इन (.xlam) का प्रतिनिधित्व करता है। |
|
|  | [XLTM](#XLTM) | Microsoft Excel मैक्रो-सक्षम टेम्पलेट (.xltm) का प्रतिनिधित्व करता है, जो Microsoft Excel द्वारा मैक्रो-सक्षम टेम्पलेट फ़ाइलों के रूप में उत्पन्न फ़ाइलों का प्रतिनिधित्व करता है। |
|
|  | [XLT](#XLT) | Microsoft Excel टेम्पलेट (.xlt) का प्रतिनिधित्व करता है, जो Microsoft Excel के साथ बनाई गई टेम्पलेट फ़ाइलें हैं, एक स्प्रेडशीट एप्लिकेशन जो Microsoft Office सूट का हिस्सा है। |
|
|  | [XLTX](#XLTX) | Excel Open XML स्प्रेडशीट टेम्पलेट (.xltx) का प्रतिनिधित्व करता है, जो Office OpenXML फ़ाइल फ़ॉर्मेट विनिर्देशों पर आधारित Microsoft Excel टेम्पलेट्स का प्रतिनिधित्व करता है। |
|
|  | [SXC](#SXC) | StarOffice Calc स्प्रेडशीट (.sxc) का प्रतिनिधित्व करता है। |
|
|  | [MPP](#MPP) | Microsoft Project फ़ाइल (.mpp) का प्रतिनिधित्व करता है, जो एक Microsoft Project डेटा फ़ाइल है जो परियोजना प्रबंधन से संबंधित जानकारी को एकीकृत रूप में संग्रहीत करती है। |
|
|  | [MPT](#MPT) | Microsoft Project टेम्पलेट (.mpt) का प्रतिनिधित्व करता है, जिसमें .MPP फ़ाइलें बनाने के लिए मूल जानकारी और संरचना के साथ दस्तावेज़ सेटिंग्स शामिल हैं। |
|
|  | [MPX](#MPX) | Microsoft Project एक्सचेंज फ़ाइल (.mpx) का प्रतिनिधित्व करता है, जो ASCII फ़ाइल फ़ॉर्मेट है जो Microsoft Project (MSP) और अन्य अनुप्रयोगों के बीच परियोजना जानकारी स्थानांतरित करने के लिए उपयोग होता है जो MPX फ़ाइल फ़ॉर्मेट का समर्थन करते हैं, जैसे Primavera Project Planner, Sciforma, और Timerline Precision Estimating। |
|
|  | [AS](#AS) | ActionScript फ़ाइल (.as) का प्रतिनिधित्व करता है। |
|
|  | [AS_3](#AS-3) | ActionScript फ़ाइल (.as3) का प्रतिनिधित्व करता है। |
|
|  | [ASM](#ASM) | Assembly Language स्रोत कोड फ़ाइल (.asm) का प्रतिनिधित्व करता है। |
|
|  | [BAT](#BAT) | DOS बैच फ़ाइल (.bat) का प्रतिनिधित्व करता है। |
|
|  | [C](#C) | C/C++ स्रोत कोड फ़ाइल (.c) का प्रतिनिधित्व करता है। |
|
|  | [CC](#CC) | C++ स्रोत कोड फ़ाइल (.cc) का प्रतिनिधित्व करता है। |
|
|  | [CMAKE](#CMAKE) | CMake फ़ाइल (.cmake) का प्रतिनिधित्व करता है। |
|
|  | [CPP](#CPP) | C++ स्रोत कोड फ़ाइल (.cpp) का प्रतिनिधित्व करता है। |
|
|  | [CS](#CS) | C# स्रोत कोड फ़ाइल (.cs) का प्रतिनिधित्व करता है, जो C# प्रोग्रामिंग भाषा के लिए स्रोत कोड फ़ाइल है। |
|
|  | [VB](#VB) | Visual Basic प्रोजेक्ट आइटम फ़ाइल (.vb) का प्रतिनिधित्व करता है, जो Visual Basic भाषा में बनाई गई स्रोत कोड फ़ाइल है। |
|
|  | [CSS](#CSS) | Cascading Style Sheet (.css) फ़ाइल का प्रतिनिधित्व करता है। |
|
|  | [CXX](#CXX) | C++ स्रोत कोड फ़ाइल (.cxx) का प्रतिनिधित्व करता है। |
|
|  | [DIFF](#DIFF) | पैच फ़ाइल (.diff) का प्रतिनिधित्व करता है। |
|
|  | [ERB](#ERB) | Ruby ERB स्क्रिप्ट (.erb) का प्रतिनिधित्व करता है। |
|
|  | [GROOVY](#GROOVY) | Groovy स्रोत कोड फ़ाइल (.groovy) का प्रतिनिधित्व करता है। |
|
|  | [H](#H) | C/C++/Objective-C हेडर फ़ाइल (.h) का प्रतिनिधित्व करता है। |
|
|  | [HAML](#HAML) | Haml स्रोत कोड फ़ाइल (.haml) का प्रतिनिधित्व करता है। |
|
|  | [HH](#HH) | एक C++ हेडर फ़ाइल (.hh) का प्रतिनिधित्व करता है। |
|
|  | [JAVA](#JAVA) | एक जावा सोर्स कोड फ़ाइल (.java) का प्रतिनिधित्व करता है। |
|
|  | [JS](#JS) | एक जावास्क्रिप्ट फ़ाइल (.js) का प्रतिनिधित्व करता है। |
|
|  | [JSON](#JSON) | एक जावास्क्रिप्ट ऑब्जेक्ट नोटेशन फ़ाइल (.json) का प्रतिनिधित्व करता है। |
|
|  | [LESS](#LESS) | एक LESS स्टाइल शीट (.less) फ़ाइल का प्रतिनिधित्व करता है। |
|
|  | [LOG](#LOG) | एक लॉग फ़ाइल (.log) का प्रतिनिधित्व करता है। |
|
|  | [M](#M) | एक ऑब्जेक्टिव‑C इम्प्लीमेंटेशन फ़ाइल (.m) का प्रतिनिधित्व करता है। |
|
|  | [MAKE](#MAKE) | एक Xcode मेकफ़ाइल स्क्रिप्ट (.make) का प्रतिनिधित्व करता है। |
|
|  | [MD](#MD) | एक मार्कडाउन डॉक्यूमेंटेशन फ़ाइल (.md) का प्रतिनिधित्व करता है। |
|
|  | [ML](#ML) | एक ML सोर्स कोड फ़ाइल (.ml) का प्रतिनिधित्व करता है। |
|
|  | [MM](#MM) | एक ऑब्जेक्टिव‑C++ सोर्स फ़ाइल (.mm) का प्रतिनिधित्व करता है। |
|
|  | [PHP](#PHP) | एक PHP सोर्स कोड फ़ाइल (.php) का प्रतिनिधित्व करता है। |
|
|  | [PL](#PL) | एक पर्ल स्क्रिप्ट (.pl) का प्रतिनिधित्व करता है। |
|
|  | [PROPERTIES](#PROPERTIES) | एक जावा प्रॉपर्टीज़ फ़ाइल (.properties) का प्रतिनिधित्व करता है। |
|
|  | [PY](#PY) | एक पाइथन स्क्रिप्ट (.py) का प्रतिनिधित्व करता है। |
|
|  | [RB](#RB) | एक रूबी सोर्स कोड (.rb) फ़ाइल का प्रतिनिधित्व करता है। |
|
|  | [RST](#RST) | एक reStructuredText फ़ाइल (.rst) का प्रतिनिधित्व करता है। |
|
|  | [SASS](#SASS) | एक सिंटैक्टिकली ऑसम स्टाइलशीट्स फ़ाइल (.sass) का प्रतिनिधित्व करता है। |
|
|  | [SCALA](#SCALA) | एक स्काला सोर्स कोड फ़ाइल (.scala) का प्रतिनिधित्व करता है। |
|
|  | [SCM](#SCM) | एक स्कीम सोर्स कोड फ़ाइल (.scm) का प्रतिनिधित्व करता है। |
|
|  | [SCRIPT](#SCRIPT) | एक जेनरिक स्क्रिप्ट फ़ाइल (.script) का प्रतिनिधित्व करता है। |
|
|  | [SH](#SH) | एक बैश शेल स्क्रिप्ट (.sh) का प्रतिनिधित्व करता है। |
|
|  | [SML](#SML) | एक स्टैंडर्ड ML सोर्स कोड फ़ाइल (.sml) का प्रतिनिधित्व करता है। |
|
|  | [SQL](#SQL) | एक स्ट्रक्चर्ड क्वेरी लैंग्वेज डेटा फ़ाइल (.sql) का प्रतिनिधित्व करता है। |
|
|  | [VIM](#VIM) | एक Vim सेटिंग्स फ़ाइल (.vim) का प्रतिनिधित्व करता है। |
|
|  | [YAML](#YAML) | YAML दस्तावेज़ (.yaml) का प्रतिनिधित्व करता है। |
|
|  | [DOC](#DOC) | Microsoft Word दस्तावेज़ (.doc) फ़ाइल का प्रतिनिधित्व करता है। |
|
|  | [DOCX](#DOCX) | Microsoft Word Open XML दस्तावेज़ (.docx) फ़ाइल का प्रतिनिधित्व करता है। |
|
|  | [CHM](#CHM) | Microsoft संकलित HTML हेल्प फ़ाइल (.chm) का प्रतिनिधित्व करता है। |
|
|  | [DOCM](#DOCM) | Word Open XML मैक्रो-सक्षम दस्तावेज़ (.docm) फ़ाइल का प्रतिनिधित्व करता है। |
|
|  | [DOT](#DOT) | Word दस्तावेज़ टेम्पलेट (.dot) फ़ाइल का प्रतिनिधित्व करता है। |
|
|  | [DOTX](#DOTX) | Word Open XML दस्तावेज़ टेम्पलेट (.dotx) फ़ाइल का प्रतिनिधित्व करता है। |
|
|  | [DOTM](#DOTM) | Word Open XML मैक्रो-सक्षम दस्तावेज़ टेम्पलेट (.dotm) फ़ाइल का प्रतिनिधित्व करता है। |
|
|  | [RTF](#RTF) | Rich Text Format फ़ाइल (.rtf) का प्रतिनिधित्व करता है। |
|
|  | [TXT](#TXT) | सादा टेक्स्ट फ़ाइल (.txt) का प्रतिनिधित्व करता है। |
|
|  | [ODT](#ODT) | OpenDocument टेक्स्ट दस्तावेज़ (.odt) का प्रतिनिधित्व करता है। |
|
|  | [OTT](#OTT) | OpenDocument दस्तावेज़ टेम्पलेट (.ott) का प्रतिनिधित्व करता है। |
|
|  | [VCF](#VCF) | vCard फ़ाइल (.vcf) का प्रतिनिधित्व करता है, जो संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल फ़ॉर्मेट है। |
|
|  | [AI](#AI) | Adobe Illustrator फ़ाइल (.ai) का प्रतिनिधित्व करता है, जो Adobe Illustrator चित्रों के लिए एक फ़ाइल फ़ॉर्मेट है। |
|
|  | [PSM1](#PSM1) | PowerShell स्क्रिप्ट मॉड्यूल फ़ाइल (.psm1) का प्रतिनिधित्व करता है। |
|
|  | [PS1](#PS1) | PowerShell स्क्रिप्ट फ़ाइल (.ps1) का प्रतिनिधित्व करता है। |
|
|  | [PSD1](#PSD1) | PowerShell स्क्रिप्ट मॉड्यूल मैनिफेस्ट फ़ाइल (.psd1) का प्रतिनिधित्व करता है। |
|
## Methods

| Method | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | फ़ाइल एक्सटेंशन को फ़ाइल प्रकार से मैप करता है। |
|
|  | [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | फ़ाइल नाम या फ़ाइल पथ से फ़ाइल एक्सटेंशन निकालता है और उसे फ़ाइल प्रकार से मैप करता है। |
|
|  | [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | फ़ाइल मीडिया प्रकार को फ़ाइल प्रकार से मैप करता है। |
|
|  | [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है। |
|
|  | [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है। |
|
|  | [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है। |
|
|  | [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है। |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | समर्थित फ़ाइल प्रकारों को पुनः प्राप्त करता है। |
|
|  | [detectCharset(String filePath)](#detectCharset-java.lang.String-) | पथ द्वारा टेक्स्ट [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), और [CSV](../../com.groupdocs.viewer/filetype#CSV) फ़ाइलों का कैरेक्टर सेट पता लगाने का प्रयास करता है। |
|
|  | [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | स्ट्रीम द्वारा टेक्स्ट [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), और [CSV](../../com.groupdocs.viewer/filetype#CSV) फ़ाइल का कैरेक्टर सेट पता लगाने का प्रयास करता है। |
|
|  | [getFileFormat()](#getFileFormat--) | फ़ाइल फ़ॉर्मेट का नाम प्राप्त करता है, उदाहरण के लिए, "Microsoft Word Document"। |
|
|  | [getExtension()](#getExtension--) | फ़ाइल एक्सटेंशन उपसर्ग प्राप्त करता है (जिसमें अवधि "." शामिल है), उदाहरण के लिए, ".doc"। |
|
|  | [toString()](#toString--) | वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


अज्ञात फ़ाइल प्रकार का प्रतिनिधित्व करता है।


### ZIP {#ZIP}
```
public static final FileType ZIP
```


ज़िप्ड फ़ाइल (.zip) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों या निर्देशिकाओं को रख सकती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/compression/zip)।


### TAR {#TAR}
```
public static final FileType TAR
```


एक या अधिक फ़ाइलों को एकत्र करने के लिए बनाई गई समेकित Unix फ़ाइल संग्रह (.tar) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/compression/tar)।


### XZ {#XZ}
```
public static final FileType XZ
```


LZMA एल्गोरिदम पर आधारित उच्च अनुपात संपीड़न एल्गोरिदम का उपयोग करके संकुचित XZ फ़ाइल (.xz) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/xz)।


### TXZ {#TXZ}
```
public static final FileType TXZ
```


एकीकृत Unix फ़ाइल अभिलेख (.txz, .tar.xz) का प्रतिनिधित्व करता है, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए बनाया गया है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/txz)।


### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


एकीकृत Unix फ़ाइल अभिलेख (.txz, .tar.xz) का प्रतिनिधित्व करता है, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए बनाया गया है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/txz)।


### TGZ {#TGZ}
```
public static final FileType TGZ
```


एकीकृत Unix फ़ाइल अभिलेख (.tgz, .tar.gz) का प्रतिनिधित्व करता है, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए बनाया गया है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/tgz)।


### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


एकीकृत Unix फ़ाइल अभिलेख (.tgz, .tar.gz) का प्रतिनिधित्व करता है, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए बनाया गया है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/tgz)।


### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


BZIP2 ओपन-सोर्स संपीड़न विधि का उपयोग करके उत्पन्न Bzip2 संकुचित फ़ाइल (.bz2) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/compression/bz2)।


### RAR {#RAR}
```
public static final FileType RAR
```


RAR (WINRAR संस्करण 4) संपीड़न विधि का उपयोग करके उत्पन्न Roshal Archive (.rar) संकुचित फ़ाइल का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/compression/rar)।


### GZ {#GZ}
```
public static final FileType GZ
```


gzip संपीड़न अनुप्रयोग के साथ बनाई गई Gnu Zipped फ़ाइल (.gz) संकुचित फ़ाइल का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/compression/gz)।


### GZIP {#GZIP}
```
public static final FileType GZIP
```


Unix सिस्टम में उपयोग किए जाने वाले Compress प्रोग्राम को बदलने के लिए एक मुफ्त उपयोगिता के रूप में प्रस्तुत Gnu Zipped फ़ाइल (.gzip) संकुचित फ़ाइल का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/compression/gz)।


### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


7Zip (.7z, .7zip) फ़ाइल का प्रतिनिधित्व करता है, जो LZMA और LZMA2 संपीड़न के साथ एक मुफ्त ओपन-सोर्स आर्काइवर है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/compression/7z/)।


### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio एक सामान्य फ़ाइल आर्काइवर उपयोगिता और इसका संबंधित फ़ाइल फ़ॉर्मेट है। यह मुख्यतः Unix‑समान कंप्यूटर ऑपरेटिंग सिस्टम पर स्थापित होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/compression/cpio)।


### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


ZST फ़ाइल एक संकुचित फ़ाइल है जो Zstandard (zstd) संपीड़न एल्गोरिदम से उत्पन्न होती है। यह एक हानि‑रहित संपीड़न द्वारा बनाई गई संकुचित फ़ाइल है। ZST फ़ाइलों का उपयोग विभिन्न प्रकार की फ़ाइलों जैसे डेटाबेस, फ़ाइल सिस्टम, नेटवर्क और गेम्स को संपीड़ित करने के लिए किया जा सकता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/compression/zst/)।


### TZST {#TZST}
```
public static final FileType TZST
```


TZST फ़ाइलें (.tar.zst, .tzst) Zstandard अभिलेख (ZST) हैं, जो आंतरिक रूप से एक एकीकृत Unix फ़ाइल अभिलेख (Tar) शामिल करती हैं, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए Unix-आधारित उपयोगिता के साथ बनाई गई हैं।


### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


TZST फ़ाइलें (.tar.zst, .tzst) Zstandard अभिलेख (ZST) हैं, जो आंतरिक रूप से एक एकीकृत Unix फ़ाइल अभिलेख (Tar) शामिल करती हैं, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए Unix-आधारित उपयोगिता के साथ बनाई गई हैं।


### ISO {#ISO}
```
public static final FileType ISO
```


ISO ऑप्टिकल डिस्क इमेज एक अनकम्प्रेस्ड अभिलेख डिस्क इमेज फ़ाइल है जो CD या DVD जैसे ऑप्टिकल डिस्क पर संपूर्ण डेटा की सामग्री को दर्शाती है, ISO-9660 मानक पर आधारित।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/compression/iso/)।


### LHA {#LHA}
```
public static final FileType LHA
```


LHA या LZH एक फ्रीवेयर संपीड़न उपयोगिता और संबंधित फ़ाइल स्वरूप है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/compression/lzh/)।


### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (या CAB) माइक्रोसॉफ्ट विंडोज़ के लिए एक अभिलेख-फ़ाइल स्वरूप है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://en.wikipedia.org/wiki/Cabinet_(file_format))।


### DXF {#DXF}
```
public static final FileType DXF
```


Drawing Exchange Format फ़ाइल (.dxf) का प्रतिनिधित्व करता है, जो AutoCAD ड्रॉइंग फ़ाइल का टैग्ड डेटा प्रतिनिधित्व है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/dxf).


### DWG {#DWG}
```
public static final FileType DWG
```


AutoCAD Drawing Database फ़ाइल (.dwg) का प्रतिनिधित्व करता है, जो 2D और 3D डिज़ाइन डेटा रखने के लिए उपयोग की जाने वाली स्वामित्व बाइनरी फ़ाइलों को दर्शाती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/dwg).


### DWT {#DWT}
```
public static final FileType DWT
```


AutoCAD Drawing Template (.dwt) का प्रतिनिधित्व करता है, जो ड्रॉइंग बनाने के लिए प्रारंभिक बिंदु के रूप में उपयोग की जाने वाली AutoCAD ड्रॉइंग टेम्पलेट फ़ाइल है, जिसे DWG फ़ाइलों के रूप में सहेजा जा सकता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/dwt).


### STL {#STL}
```
public static final FileType STL
```


एक Stereolithography फ़ाइल (.stl) का प्रतिनिधित्व करता है, जो एक अदल‑बदल योग्य फ़ाइल फ़ॉर्मेट है जो त्रि‑आयामी सतह ज्यामिति को दर्शाता है। यह तेज़ प्रोटोटाइपिंग, 3D प्रिंटिंग और कंप्यूटर‑सहायित निर्माण में सामान्यतः उपयोग किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/stl).


### IFC {#IFC}
```
public static final FileType IFC
```


एक Industry Foundation Classes फ़ाइल (.ifc) का प्रतिनिधित्व करता है, जो एक फ़ाइल फ़ॉर्मेट है जो भवन वस्तुओं और उनकी विशेषताओं के आयात और निर्यात के लिए अंतर्राष्ट्रीय मानक स्थापित करता है। यह विभिन्न सॉफ़्टवेयर अनुप्रयोगों के बीच अंतःक्रियाशीलता को सक्षम बनाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/ifc).


### DWF {#DWF}
```
public static final FileType DWF
```


एक Design Web Format फ़ाइल (.dwf) का प्रतिनिधित्व करता है, जो 2D/3D ड्रॉइंग्स को देखने, समीक्षा करने या प्रिंट करने के लिए एक संकुचित फ़ाइल फ़ॉर्मेट है। इसमें डिज़ाइन डेटा के हिस्से के रूप में ग्राफ़िक्स और टेक्स्ट शामिल होते हैं और संपीड़न के कारण फ़ाइल आकार घट जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/dwf).


### FBX {#FBX}
```
public static final FileType FBX
```


Autodesk FBX Interchange फ़ाइल (FilmBoX) (.fbx) का प्रतिनिधित्व करता है, जो एक 3D मॉडल स्वरूप है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/fbx).


### DWFX {#DWFX}
```
public static final FileType DWFX
```


डिज़ाइन वेब फ़ॉर्मेट फ़ाइल XPS (.dwfx) को दर्शाता है, जो 2D/3D ड्रॉइंग्स को XPS दस्तावेज़ के रूप में देखने, समीक्षा करने या प्रिंट करने के लिए एक संकुचित फ़ॉर्मेट है। इसमें डिज़ाइन डेटा के हिस्से के रूप में ग्राफ़िक्स और टेक्स्ट शामिल हैं और संपीड़न के कारण फ़ाइल आकार घटता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/dwfx).


### DGN {#DGN}
```
public static final FileType DGN
```


MicroStation Design फ़ाइल (.dgn) का प्रतिनिधित्व करता है, जो MicroStation और Intergraph Interactive Graphics Design System जैसे CAD अनुप्रयोगों द्वारा बनाई और समर्थित ड्रॉइंग हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/dgn).


### PLT {#PLT}
```
public static final FileType PLT
```


PLT (HPGL) फ़ाइल (.plt) को दर्शाता है, जो Autodesk, Inc. द्वारा प्रस्तुत एक वेक्टर-आधारित प्लॉटर फ़ाइल है। इसमें किसी विशिष्ट CAD फ़ाइल की जानकारी होती है, और सभी छवियों को बिंदुओं के बजाय रेखाओं का उपयोग करके प्रिंट किया जाता है, जिससे उत्पादन में सटीकता और परिशुद्धता सुनिश्चित होती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/cad/plt).


### CF2 {#CF2}
```
public static final FileType CF2
```


Common File Format फ़ाइल (.cf2) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/cf2).


### OBJ {#OBJ}
```
public static final FileType OBJ
```


Wavefront 3D ऑब्जेक्ट फ़ाइल (.obj) का प्रतिनिधित्व करता है, जो Wavefront Technologies द्वारा प्रस्तुत 3D इमेज फ़ाइल है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/3d/obj/).


### HPG {#HPG}
```
public static final FileType HPG
```


एक PLT (HPGL) फ़ाइल (.hpg) का प्रतिनिधित्व करता है।
यह HP ग्राफ़िक्स लैंग्वेज (HPGL) में प्लॉटर फ़ाइलों के लिए उपयोग किया जाने वाला फ़ाइल फ़ॉर्मेट है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/hpg).


### IGS {#IGS}
```
public static final FileType IGS
```


एक Initial Graphics Exchange Specification (IGES) फ़ाइल (.igs) का प्रतिनिधित्व करता है।


### VSD {#VSD}
```
public static final FileType VSD
```


एक Visio Drawing फ़ाइल (.vsd) का प्रतिनिधित्व करता है, जो Microsoft Visio एप्लिकेशन से बनाई गई ड्रॉइंग्स हैं, जो विभिन्न ग्राफ़िकल ऑब्जेक्ट्स और उनके अंतरसंबंधों को दर्शाती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vsd).


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio ड्रॉइंग फ़ाइल (.vsdx) को दर्शाता है, जो Microsoft Office 2013 से शुरू होने वाले Microsoft Visio फ़ाइल फ़ॉर्मेट को दर्शाता है। इसने पहले के Microsoft Visio संस्करणों द्वारा समर्थित बाइनरी फ़ाइल फ़ॉर्मेट (.VSD) को प्रतिस्थापित किया।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vsdx).


### VSS {#VSS}
```
public static final FileType VSS
```


Visio स्टेंसिल फ़ाइल (.vss) को दर्शाता है, जो Microsoft Visio 2007 और उससे पहले बनाए गए स्टेंसिल फ़ाइलें हैं। स्टेंसिल फ़ाइलें ड्रॉइंग ऑब्जेक्ट्स प्रदान करती हैं जिन्हें .VSD Visio ड्रॉइंग में शामिल किया जा सकता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vss).


### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio स्टेंसिल फ़ाइल (.vssx) को दर्शाता है, जो Microsoft Visio 2013 और उसके बाद के संस्करणों से बनाई गई ड्रॉइंग स्टेंसिल हैं। VSSX फ़ाइल फ़ॉर्मेट को Visio 2013 और उसके बाद के संस्करणों में खोला जा सकता है। Visio फ़ाइलें विभिन्न ड्रॉइंग तत्वों जैसे आकार, कनेक्टर, फ्लोचार्ट, नेटवर्क लेआउट, UML डायग्राम आदि को दर्शाने के लिए जानी जाती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vssx).


### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio मैक्रो-सक्षम ड्रॉइंग (.vsdm) को दर्शाता है, जो Microsoft Visio एप्लिकेशन द्वारा बनाए गए ड्रॉइंग फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। VSDM फ़ाइलें OPC/XML ड्रॉइंग हैं जो VSDX के समान हैं, लेकिन फ़ाइल खोलने पर मैक्रो चलाने की क्षमता भी प्रदान करती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vsdm).


### VST {#VST}
```
public static final FileType VST
```


Visio ड्रॉइंग टेम्प्लेट (.vst) को दर्शाता है, जो Microsoft Visio द्वारा बनाई गई वेक्टर इमेज फ़ाइलें हैं। ये आगे की फ़ाइलें बनाने के लिए टेम्प्लेट के रूप में कार्य करती हैं और नई Visio ड्रॉइंग बनाने के लिए उपयोग किए जाने वाले डिफ़ॉल्ट लेआउट और सेटिंग्स को शामिल करती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vst).


### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio ड्रॉइंग टेम्प्लेट (.vstx) को दर्शाता है, जो Microsoft Visio 2013 और उसके बाद के संस्करणों से बनाई गई ड्रॉइंग टेम्प्लेट फ़ाइलें हैं। ये VSTX फ़ाइलें .VSDX फ़ाइलों के रूप में सहेजी गई Visio ड्रॉइंग बनाने के लिए एक प्रारंभिक बिंदु प्रदान करती हैं, जिसमें डिफ़ॉल्ट लेआउट और सेटिंग्स होते हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vstx).


### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio मैक्रो-सक्षम ड्रॉइंग टेम्प्लेट (.vstm) को दर्शाता है, जो Microsoft Visio द्वारा बनाए गए टेम्प्लेट फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। VSTM टेम्प्लेट से बनाई गई फ़ाइलें Visual Basic for Applications (VBA) कोड में विकसित मैक्रो चलाने में सक्षम होती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vstm).


### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio मैक्रो-सक्षम स्टेंसिल फ़ाइल (.vssm) का प्रतिनिधित्व करता है, जो Microsoft Visio स्टेंसिल फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। जब VSSM फ़ाइल खोली जाती है, तो इच्छित स्वरूपण और आकृति के स्थान निर्धारण को प्राप्त करने के लिए मैक्रो चलाए जा सकते हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vssm).


### VSX {#VSX}
```
public static final FileType VSX
```


Visio स्टेंसिल XML फ़ाइल (.vsx) का प्रतिनिधित्व करता है, जो उन स्टेंसिलों को दर्शाता है जिनमें ड्रॉइंग और आकृतियाँ होती हैं जो Microsoft Visio में आरेख बनाने के लिए उपयोग की जाती हैं। VSX फ़ाइलें XML फ़ाइल फ़ॉर्मेट में सहेजी जाती हैं और Visio 2013 तक समर्थित थीं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vsx).


### VTX {#VTX}
```
public static final FileType VTX
```


Visio टेम्पलेट XML फ़ाइल (.vtx) का प्रतिनिधित्व करता है, जो एक Microsoft Visio ड्रॉइंग टेम्पलेट है जिसे XML फ़ाइल फ़ॉर्मेट में डिस्क पर सहेजा जाता है। टेम्पलेट कई Visio फ़ाइलों को समान सेटिंग्स के साथ बनाने के लिए बुनियादी सेटिंग्स प्रदान करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vtx).


### VDW {#VDW}
```
public static final FileType VDW
```


एक Visio Web Drawing (.vdw) का प्रतिनिधित्व करता है, जो वेब ड्रॉइंग को रेंडर करने के लिए आवश्यक स्ट्रीम्स और स्टोरेज को निर्दिष्ट करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/web/vdw).


### VDX {#VDX}
```
public static final FileType VDX
```


Visio ड्रॉइंग XML फ़ाइल (.vdx) का प्रतिनिधित्व करता है, जो Microsoft Visio में बनाई गई किसी भी ड्रॉइंग या चार्ट को दर्शाता है लेकिन .VDX एक्सटेंशन के साथ XML फ़ॉर्मेट में सहेजा जाता है। Visio ड्रॉइंग XML फ़ाइल Microsoft द्वारा विकसित Visio सॉफ़्टवेयर में बनाई जाती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vdx).


### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook फ़ाइल (.epub) का प्रतिनिधित्व करता है, जो एक ई-बुक फ़ाइल फ़ॉर्मेट है जो प्रकाशकों और उपभोक्ताओं के लिए एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। यह फ़ॉर्मेट कई ई-रीडर्स और सॉफ़्टवेयर अनुप्रयोगों द्वारा समर्थित है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/ebook/epub).


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket eBook (.mobi) का प्रतिनिधित्व करता है, जो सबसे अधिक उपयोग किए जाने वाले ईबुक फ़ाइल फ़ॉर्मेट में से एक है। यह फ़ॉर्मेट पुराने OEB (Open Ebook Format) फ़ॉर्मेट का एक उन्नयन है और Mobipocket Reader के लिए एक स्वामित्व फ़ॉर्मेट के रूप में उपयोग किया गया था।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/ebook/mobi).


### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Amazon Kindle Format 8 (KF8) ईबुक वह डिजिटल फ़ाइल फ़ॉर्मेट है जो Amazon Kindle डिवाइसों के लिए विकसित किया गया है। यह फ़ॉर्मेट पुराने AZW फ़ाइलों का एक उन्नयन है और केवल Kindle Fire डिवाइसों पर उपयोग किया जाता है, साथ ही पूर्वज फ़ाइल फ़ॉर्मेट यानी MOBI और AZW के साथ backward compatibility रखता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/ebook/azw3).


### MSG {#MSG}
```
public static final FileType MSG
```


एक Outlook Mail Message (.msg) का प्रतिनिधित्व करता है, जो Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, अपॉइंटमेंट या अन्य कार्यों को संग्रहीत करने के लिए उपयोग किया जाने वाला फ़ाइल फ़ॉर्मेट है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/msg).


### EML {#EML}
```
public static final FileType EML
```


E-Mail संदेश (.eml) का प्रतिनिधित्व करता है, जो Outlook और अन्य संबंधित अनुप्रयोगों का उपयोग करके सहेजे गए ईमेल संदेशों को दर्शाता है। लगभग सभी ईमेल क्लाइंट इस फ़ाइल फ़ॉर्मेट का समर्थन करते हैं क्योंकि यह RFC-822 इंटरनेट संदेश फ़ॉर्मेट मानक के अनुरूप है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/eml).


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail संदेश (.emlx) का प्रतिनिधित्व करता है, जिसे Apple द्वारा लागू और विकसित किया गया है। Apple Mail एप्लिकेशन ईमेल निर्यात करने के लिए EMLX फ़ाइल फ़ॉर्मेट का उपयोग करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/emlx).


### PST {#PST}
```
public static final FileType PST
```


एक Outlook Personal Information Store फ़ाइल (.pst) का प्रतिनिधित्व करता है, जो Outlook Personal Storage Files (जिन्हें Personal Storage Table भी कहा जाता है) को दर्शाता है, जो विभिन्न उपयोगकर्ता जानकारी संग्रहीत करती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/pst).


### OST {#OST}
```
public static final FileType OST
```


एक Outlook Offline Data फ़ाइल (.ost) का प्रतिनिधित्व करता है, जो उपयोगकर्ता के मेलबॉक्स डेटा को ऑफ़लाइन मोड में स्थानीय मशीन पर, Exchange Server के साथ Microsoft Outlook के पंजीकरण के बाद, संग्रहीत करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/ost).


### TIF {#TIF}
```
public static final FileType TIF
```


Tagged Image File (.tif) का प्रतिनिधित्व करता है, जो रास्टर इमेजेज़ को दर्शाता है जो विभिन्न उपकरणों पर उपयोग के लिए बनाए गए हैं जो इस फ़ाइल फ़ॉर्मेट मानक का पालन करते हैं। यह कई रंग स्थानों में द्वि-स्तरीय, ग्रेस्केल, पैलेट-रंग, और पूर्ण-रंग इमेज डेटा का वर्णन करने में सक्षम है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/tiff).


### TIFF {#TIFF}
```
public static final FileType TIFF
```


Tagged Image File Format (.tiff) का प्रतिनिधित्व करता है, जो रास्टर इमेजेज़ को दर्शाता है जो विभिन्न उपकरणों पर उपयोग के लिए बनाए गए हैं जो इस फ़ाइल फ़ॉर्मेट मानक का पालन करते हैं। यह कई रंग स्थानों में द्वि-स्तरीय, ग्रेस्केल, पैलेट-रंग, और पूर्ण-रंग इमेज डेटा का वर्णन करने में सक्षम है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/tiff).


### JPG {#JPG}
```
public static final FileType JPG
```


JPEG इमेज (.jpg) का प्रतिनिधित्व करता है, जो एक प्रकार का इमेज फ़ॉर्मेट है जिसे लॉसी कम्प्रेशन विधि से सहेजा जाता है। कम्प्रेशन के परिणामस्वरूप आउटपुट इमेज, स्टोरेज आकार और इमेज गुणवत्ता के बीच संतुलन बनाती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/jpeg).


### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG इमेज (.jpeg) का प्रतिनिधित्व करता है, जो एक प्रकार का इमेज फ़ॉर्मेट है जिसे लॉसी कम्प्रेशन विधि से सहेजा जाता है। कम्प्रेशन के परिणामस्वरूप आउटपुट इमेज, स्टोरेज आकार और इमेज गुणवत्ता के बीच संतुलन बनाती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/jpeg).


### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG फ़ाइल इंटरचेंज फ़ॉर्मेट (.jfif) एक इमेज है जिसे प्लेटफ़ॉर्मों के बीच तेज़ आदान‑प्रदान के लिए विकसित किया गया था। यह फ़ॉर्मेट JPEG कम्प्रेशन का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/jfif).


### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) का प्रतिनिधित्व करता है, जो एक प्रकार का रास्टर इमेज फ़ाइल फ़ॉर्मेट है जो लॉसलेस कम्प्रेशन का उपयोग करता है। यह फ़ॉर्मेट Graphics Interchange Format (GIF) के विकल्प के रूप में बनाया गया था और इसमें कोई कॉपीराइट प्रतिबंध नहीं है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/png).


### GIF {#GIF}
```
public static final FileType GIF
```


Graphical Interchange Format फ़ाइल (.gif) का प्रतिनिधित्व करता है, जो एक अत्यधिक संकुचित इमेज प्रकार है। प्रत्येक इमेज के लिए, GIF सामान्यतः प्रति पिक्सेल अधिकतम 8 बिट्स और इमेज में कुल 256 रंगों की अनुमति देता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/gif).


### APNG {#APNG}
```
public static final FileType APNG
```


Animated Portable Network Graphic (.apng) का प्रतिनिधित्व करता है, जो PNG फ़ॉर्मेट का एक विस्तार है जो एनीमेशन का समर्थन करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/apng).


### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap इमेज फ़ाइल (.bmp) का प्रतिनिधित्व करता है, जिसका उपयोग बिटमैप डिजिटल इमेज को संग्रहीत करने के लिए किया जाता है। ये इमेज ग्राफ़िक्स एडेप्टर से स्वतंत्र होते हैं और इन्हें डिवाइस इंडिपेंडेंट बिटमैप (DIB) फ़ाइल फ़ॉर्मेट भी कहा जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/bmp).


### ICO {#ICO}
```
public static final FileType ICO
```


Icon फ़ाइल (.ico) का प्रतिनिधित्व करता है, जो माइक्रोसॉफ्ट विंडोज पर एप्लिकेशन के प्रतिनिधित्व के लिए आइकन के रूप में उपयोग की जाने वाली इमेज फ़ाइल प्रकार है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/ico).


### TGA {#TGA}
```
public static final FileType TGA
```


Truevision TGA (TARGA) फ़ाइल का प्रतिनिधित्व करता है, जिसका उपयोग TRUEVISION द्वारा विकसित बिटमैप डिजिटल इमेज को संग्रहीत करने के लिए किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/tga).


### JP_2 {#JP-2}
```
public static final FileType JP_2
```


JPEG 2000 कोर इमेज फ़ाइल (.jp2) का प्रतिनिधित्व करता है, जो एक इमेज कोडिंग सिस्टम और अत्याधुनिक इमेज कम्प्रेशन मानक है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/jp2).


### JPF {#JPF}
```
public static final FileType JPF
```


JPEG 2000 इमेज फ़ाइल (.jpf) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/image/jpf).


### JPX {#JPX}
```
public static final FileType JPX
```


JPEG 2000 इमेज फ़ाइल (.jpx) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/jpx).


### JPM {#JPM}
```
public static final FileType JPM
```


JPEG 2000 इमेज फ़ाइल (.jpm) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/jpm).


### J2C {#J2C}
```
public static final FileType J2C
```


JPEG 2000 कोड InputStream (.j2c) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/j2c).


### J2K {#J2K}
```
public static final FileType J2K
```


JPEG 2000 कोड स्ट्रीम (.j2k) का प्रतिनिधित्व करता है, जो DCT कम्प्रेशन के बजाय वेवलेट कम्प्रेशन का उपयोग करके संकुचित इमेज है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/j2k).


### JPC {#JPC}
```
public static final FileType JPC
```


JPEG 2000 कोड स्ट्रीम (.jpc) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/jpc).


### JLS {#JLS}
```
public static final FileType JLS
```


JPEG-LS (JLS) फ़ाइल (.jls) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/jls).


### DIB {#DIB}
```
public static final FileType DIB
```


Device Independent Bitmap फ़ाइल (.dib) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/dib).


### WMF {#WMF}
```
public static final FileType WMF
```


Windows Metafile (.wmf) का प्रतिनिधित्व करता है, जो वेक्टर और बिटमैप-फ़ॉर्मेट इमेज डेटा को संग्रहीत करने के लिए Microsoft Windows Metafile (WMF) को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/wmf).


### WMZ {#WMZ}
```
public static final FileType WMZ
```


Compressed Windows Metafile (.wmz) का प्रतिनिधित्व करता है, जो वेक्टर और बिटमैप-फ़ॉर्मेट इमेज डेटा को संग्रहीत करने के लिए GZIP आर्काइव में संकुचित Microsoft Windows Metafile (WMF) को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/wmz#compressed_windows_metafile).


### EMF {#EMF}
```
public static final FileType EMF
```


Enhanced Windows Metafile (.emf) का प्रतिनिधित्व करता है, जो ग्राफ़िकल इमेज को डिवाइस‑इंडिपेंडेंट रूप में दर्शाता है। EMF के मेटाफाइल में क्रमिक क्रम में परिवर्तनीय‑लंबाई वाले रिकॉर्ड होते हैं जो किसी भी आउटपुट डिवाइस पर पार्स करने के बाद संग्रहीत इमेज को रेंडर कर सकते हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/emf).


### EMZ {#EMZ}
```
public static final FileType EMZ
```


Windows Compressed Enhanced Metafile (.emz) को दर्शाता है, जो ग्राफ़िकल छवियों को डिवाइस-स्वतंत्र रूप से GZIP द्वारा संकुचित करता है। EMF के मेटाफाइल में क्रमिक क्रम में परिवर्तनीय-लंबाई वाले रिकॉर्ड होते हैं जो किसी भी आउटपुट डिवाइस पर पार्स करने के बाद संग्रहीत छवि को रेंडर कर सकते हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/emz).


### WEBP {#WEBP}
```
public static final FileType WEBP
```


WebP Image (.webp) को दर्शाता है, जो लॉसलेस और लॉसी संपीड़न पर आधारित एक आधुनिक रास्टर वेब इमेज फ़ाइल फ़ॉर्मेट है। यह समान इमेज क्वालिटी प्रदान करता है जबकि इमेज आकार को काफी कम करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/webp).


### DNG {#DNG}
```
public static final FileType DNG
```


Digital Negative Specification (.dng) को दर्शाता है, जो कच्ची फ़ाइलों के संग्रह के लिए उपयोग किया जाने वाला डिजिटल कैमरा इमेज फ़ॉर्मेट है। इसे Adobe ने सितंबर 2004 में विकसित किया था और यह मुख्य रूप से डिजिटल फ़ोटोग्राफी के लिए उपयोग किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/dng).


### CDR {#CDR}
```
public static final FileType CDR
```


CorelDraw Vector Graphic Drawing (.cdr) को दर्शाता है, जो CorelDRAW के साथ मूल रूप से निर्मित एक वेक्टर ड्रॉइंग इमेज फ़ाइल है, जो डिजिटल रूप से एन्कोडेड और संकुचित छवियों को संग्रहीत करने के लिए उपयोग होती है। एक CDR ड्रॉइंग फ़ाइल में टेक्स्ट, लाइन्स, शैप्स, इमेजेज, रंग और इफ़ेक्ट्स होते हैं जो इमेज सामग्री की वेक्टर प्रतिनिधित्व के लिए होते हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/cdr).


### CMX {#CMX}
```
public static final FileType CMX
```


Corel Exchange (.cmx) को दर्शाता है, जो एक ड्राइंग इमेज फ़ाइल है जिसमें वेक्टर ग्राफ़िक्स और बिटमैप ग्राफ़िक्स दोनों हो सकते हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/cmx).


### DJVU {#DJVU}
```
public static final FileType DJVU
```


DjVu Image (.djvu) को दर्शाता है, जो स्कैन किए गए दस्तावेज़ों और पुस्तकों के लिए अभिप्रेत एक ग्राफ़िक्स फ़ाइल फ़ॉर्मेट है, विशेष रूप से उन फ़ाइलों के लिए जिनमें पाठ, चित्र, इमेज और फ़ोटोग्राफ़ का संयोजन होता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/djvu).


### CGM {#CGM}
```
public static final FileType CGM
```


Computer Graphics Metafile (.cgm) को दर्शाता है, जो एक मुफ्त, प्लेटफ़ॉर्म-स्वतंत्र, अंतर्राष्ट्रीय मानक मेटाफाइल फ़ॉर्मेट है, जो वेक्टर ग्राफ़िक्स (2D), रास्टर ग्राफ़िक्स और टेक्स्ट को संग्रहीत और विनिमय करने के लिए उपयोग होता है। CGM ऑब्जेक्ट-ओरिएंटेड दृष्टिकोण का उपयोग करता है और इमेज उत्पादन के लिए कई फ़ंक्शन प्रदान करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/page-description-language/cgm).


### PCL {#PCL}
```
public static final FileType PCL
```


Printer Command Language Document (.pcl) को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/page-description-language/pcl).


### PSD {#PSD}
```
public static final FileType PSD
```


Adobe Photoshop Document (.psd) को दर्शाता है, जो Adobe Photoshop का मूल फ़ाइल फ़ॉर्मेट है जो ग्राफ़िक्स डिज़ाइनिंग और विकास के लिए उपयोग होता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/psd).


### PSB {#PSB}
```
public static final FileType PSB
```


Photoshop Large Document Format (.psb) को दर्शाता है, जो Adobe Photoshop में ग्राफ़िक्स डिज़ाइनिंग और विकास के लिए उपयोग होता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/psb).


### DCM {#DCM}
```
public static final FileType DCM
```


DICOM Image (.dcm) को दर्शाता है, जो एक डिजिटल इमेज है जो रोगियों की चिकित्सा जानकारी जैसे MRI, CT स्कैन और अल्ट्रासाउंड इमेज को संग्रहीत करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/dcm).


### PS {#PS}
```
public static final FileType PS
```


PostScript File (.ps) को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/page-description-language/ps).


### EPS {#EPS}
```
public static final FileType EPS
```


Encapsulated PostScript File (.eps) को दर्शाता है, जो एक Encapsulated PostScript भाषा प्रोग्राम का वर्णन करता है जो एक पृष्ठ की उपस्थिति को परिभाषित करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/page-description-language/eps).


### ODG {#ODG}
```
public static final FileType ODG
```


OpenDocument Graphic File (.odg) को दर्शाता है, जो Apache OpenOffice के Draw एप्लिकेशन द्वारा ड्राइंग तत्वों को वेक्टर इमेज के रूप में संग्रहीत करने के लिए उपयोग होता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/odg).


### FODG {#FODG}
```
public static final FileType FODG
```


Flat XML ODF Template (.fodg) को दर्शाता है, जो Apache OpenOffice के Draw एप्लिकेशन द्वारा ड्राइंग तत्वों को वेक्टर इमेज के रूप में संग्रहीत करने के लिए उपयोग होता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/fodg).


### SVG {#SVG}
```
public static final FileType SVG
```


Scalable Vector Graphics File (.svg) को दर्शाता है, जो एक Scalable Vector Graphics फ़ाइल है जो इमेज की उपस्थिति का वर्णन करने के लिए XML-आधारित टेक्स्ट फ़ॉर्मेट का उपयोग करती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/page-description-language/svg).


### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Compressed Scalable Vector Graphics File (.svgz) को दर्शाता है, जो एक Scalable Vector Graphics फ़ाइल है जो XML-आधारित टेक्स्ट फ़ॉर्मेट, GZIP द्वारा संकुचित, का उपयोग करके इमेज की उपस्थिति का वर्णन करती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/svgz).


### OTG {#OTG}
```
public static final FileType OTG
```


OpenDocument Graphic Template (.otg) को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/image/otg).


### HTM {#HTM}
```
public static final FileType HTM
```


Hypertext Markup Language File (.htm) को दर्शाता है, जो ब्राउज़र में प्रदर्शित होने वाले वेब पेजों के लिए उपयोग किया जाने वाला एक्सटेंशन है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/web/html).


### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language File (.html) को दर्शाता है, जो ब्राउज़र में प्रदर्शित होने वाले वेब पेजों के लिए उपयोग किया जाने वाला एक्सटेंशन है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/web/html).


### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht) को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/web/mht).


### NSF {#NSF}
```
public static final FileType NSF
```


Lotus Notes Database (.nsf) को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/nsf).


### MBOX {#MBOX}
```
public static final FileType MBOX
```


Email Mailbox File (.mbox) को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/mbox).


### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml) को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/web/mhtml).


### XML {#XML}
```
public static final FileType XML
```


XML File (.xml) को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/web/xml).


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote एप्लिकेशन द्वारा निर्मित OneNote दस्तावेज़ (.one) को दर्शाता है। OneNote आपको एप्लिकेशन का उपयोग करके जानकारी एकत्र करने देता है जैसे आप नोट लेने के लिए अपने ड्राफ्टपैड का उपयोग कर रहे हों।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/note-taking/one).


### PDF {#PDF}
```
public static final FileType PDF
```


Adobe द्वारा 1990 के दशक में निर्मित एक प्रकार का दस्तावेज़, Portable Document Format फ़ाइल (.pdf) को दर्शाता है। इस फ़ाइल फ़ॉर्मेट का उद्देश्य दस्तावेज़ों और अन्य संदर्भ सामग्री को एक ऐसे फ़ॉर्मेट में प्रस्तुत करने के लिए मानक पेश करना था जो एप्लिकेशन सॉफ़्टवेयर, हार्डवेयर और ऑपरेटिंग सिस्टम से स्वतंत्र हो।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/view/pdf).


### XPS {#XPS}
```
public static final FileType XPS
```


XML Paper Specification फ़ाइल (.xps) को दर्शाता है, जो Microsoft द्वारा निर्मित XML Paper Specification पर आधारित पृष्ठ लेआउट फ़ाइलें हैं। यह फ़ॉर्मेट Microsoft द्वारा EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और PDF फ़ाइल फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, रूप‑रंग और प्रिंटिंग जानकारी के लिए XML का उपयोग करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/page-description-language/xps).


### OXPS {#OXPS}
```
public static final FileType OXPS
```


OpenXPS File (.oxps) को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/page-description-language/oxps).


### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX स्रोत दस्तावेज़ (.tex) को दर्शाता है, जो एक भाषा है जिसमें प्रोग्रामिंग और मार्क‑अप सुविधाएँ शामिल हैं और जिसका उपयोग दस्तावेज़ टाइपसेट करने के लिए किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/page-description-language/tex).


### OFD {#OFD}
```
public static final FileType OFD
```


GB/T 33190-2016 द्वारा परिभाषित Open Fixed-layout Document (OFD) फ़ॉर्मेट का लक्ष्य चीनी सार्वजनिक संस्थानों में PDF को बदलना है।


### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint प्रस्तुति फ़ाइल (.ppt) को दर्शाता है, जो स्लाइडों के संग्रह से बनी फ़ाइल है जिसे स्लाइडशो के रूप में प्रदर्शित किया जाता है। यह Microsoft PowerPoint 97-2003 द्वारा उपयोग किए जाने वाले बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/presentation/ppt).


### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML प्रस्तुति फ़ाइल (.pptx) को दर्शाता है, जो लोकप्रिय Microsoft PowerPoint एप्लिकेशन द्वारा निर्मित प्रस्तुति फ़ाइलें हैं। पहले के PPT फ़ाइल फ़ॉर्मेट के विपरीत, जो बाइनरी था, PPTX फ़ॉर्मेट Microsoft PowerPoint Open XML प्रस्तुति फ़ाइल फ़ॉर्मेट पर आधारित है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/presentation/pptx).


### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint स्लाइड शो फ़ाइल (.pps) को दर्शाता है, जो स्लाइड शो उद्देश्यों के लिए Microsoft PowerPoint का उपयोग करके बनाई गई हैं। PPS फ़ाइल पढ़ना और बनाना Microsoft PowerPoint 97-2003 द्वारा समर्थित है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/presentation/pps).


### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML स्लाइड शो (.ppsx) फ़ाइलों को दर्शाता है, जो स्लाइड शो उद्देश्यों के लिए Microsoft PowerPoint 2007 और उसके बाद के संस्करणों से बनाई गई हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/presentation/ppsx).


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument प्रस्तुति (.odp) को दर्शाता है, जो OpenOffice.org द्वारा OASISOpen मानक में उपयोग किए जाने वाले प्रस्तुति फ़ाइल फ़ॉर्मेट को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/presentation/odp).


### FODP {#FODP}
```
public static final FileType FODP
```


OpenDocument प्रस्तुति (.fodp) को दर्शाता है, जो OpenDocument फ्लैट XML प्रस्तुति को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/fodp).


### POT {#POT}
```
public static final FileType POT
```


PowerPoint टेम्पलेट (.pot) को दर्शाता है, जो PowerPoint 97-2003 संस्करणों द्वारा बनाई गई Microsoft PowerPoint टेम्पलेट फ़ाइलें हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/presentation/pot).


### PPTM {#PPTM}
```
public static final FileType PPTM
```


PowerPoint Open XML मैक्रो‑सक्षम प्रस्तुति (.pptm) को दर्शाता है, जो Microsoft PowerPoint 2007 या उसके बाद के संस्करणों से बनाई गई मैक्रो‑सक्षम प्रस्तुति फ़ाइलें हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/presentation/pptm).


### POTX {#POTX}
```
public static final FileType POTX
```


PowerPoint Open XML प्रस्तुति टेम्पलेट (.potx) को दर्शाता है, जो Microsoft PowerPoint 2007 और उसके बाद के संस्करणों से बनाई गई Microsoft PowerPoint टेम्पलेट प्रस्तुतियों को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/presentation/potx).


### POTM {#POTM}
```
public static final FileType POTM
```


PowerPoint Open XML मैक्रो-सक्षम प्रेज़ेंटेशन टेम्प्लेट (.potm) को दर्शाता है, जो Microsoft PowerPoint टेम्प्लेट फ़ाइलें हैं जिनमें मैक्रो का समर्थन होता है। POTM फ़ाइलें PowerPoint 2007 या उससे ऊपर के संस्करण से बनाई जाती हैं और इनमें डिफ़ॉल्ट सेटिंग्स होती हैं जिन्हें आगे की प्रेज़ेंटेशन फ़ाइलें बनाने के लिए उपयोग किया जा सकता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/presentation/potm).


### PPSM {#PPSM}
```
public static final FileType PPSM
```


PowerPoint Open XML मैक्रो‑सक्षम स्लाइड (.ppsm) को दर्शाता है, जो Microsoft PowerPoint 2007 या उसके बाद के संस्करणों से बनाई गई मैक्रो‑सक्षम स्लाइड शो फ़ाइल फ़ॉर्मेट को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/presentation/ppsm).


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument प्रस्तुति टेम्पलेट (.otp) को दर्शाता है, जो OASIS OpenDocument मानक फ़ॉर्मेट में अनुप्रयोगों द्वारा बनाई गई प्रस्तुति टेम्पलेट फ़ाइलें हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/presentation/otp).


### XLS {#XLS}
```
public static final FileType XLS
```


Excel स्प्रेडशीट (.xls) को दर्शाता है, जो Excel बाइनरी फ़ाइल फ़ॉर्मेट का प्रतिनिधित्व करता है। ऐसी फ़ाइलें Microsoft Excel के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे OpenOffice Calc या Apple Numbers द्वारा भी बनाई जा सकती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xls).


### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Excel 2003 XML (SpreadsheetML) (.xml) को दर्शाता है, जो Excel बाइनरी फ़ाइल फ़ॉर्मेट का प्रतिनिधित्व करता है। ऐसी फ़ाइलें Microsoft Excel के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे OpenOffice Calc या Apple Numbers द्वारा भी बनाई जा सकती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xls).


### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Apple Numbers (.numbers) को दर्शाता है, जो Excel जैसी बाइनरी फ़ाइल फ़ॉर्मेट का प्रतिनिधित्व करता है। ऐसी फ़ाइलें Apple Numbers एप्लिकेशन द्वारा बनाई जा सकती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/numbers).


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML स्प्रेडशीट (.xlsx) को दर्शाता है, जो Microsoft Excel दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है जिसे Microsoft ने Microsoft Office 2007 के रिलीज़ के साथ पेश किया था।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xlsx).


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML मैक्रो‑सक्षम स्प्रेडशीट (.xlsm) को दर्शाता है, जो मैक्रो का समर्थन करने वाली स्प्रेडशीट फ़ाइल का प्रकार है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xlsm).


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel बाइनरी स्प्रेडशीट (.xlsb) को दर्शाता है, जो Excel बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है। यह रिकॉर्ड्स और संरचनाओं का संग्रह है जो Excel वर्कबुक सामग्री को निर्दिष्ट करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xlsb).


### CSV {#CSV}
```
public static final FileType CSV
```


कॉमा सेपरेटेड वैल्यूज़ फ़ाइल (.csv) को दर्शाता है, जो साधारण टेक्स्ट फ़ाइलें हैं जिनमें कॉमा‑सेपरेटेड डेटा रिकॉर्ड होते हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/csv).


### TSV {#TSV}
```
public static final FileType TSV
```


टैब सेपरेटेड वैल्यूज़ फ़ाइल (.tsv) को दर्शाता है, जो साधारण टेक्स्ट फ़ॉर्मेट में टैब द्वारा अलग किए गए डेटा को दर्शाती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/tsv).


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument स्प्रेडशीट (.ods) को दर्शाता है, जो OpenDocument स्प्रेडशीट दस्तावेज़ फ़ॉर्मेट का संक्षिप्त रूप है जिसे उपयोगकर्ता संपादित कर सकता है। डेटा ODF फ़ाइलों में पंक्तियों और स्तंभों में संग्रहीत रहता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/ods).


### FODS {#FODS}
```
public static final FileType FODS
```


OpenDocument फ्लैट XML स्प्रेडशीट (.fods) को दर्शाता है।
यह एक स्प्रेडशीट दस्तावेज़ फ़ॉर्मेट है जो XML पर आधारित है और OpenOffice तथा LibreOffice द्वारा उपयोग किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/fods).


### OTS {#OTS}
```
public static final FileType OTS
```


OpenDocument स्प्रेडशीट टेम्पलेट (.ots) को दर्शाता है।
यह एक टेम्प्लेट दस्तावेज़ फ़ॉर्मेट है जो OpenOffice और LibreOffice द्वारा स्प्रेडशीट्स के लिए उपयोग किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/ots).


### XLAM {#XLAM}
```
public static final FileType XLAM
```


Microsoft Excel ऐड-इन (.xlam) का प्रतिनिधित्व करता है।
यह एक फ़ाइल फ़ॉर्मेट है जो Microsoft Excel द्वारा कस्टम कार्यक्षमता वाले ऐड-इन्स बनाने के लिए उपयोग किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/xlam).


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel मैक्रो-सक्षम टेम्प्लेट (.xltm) को दर्शाता है, जो Microsoft Excel द्वारा मैक्रो-सक्षम टेम्प्लेट फ़ाइलों के रूप में उत्पन्न फ़ाइलों का प्रतिनिधित्व करता है। XLTM फ़ाइलें संरचना में XLTX के समान हैं, सिवाय इसके कि बाद वाली मैक्रो वाले टेम्प्लेट फ़ाइलों को बनाने का समर्थन नहीं करती।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xltm).


### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel टेम्पलेट (.xlt) का प्रतिनिधित्व करता है, जो Microsoft Excel के साथ बनाए गए टेम्पलेट फ़ाइलें हैं, एक स्प्रेडशीट एप्लिकेशन जो Microsoft Office सूट का हिस्सा है। Microsoft Office 97-2003 नई XLT फ़ाइलें बनाने और उन्हें खोलने का समर्थन करता था।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xlt).


### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML स्प्रेडशीट टेम्पलेट (.xltx) का प्रतिनिधित्व करता है, जो Office OpenXML फ़ाइल फ़ॉर्मेट विनिर्देशों पर आधारित Microsoft Excel टेम्पलेट्स को दर्शाता है। इसका उपयोग एक मानक टेम्पलेट फ़ाइल बनाने के लिए किया जाता है जिसे XLTX फ़ाइल में निर्दिष्ट समान सेटिंग्स के साथ XLSX फ़ाइलें उत्पन्न करने के लिए उपयोग किया जा सकता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xltx).


### SXC {#SXC}
```
public static final FileType SXC
```


StarOffice Calc स्प्रेडशीट (.sxc) का प्रतिनिधित्व करता है।
यह एक स्प्रेडशीट दस्तावेज़ है जो StarOffice Calc, एक स्प्रेडशीट प्रोग्राम के साथ बनाया गया है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/sxc).


### MPP {#MPP}
```
public static final FileType MPP
```


Microsoft Project फ़ाइल (.mpp) का प्रतिनिधित्व करता है, जो एक Microsoft Project डेटा फ़ाइल है जो परियोजना प्रबंधन से संबंधित जानकारी को एकीकृत रूप में संग्रहीत करती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/project-management/mpp).


### MPT {#MPT}
```
public static final FileType MPT
```


Microsoft Project टेम्पलेट (.mpt) का प्रतिनिधित्व करता है, जिसमें .MPP फ़ाइलें बनाने के लिए मूल जानकारी और संरचना के साथ दस्तावेज़ सेटिंग्स शामिल हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/project-management/mpt).


### MPX {#MPX}
```
public static final FileType MPX
```


Microsoft Project एक्सचेंज फ़ाइल (.mpx) का प्रतिनिधित्व करता है, जो ASCII फ़ाइल फ़ॉर्मेट है जो Microsoft Project (MSP) और अन्य अनुप्रयोगों के बीच परियोजना जानकारी स्थानांतरित करने के लिए उपयोग होता है जो MPX फ़ाइल फ़ॉर्मेट का समर्थन करते हैं, जैसे Primavera Project Planner, Sciforma, और Timerline Precision Estimating।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/project-management/mpx).


### AS {#AS}
```
public static final FileType AS
```


ActionScript फ़ाइल (.as) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/as).


### AS_3 {#AS-3}
```
public static final FileType AS_3
```


ActionScript फ़ाइल (.as3) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://datatypes.net/open-as3-files).


### ASM {#ASM}
```
public static final FileType ASM
```


Assembly Language स्रोत कोड फ़ाइल (.asm) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/cad/asm).


### BAT {#BAT}
```
public static final FileType BAT
```


DOS बैच फ़ाइल (.bat) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/executable/bat).


### C {#C}
```
public static final FileType C
```


C/C++ स्रोत कोड फ़ाइल (.c) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/programming/c).


### CC {#CC}
```
public static final FileType CC
```


C++ स्रोत कोड फ़ाइल (.cc) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/cc).


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


CMake फ़ाइल (.cmake) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/programming/cmake).


### CPP {#CPP}
```
public static final FileType CPP
```


C++ स्रोत कोड फ़ाइल (.cpp) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/programming/cpp).


### CS {#CS}
```
public static final FileType CS
```


C# स्रोत कोड फ़ाइल (.cs) का प्रतिनिधित्व करता है, जो C# प्रोग्रामिंग भाषा की स्रोत कोड फ़ाइल है। इसे Microsoft द्वारा .NET Framework के साथ उपयोग के लिए प्रस्तुत किया गया था।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/programming/cs).


### VB {#VB}
```
public static final FileType VB
```


Visual Basic प्रोजेक्ट आइटम फ़ाइल (.vb) का प्रतिनिधित्व करता है, जो Visual Basic भाषा में बनाई गई स्रोत कोड फ़ाइल है। इसे Microsoft द्वारा .NET अनुप्रयोगों के विकास के लिए बनाया गया था।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/programming/vb).


### CSS {#CSS}
```
public static final FileType CSS
```


Cascading Style Sheet (.css) फ़ाइल का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/web/css).


### CXX {#CXX}
```
public static final FileType CXX
```


C++ स्रोत कोड फ़ाइल (.cxx) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/cxx).


### DIFF {#DIFF}
```
public static final FileType DIFF
```


पैच फ़ाइल (.diff) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/diff).


### ERB {#ERB}
```
public static final FileType ERB
```


Ruby ERB स्क्रिप्ट (.erb) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/erb).


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Groovy स्रोत कोड फ़ाइल (.groovy) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/programming/groovy).


### H {#H}
```
public static final FileType H
```


C/C++/Objective-C हेडर फ़ाइल (.h) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/h).


### HAML {#HAML}
```
public static final FileType HAML
```


Haml स्रोत कोड फ़ाइल (.haml) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/programming/haml).


### HH {#HH}
```
public static final FileType HH
```


एक C++ हेडर फ़ाइल (.hh) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/hh).


### JAVA {#JAVA}
```
public static final FileType JAVA
```


एक जावा सोर्स कोड फ़ाइल (.java) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/programming/java).


### JS {#JS}
```
public static final FileType JS
```


एक जावास्क्रिप्ट फ़ाइल (.js) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/web/js).


### JSON {#JSON}
```
public static final FileType JSON
```


एक जावास्क्रिप्ट ऑब्जेक्ट नोटेशन फ़ाइल (.json) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/web/json).


### LESS {#LESS}
```
public static final FileType LESS
```


एक LESS स्टाइल शीट (.less) फ़ाइल का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/web/less).


### LOG {#LOG}
```
public static final FileType LOG
```


एक लॉग फ़ाइल (.log) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/database/log).


### M {#M}
```
public static final FileType M
```


एक ऑब्जेक्टिव‑C इम्प्लीमेंटेशन फ़ाइल (.m) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/m).


### MAKE {#MAKE}
```
public static final FileType MAKE
```


एक Xcode मेकफ़ाइल स्क्रिप्ट (.make) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/make).


### MD {#MD}
```
public static final FileType MD
```


एक मार्कडाउन डॉक्यूमेंटेशन फ़ाइल (.md) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/word-processing/md).


### ML {#ML}
```
public static final FileType ML
```


एक ML सोर्स कोड फ़ाइल (.ml) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/programming/ml).


### MM {#MM}
```
public static final FileType MM
```


एक ऑब्जेक्टिव‑C++ सोर्स फ़ाइल (.mm) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/mm).


### PHP {#PHP}
```
public static final FileType PHP
```


एक PHP सोर्स कोड फ़ाइल (.php) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/programming/php).


### PL {#PL}
```
public static final FileType PL
```


एक पर्ल स्क्रिप्ट (.pl) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/pl).


### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


एक जावा प्रॉपर्टीज़ फ़ाइल (.properties) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/properties).


### PY {#PY}
```
public static final FileType PY
```


एक पाइथन स्क्रिप्ट (.py) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/py).


### RB {#RB}
```
public static final FileType RB
```


एक रूबी सोर्स कोड (.rb) फ़ाइल का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/rb).


### RST {#RST}
```
public static final FileType RST
```


एक reStructuredText फ़ाइल (.rst) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/rst).


### SASS {#SASS}
```
public static final FileType SASS
```


एक सिंटैक्टिकली ऑसम स्टाइलशीट्स फ़ाइल (.sass) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/web/sass).


### SCALA {#SCALA}
```
public static final FileType SCALA
```


एक स्काला सोर्स कोड फ़ाइल (.scala) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/scala).


### SCM {#SCM}
```
public static final FileType SCM
```


एक स्कीम सोर्स कोड फ़ाइल (.scm) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/scm).


### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


एक जेनरिक स्क्रिप्ट फ़ाइल (.script) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/script).


### SH {#SH}
```
public static final FileType SH
```


एक बैश शेल स्क्रिप्ट (.sh) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/cs/programming/sh).


### SML {#SML}
```
public static final FileType SML
```


एक स्टैंडर्ड ML सोर्स कोड फ़ाइल (.sml) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/sml).


### SQL {#SQL}
```
public static final FileType SQL
```


एक स्ट्रक्चर्ड क्वेरी लैंग्वेज डेटा फ़ाइल (.sql) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/database/sql).


### VIM {#VIM}
```
public static final FileType VIM
```


एक Vim सेटिंग्स फ़ाइल (.vim) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/vim).


### YAML {#YAML}
```
public static final FileType YAML
```


YAML दस्तावेज़ (.yaml) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/programming/yaml).


### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word दस्तावेज़ (.doc) फ़ाइल का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/doc).


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML दस्तावेज़ (.docx) फ़ाइल का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/docx).


### CHM {#CHM}
```
public static final FileType CHM
```


Microsoft संकलित HTML हेल्प फ़ाइल (.chm) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/web/chm).


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML मैक्रो-सक्षम दस्तावेज़ (.docm) फ़ाइल का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/docm).


### DOT {#DOT}
```
public static final FileType DOT
```


Word दस्तावेज़ टेम्पलेट (.dot) फ़ाइल का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/dot).


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML दस्तावेज़ टेम्पलेट (.dotx) फ़ाइल का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/dotx).


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML मैक्रो-सक्षम दस्तावेज़ टेम्पलेट (.dotm) फ़ाइल का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/dotm).


### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Format फ़ाइल (.rtf) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/rtf).


### TXT {#TXT}
```
public static final FileType TXT
```


सादा टेक्स्ट फ़ाइल (.txt) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/txt).


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument टेक्स्ट दस्तावेज़ (.odt) का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/odt).


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument दस्तावेज़ टेम्पलेट (.ott) का प्रतिनिधित्व करता है।
यह OASIS के OpenDocument मानक फ़ॉर्मेट के अनुरूप उत्पन्न किया गया एक टेम्पलेट दस्तावेज़ है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/ott).


### VCF {#VCF}
```
public static final FileType VCF
```


vCard फ़ाइल (.vcf) का प्रतिनिधित्व करता है, जो संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल फ़ॉर्मेट है।
यह लोकप्रिय सूचना विनिमय अनुप्रयोगों के बीच डेटा विनिमय के लिए व्यापक रूप से उपयोग किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/vcf).


### AI {#AI}
```
public static final FileType AI
```


Adobe Illustrator फ़ाइल (.ai) का प्रतिनिधित्व करता है, जो Adobe Illustrator चित्रों के लिए एक फ़ाइल फ़ॉर्मेट है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/image/ai).


### PSM1 {#PSM1}
```
public static final FileType PSM1
```


PowerShell स्क्रिप्ट मॉड्यूल फ़ाइल (.psm1) का प्रतिनिधित्व करता है।
यह PowerShell मॉड्यूल स्क्रिप्ट्स के लिए एक फ़ाइल फ़ॉर्मेट है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/psm1).


### PS1 {#PS1}
```
public static final FileType PS1
```


PowerShell स्क्रिप्ट फ़ाइल (.ps1) का प्रतिनिधित्व करता है।
यह Windows PowerShell Cmdlet फ़ाइलों के लिए एक फ़ाइल फ़ॉर्मेट है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/ps1).


### PSD1 {#PSD1}
```
public static final FileType PSD1
```


PowerShell स्क्रिप्ट मॉड्यूल मैनिफेस्ट फ़ाइल (.psd1) का प्रतिनिधित्व करता है।
यह PowerShell मॉड्यूल मैनिफेस्ट स्क्रिप्ट्स के लिए एक फ़ाइल फ़ॉर्मेट है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://fileinfo.com/extension/psd1).


### values() {#values--}
```
public static FileType[] values()
```




**Returns:**
com.groupdocs.viewer.FileType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static FileType valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


फ़ाइल एक्सटेंशन को फ़ाइल प्रकार से मैप करता है।


यह मेथड फ़ाइल एक्सटेंशन लेता है, चाहे वह अवधि "." के साथ हो या बिना, और यदि समर्थित हो तो संबंधित फ़ाइल प्रकार लौटाता है।
यदि फ़ाइल प्रकार समर्थित नहीं है, तो यह डिफ़ॉल्ट [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) फ़ाइल प्रकार लौटाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | extension | java.lang.String | फ़ाइल एक्सटेंशन, अवधि "." के साथ या बिना। |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


फ़ाइल नाम या फ़ाइल पथ से फ़ाइल एक्सटेंशन निकालता है और उसे फ़ाइल प्रकार से मैप करता है।


यदि फ़ाइल प्रकार समर्थित है, तो मेथड संबंधित लौटाता है
FileType
,
अन्यथा यह डिफ़ॉल्ट [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) फ़ाइल प्रकार लौटाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | फ़ाइल नाम या फ़ाइल पथ। |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


फ़ाइल मीडिया प्रकार को फ़ाइल प्रकार में मैप करता है। उदाहरण के लिए, 'application/pdf' को [PDF](../../com.groupdocs.viewer/filetype#PDF) में मैप किया जाएगा।


यह मेथड फ़ाइल मीडिया प्रकार को इनपुट के रूप में लेता है और इसे संबंधित में मैप करता है
FileType
. यदि मीडिया प्रकार है
समर्थित, तो मेथड संबंधित फ़ाइल प्रकार लौटाता है। यदि मीडिया प्रकार समर्थित नहीं है, तो यह डिफ़ॉल्ट लौटाता है
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | mediaType | java.lang.String | फ़ाइल मीडिया प्रकार, उदाहरण के लिए, 'application/pdf'। |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।


यह मेथड फ़ाइल का प्रतिनिधित्व करने वाले इनपुट स्ट्रीम को लेता है और फ़ाइल सिग्नेचर का विश्लेषण करके उसके फ़ाइल प्रकार का पता लगाने की कोशिश करता है। यह
फ़ाइल सिग्नेचर फ़ाइल की शुरुआत में बाइट्स की एक अनूठी क्रम है जो उसके फ़ाइल प्रकार को दर्शाती है। मेथड
इनपुट स्ट्रीम से फ़ाइल सिग्नेचर को पढ़ता है और इसे समर्थित फ़ाइल प्रकारों के ज्ञात फ़ाइल सिग्नेचर के विरुद्ध मिलाता है।
यदि मिलान मिलता है, तो मेथड संबंधित फ़ाइल प्रकार लौटाता है। यदि कोई मिलान नहीं मिलता, तो यह डिफ़ॉल्ट लौटाता है
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | stream | java.io.InputStream | फ़ाइल का प्रतिनिधित्व करने वाला इनपुट स्ट्रीम। |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।


यह मेथड फ़ाइल सिग्नेचर का विश्लेषण करता है, जो फ़ाइल की शुरुआत में बाइट्स की एक अनूठी क्रम है, निर्धारित करने के लिए
फ़ाइल प्रकार। यह प्रदान किए गए इनपुट स्ट्रीम से फ़ाइल सिग्नेचर को पढ़ता है और इसे ज्ञात फ़ाइल सिग्नेचर के विरुद्ध मिलाता है
समर्थित फ़ाइल प्रकारों का। यदि मिलान मिलता है, तो मेथड संबंधित फ़ाइल प्रकार लौटाता है। यदि कोई मिलान नहीं मिलता, तो यह
डिफ़ॉल्ट [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) फ़ाइल प्रकार लौटाता है।


यदि फ़ाइल एन्क्रिप्टेड है और खोलने के लिए पासवर्ड की आवश्यकता है, तो पासवर्ड को इस पैरामीटर के रूप में प्रदान किया जाना चाहिए।
विधि। पासवर्ड का उपयोग फ़ाइल को डिक्रिप्ट करने और फ़ाइल प्रकार निर्धारित करने के लिए उसकी सिग्नेचर का विश्लेषण करने में किया जाएगा।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | stream | java.io.InputStream | फ़ाइल का प्रतिनिधित्व करने वाला इनपुट स्ट्रीम। |
|
|  | पासवर्ड | java.lang.String | फ़ाइल खोलने के लिए पासवर्ड। |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।


यह मेथड फ़ाइल सिग्नेचर का विश्लेषण करता है, जो फ़ाइल की शुरुआत में बाइट्स की एक अनूठी क्रम है, निर्धारित करने के लिए
फ़ाइल प्रकार। यह प्रदान किए गए इनपुट स्ट्रीम से फ़ाइल सिग्नेचर को पढ़ता है और इसे ज्ञात फ़ाइल सिग्नेचर के विरुद्ध मिलाता है
समर्थित फ़ाइल प्रकारों का। यदि मिलान मिलता है, तो मेथड संबंधित फ़ाइल प्रकार लौटाता है। यदि कोई मिलान नहीं मिलता, तो यह
डिफ़ॉल्ट [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) फ़ाइल प्रकार लौटाता है।


फ़ाइल प्रकार पहचान प्रक्रिया के दौरान किसी भी संबंधित जानकारी या त्रुटियों को लॉग करने के लिए एक लॉगर प्रदान किया जा सकता है। लॉगर
ILogger इंटरफ़ेस को लागू करना चाहिए। यदि कोई लॉगर प्रदान नहीं किया जाता है, तो पहचान प्रक्रिया कोई भी
लॉग आउटपुट।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | stream | java.io.InputStream | फ़ाइल का प्रतिनिधित्व करने वाला इनपुट स्ट्रीम। |
|
|  | लॉगर | com.groupdocs.foundation.logging.ILogger | सूचना या त्रुटियों को लॉग करने के लिए लॉगर। |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।


यह मेथड फ़ाइल सिग्नेचर का विश्लेषण करता है, जो फ़ाइल की शुरुआत में बाइट्स की एक अनूठी क्रम है, निर्धारित करने के लिए
फ़ाइल प्रकार। यह प्रदान किए गए इनपुट स्ट्रीम से फ़ाइल सिग्नेचर को पढ़ता है और इसे ज्ञात फ़ाइल सिग्नेचर के विरुद्ध मिलाता है
समर्थित फ़ाइल प्रकारों का। यदि मिलान मिलता है, तो मेथड संबंधित फ़ाइल प्रकार लौटाता है। यदि कोई मिलान नहीं मिलता, तो यह
डिफ़ॉल्ट [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) फ़ाइल प्रकार लौटाता है।


यदि फ़ाइल एन्क्रिप्टेड या संरक्षित है तो पासवर्ड प्रदान किया जा सकता है। पासवर्ड का उपयोग फ़ाइल को खोलने से पहले किया जाएगा
फ़ाइल की सिग्नेचर का विश्लेषण करने के लिए। यदि फ़ाइल को पासवर्ड की आवश्यकता नहीं है, तो इस पैरामीटर को null सेट किया जा सकता है।


फ़ाइल प्रकार पहचान प्रक्रिया के दौरान किसी भी संबंधित जानकारी या त्रुटियों को लॉग करने के लिए एक लॉगर प्रदान किया जा सकता है। लॉगर
ILogger इंटरफ़ेस को लागू करना चाहिए। यदि कोई लॉगर प्रदान नहीं किया जाता है, तो पहचान प्रक्रिया कोई भी
लॉग आउटपुट।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | stream | java.io.InputStream | फ़ाइल का प्रतिनिधित्व करने वाला इनपुट स्ट्रीम। |
|
|  | पासवर्ड | java.lang.String | फ़ाइल खोलने के लिए पासवर्ड। |
|
|  | लॉगर | com.groupdocs.foundation.logging.ILogger | सूचना या त्रुटियों को लॉग करने के लिए लॉगर। |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


समर्थित फ़ाइल प्रकारों को पुनः प्राप्त करता है।


यह विधि सिस्टम द्वारा समर्थित सभी फ़ाइल प्रकारों का क्रम लौटाती है। फ़ाइल प्रकार विभिन्न
दस्तावेज़ फ़ॉर्मेट जो सिस्टम द्वारा प्रोसेस या पहचाने जा सकते हैं।
***Learn more**
* Learn more about the supported document formats: [Full list of supported file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/)*


**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - समर्थित फ़ाइल प्रकारों का क्रम।

### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


पथ द्वारा टेक्स्ट [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), और [CSV](../../com.groupdocs.viewer/filetype#CSV) फ़ाइलों का कैरेक्टर सेट पता लगाने का प्रयास करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | फ़ाइल नाम या फ़ाइल पथ। |
|

**Returns:**
java.nio.charset.Charset - फ़ाइल कैरेक्टरसेट का पता न चलने पर Charset या null।

**Example:**


Charset charset = FileType.detectCharset("message.txt");
     

### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


स्ट्रीम द्वारा टेक्स्ट [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), और [CSV](../../com.groupdocs.viewer/filetype#CSV) फ़ाइल का कैरेक्टर सेट पता लगाने का प्रयास करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | stream | java.io.InputStream | फ़ाइल स्ट्रीम। |
|

**Returns:**
java.nio.charset.Charset - फ़ाइल कैरेक्टरसेट का पता न चलने पर Charset या null।

**Example:**


InputStream stream = new FileInputStream("message.txt");
Charset charset = FileType.detectCharset(stream);
     

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


फ़ाइल फ़ॉर्मेट का नाम प्राप्त करता है, उदाहरण के लिए, "Microsoft Word Document"।


**Returns:**
java.lang.String - फ़ाइल फ़ॉर्मेट का नाम।

### getExtension() {#getExtension--}
```
public final String getExtension()
```


फ़ाइल एक्सटेंशन उपसर्ग प्राप्त करता है (जिसमें अवधि "." शामिल है), उदाहरण के लिए, ".doc"।


**Returns:**
java.lang.String - फ़ाइल एक्सटेंशन उपसर्ग।

### toString() {#toString--}
```
public String toString()
```


वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व लौटाता है।


**Returns:**
java.lang.String - वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व।

