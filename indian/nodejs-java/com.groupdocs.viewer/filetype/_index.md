---
title: "FileType"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "फ़ाइल प्रकार को दर्शाता है।"
type: docs
weight: 14
url: /hi/nodejs-java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

फ़ाइल प्रकार का प्रतिनिधित्व करता है। GroupDocs.Viewer घटक द्वारा समर्थित सभी फ़ाइल प्रकारों की सूची प्राप्त करने के लिए मेथड प्रदान करता है।

FileType enum विभिन्न फ़ाइल प्रकारों के स्थिरांक प्रदान करता है जो GroupDocs.Viewer घटक द्वारा समर्थित हैं। आप इस enum के मेथड का उपयोग करके सभी समर्थित फ़ाइल प्रकारों की सूची प्राप्त कर सकते हैं या यह जांच सकते हैं कि कोई विशिष्ट फ़ाइल प्रकार समर्थित है या नहीं।

उदाहरण उपयोग:

```

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
 
```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | अज्ञात फ़ाइल प्रकार का प्रतिनिधित्व करता है। |
| [ZIP](#ZIP) | एक ज़िप्ड फ़ाइल (.zip) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों या डायरेक्टरीज़ को रख सकती है। |
| [TAR](#TAR) | एक एकत्रित Unix फ़ाइल आर्काइव (.tar) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों को संग्रहित करने के लिए बनाया गया है। |
| [XZ](#XZ) | एक XZ फ़ाइल (.xz) का प्रतिनिधित्व करता है जो LZMA एल्गोरिदम पर आधारित उच्च अनुपात संपीड़न एल्गोरिदम का उपयोग करके संकुचित की गई है। |
| [TXZ](#TXZ) | एक एकत्रित Unix फ़ाइल आर्काइव (.txz, .tar.xz) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों को संग्रहित करने के लिए बनाया गया है। |
| [TARXZ](#TARXZ) | एक एकत्रित Unix फ़ाइल आर्काइव (.txz, .tar.xz) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों को संग्रहित करने के लिए बनाया गया है। |
| [TGZ](#TGZ) | एक एकत्रित Unix फ़ाइल आर्काइव (.tgz, .tar.gz) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों को संग्रहित करने के लिए बनाया गया है। |
| [TARGZ](#TARGZ) | एक एकत्रित Unix फ़ाइल आर्काइव (.tgz, .tar.gz) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों को संग्रहित करने के लिए बनाया गया है। |
| [BZ_2](#BZ-2) | एक Bzip2 संकुचित फ़ाइल (.bz2) का प्रतिनिधित्व करता है जो BZIP2 ओपन-सोर्स संपीड़न विधि का उपयोग करके उत्पन्न की गई है। |
| [RAR](#RAR) | एक Roshal आर्काइव (.rar) संकुचित फ़ाइल का प्रतिनिधित्व करता है जो RAR (WINRAR संस्करण 4) संपीड़न विधि का उपयोग करके उत्पन्न की गई है। |
| [GZ](#GZ) | एक Gnu ज़िप्ड फ़ाइल (.gz) का प्रतिनिधित्व करता है जो gzip संपीड़न एप्लिकेशन से बनाई गई है। |
| [GZIP](#GZIP) | एक Gnu Zipped फ़ाइल (.gzip) को दर्शाता है, जो Unix सिस्टम में उपयोग किए जाने वाले Compress प्रोग्राम को बदलने के लिए एक मुफ्त उपयोगिता के रूप में पेश की गई संपीड़ित फ़ाइल है। |
| [SEVEN_ZIP](#SEVEN-ZIP) | एक 7Zip (.7z, .7zip) फ़ाइल को दर्शाता है, जो LZMA और LZMA2 संपीड़न के साथ एक मुफ्त ओपन-सोर्स आर्काइवर है। |
| [CPIO](#CPIO) | Cpio एक सामान्य फ़ाइल आर्काइवर उपयोगिता और इसका संबंधित फ़ाइल स्वरूप है। |
| [ZSTANDARD](#ZSTANDARD) | ZST फ़ाइल एक संपीड़ित फ़ाइल है जो Zstandard (zstd) संपीड़न एल्गोरिद्म द्वारा उत्पन्न होती है। |
| [TZST](#TZST) | TZST फ़ाइलें (.tar.zst, .tzst) Zstandard अभिलेख (ZST) हैं, जो आंतरिक रूप से एक एकीकृत Unix फ़ाइल अभिलेख (Tar) को समाहित करती हैं, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए Unix-आधारित उपयोगिता द्वारा बनाई गई है। |
| [TAR_ZST](#TAR-ZST) | TZST फ़ाइलें (.tar.zst, .tzst) Zstandard अभिलेख (ZST) हैं, जो आंतरिक रूप से एक एकीकृत Unix फ़ाइल अभिलेख (Tar) को समाहित करती हैं, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए Unix-आधारित उपयोगिता द्वारा बनाई गई है। |
| [ISO](#ISO) | ISO ऑप्टिकल डिस्क इमेज एक अनसंपीड़ित अभिलेख डिस्क इमेज फ़ाइल है जो CD या DVD जैसे ऑप्टिकल डिस्क पर संपूर्ण डेटा की सामग्री को दर्शाती है, ISO-9660 मानक पर आधारित। |
| [LHA](#LHA) | LHA या LZH एक फ्रीवेयर संपीड़न उपयोगिता और संबंधित फ़ाइल स्वरूप है। |
| [CAB](#CAB) | Cabinet (या CAB) Microsoft Windows के लिए एक अभिलेख-फ़ाइल स्वरूप है। |
| [DXF](#DXF) | एक Drawing Exchange Format फ़ाइल (.dxf) को दर्शाता है, जो AutoCAD ड्रॉइंग फ़ाइल का टैग्ड डेटा प्रतिनिधित्व है। |
| [DWG](#DWG) | एक AutoCAD Drawing Database फ़ाइल (.dwg) को दर्शाता है, जो 2D और 3D डिज़ाइन डेटा को रखने के लिए उपयोग की जाने वाली स्वामित्व वाली बाइनरी फ़ाइलों को दर्शाती है। |
| [DWT](#DWT) | एक AutoCAD Drawing Template (.dwt) को दर्शाता है, जो ड्रॉइंग बनाने के लिए शुरुआती रूप में उपयोग की जाने वाली AutoCAD ड्रॉइंग टेम्पलेट फ़ाइल है, जिसे DWG फ़ाइलों के रूप में सहेजा जा सकता है। |
| [STL](#STL) | एक Stereolithography फ़ाइल (.stl) को दर्शाता है, जो 3-आयामी सतह ज्यामिति को दर्शाने वाला एक अदलाबदल योग्य फ़ाइल स्वरूप है। |
| [IFC](#IFC) | एक Industry Foundation Classes फ़ाइल (.ifc) को दर्शाता है, जो भवन वस्तुओं और उनकी विशेषताओं के आयात और निर्यात के लिए अंतर्राष्ट्रीय मानक स्थापित करने वाला फ़ाइल स्वरूप है। |
| [DWF](#DWF) | एक Design Web Format फ़ाइल (.dwf) को दर्शाता है, जो 2D/3D ड्रॉइंग को देखने, समीक्षा करने या प्रिंट करने के लिए एक संपीड़ित फ़ाइल स्वरूप है। |
| [FBX](#FBX) | एक Autodesk FBX Interchange फ़ाइल (FilmBoX) (.fbx) को दर्शाता है, जो एक 3D मॉडल स्वरूप है। |
| [DWFX](#DWFX) | एक Design Web Format फ़ाइल XPS (.dwfx) को दर्शाता है, जो 2D/3D ड्रॉइंग को XPS दस्तावेज़ के रूप में देखने, समीक्षा करने या प्रिंट करने के लिए एक संपीड़ित स्वरूप है। |
| [DGN](#DGN) | एक MicroStation Design फ़ाइल (.dgn) को दर्शाता है, जो MicroStation और Intergraph Interactive Graphics Design System जैसे CAD अनुप्रयोगों द्वारा निर्मित और समर्थित ड्रॉइंग हैं। |
| [PLT](#PLT) | एक PLT (HPGL) फ़ाइल (.plt) को दर्शाता है, जो Autodesk, Inc. द्वारा प्रस्तुत एक वेक्टर-आधारित प्लॉटर फ़ाइल है। |
| [CF2](#CF2) | एक Common File Format फ़ाइल (.cf2) को दर्शाता है। |
| [OBJ](#OBJ) | एक Wavefront 3D Object फ़ाइल (.obj) को दर्शाता है, जो Wavefront Technologies द्वारा प्रस्तुत 3D इमेज फ़ाइल है। |
| [HPG](#HPG) | एक PLT (HPGL) फ़ाइल (.hpg) को दर्शाता है। |
| [IGS](#IGS) | एक Initial Graphics Exchange Specification (IGES) फ़ाइल (.igs) को दर्शाता है। |
| [VSD](#VSD) | एक Visio Drawing फ़ाइल (.vsd) को दर्शाता है, जो Microsoft Visio अनुप्रयोग से बनाई गई ड्रॉइंग हैं, जो विभिन्न ग्राफिकल वस्तुओं और उनके अंतर्संबंधों को दर्शाती हैं। |
| [VSDX](#VSDX) | एक Visio Drawing फ़ाइल (.vsdx) को दर्शाता है, जो Microsoft Office 2013 से आगे के संस्करणों में प्रस्तुत Microsoft Visio फ़ाइल स्वरूप को दर्शाती है। |
| [VSS](#VSS) | एक Visio Stencil फ़ाइल (.vss) को दर्शाता है, जो Microsoft Visio 2007 और उससे पहले के संस्करणों से बनाई गई स्टेंसिल फ़ाइलें हैं। |
| [VSSX](#VSSX) | Visio Stencil File (.vssx) का प्रतिनिधित्व करता है, जो Microsoft Visio 2013 और उसके बाद के संस्करणों के साथ बनाई गई ड्रॉइंग स्टेंसिल हैं। |
| [VSDM](#VSDM) | Visio Macro-Enabled Drawing (.vsdm) का प्रतिनिधित्व करता है, जो Microsoft Visio एप्लिकेशन के साथ बनाई गई ड्रॉइंग फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। |
| [VST](#VST) | Visio Drawing Template (.vst) का प्रतिनिधित्व करता है, जो Microsoft Visio के साथ बनाई गई वेक्टर इमेज फ़ाइलें हैं। |
| [VSTX](#VSTX) | Visio Drawing Template (.vstx) का प्रतिनिधित्व करता है, जो Microsoft Visio 2013 और उसके बाद के संस्करणों के साथ बनाई गई ड्रॉइंग टेम्प्लेट फ़ाइलें हैं। |
| [VSTM](#VSTM) | Visio Macro-Enabled Drawing Template (.vstm) का प्रतिनिधित्व करता है, जो Microsoft Visio के साथ बनाई गई टेम्प्लेट फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। |
| [VSSM](#VSSM) | Visio Macro-Enabled Stencil File (.vssm) का प्रतिनिधित्व करता है, जो Microsoft Visio Stencil फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। |
| [VSX](#VSX) | Visio Stencil XML File (.vsx) का प्रतिनिधित्व करता है, जो ड्रॉइंग और आकारों से बनी स्टेंसिल को दर्शाता है, जिन्हें Microsoft Visio में डायग्राम बनाने के लिए उपयोग किया जाता है। |
| [VTX](#VTX) | Visio Template XML File (.vtx) का प्रतिनिधित्व करता है, जो Microsoft Visio ड्रॉइंग टेम्प्लेट है जिसे XML फ़ाइल फ़ॉर्मेट में डिस्क पर सहेजा गया है। |
| [VDW](#VDW) | Visio Web Drawing (.vdw) का प्रतिनिधित्व करता है, जो वेब ड्रॉइंग को रेंडर करने के लिए आवश्यक स्ट्रीम और स्टोरेज को निर्दिष्ट करता है। |
| [VDX](#VDX) | Visio Drawing XML File (.vdx) का प्रतिनिधित्व करता है, जो Microsoft Visio में बनाई गई किसी भी ड्रॉइंग या चार्ट को दर्शाता है, लेकिन .VDX एक्सटेंशन के साथ XML फ़ॉर्मेट में सहेजा गया है। |
| [EPUB](#EPUB) | Open eBook File (.epub) का प्रतिनिधित्व करता है, जो एक ई-बुक फ़ाइल फ़ॉर्मेट है जो प्रकाशकों और उपभोक्ताओं के लिए मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। |
| [MOBI](#MOBI) | Mobipocket eBook (.mobi) का प्रतिनिधित्व करता है, जो सबसे अधिक उपयोग किए जाने वाले ईबुक फ़ाइल फ़ॉर्मेट में से एक है। |
| [AZW_3](#AZW-3) | Amazon Kindle Format 8 (KF8) ईबुक, Amazon Kindle डिवाइसों के लिए विकसित किया गया डिजिटल फ़ाइल फ़ॉर्मेट है। |
| [MSG](#MSG) | Outlook Mail Message (.msg) का प्रतिनिधित्व करता है, जो Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, नियुक्तियों या अन्य कार्यों को संग्रहीत करने के लिए उपयोग किया जाने वाला फ़ाइल फ़ॉर्मेट है। |
| [EML](#EML) | E-Mail Message (.eml) का प्रतिनिधित्व करता है, जो Outlook और अन्य संबंधित अनुप्रयोगों द्वारा सहेजे गए ईमेल संदेशों को दर्शाता है। |
| [EMLX](#EMLX) | Apple Mail Message (.emlx) का प्रतिनिधित्व करता है, जिसे Apple ने लागू और विकसित किया है। |
| [PST](#PST) | Outlook Personal Information Store File (.pst) का प्रतिनिधित्व करता है, जो Outlook Personal Storage Files (जिसे Personal Storage Table भी कहा जाता है) को दर्शाता है, जो विभिन्न उपयोगकर्ता जानकारी संग्रहीत करती हैं। |
| [OST](#OST) | Outlook Offline Data File (.ost) का प्रतिनिधित्व करता है, जो Exchange Server के साथ Microsoft Outlook का उपयोग करके पंजीकरण के बाद स्थानीय मशीन पर ऑफ़लाइन मोड में उपयोगकर्ता के मेलबॉक्स डेटा को दर्शाता है। |
| [TIF](#TIF) | Tagged Image File (.tif) का प्रतिनिधित्व करता है, जो रास्टर इमेजेज़ को दर्शाता है जो इस फ़ाइल फ़ॉर्मेट मानक का पालन करने वाले विभिन्न उपकरणों पर उपयोग के लिए बनाए गए हैं। |
| [TIFF](#TIFF) | Tagged Image File Format (.tiff) का प्रतिनिधित्व करता है, जो रास्टर इमेजेज़ को दर्शाता है जो इस फ़ाइल फ़ॉर्मेट मानक का पालन करने वाले विभिन्न उपकरणों पर उपयोग के लिए बनाए गए हैं। |
| [JPG](#JPG) | JPEG Image (.jpg) का प्रतिनिधित्व करता है, जो एक प्रकार का इमेज फ़ॉर्मेट है जिसे लॉसी कम्प्रेशन विधि से सहेजा जाता है। |
| [JPEG](#JPEG) | JPEG Image (.jpeg) का प्रतिनिधित्व करता है, जो एक प्रकार का इमेज फ़ॉर्मेट है जिसे लॉसी कम्प्रेशन विधि से सहेजा जाता है। |
| [JFIF](#JFIF) | JPEG File Interchange Format (.jfif) एक इमेज है जिसे प्लेटफ़ॉर्मों के बीच तेज़ आदान-प्रदान के लिए विकसित किया गया था। |
| [PNG](#PNG) | Portable Network Graphic (.png) का प्रतिनिधित्व करता है, जो एक प्रकार का रास्टर इमेज फ़ाइल फ़ॉर्मेट है जो लॉसलेस कम्प्रेशन का उपयोग करता है। |
| [GIF](#GIF) | Graphical Interchange Format File (.gif) का प्रतिनिधित्व करता है, जो एक प्रकार की अत्यधिक संकुचित इमेज है। |
| [APNG](#APNG) | Animated Portable Network Graphic (.apng) को दर्शाता है, जो PNG फ़ॉर्मेट का एक विस्तार है जो एनीमेशन का समर्थन करता है। |
| [BMP](#BMP) | Bitmap Image File (.bmp) को दर्शाता है, जो बिटमैप डिजिटल छवियों को संग्रहीत करने के लिए उपयोग किया जाता है। |
| [ICO](#ICO) | Icon File (.ico) को दर्शाता है, जो माइक्रोसॉफ्ट विंडोज पर एप्लिकेशन के प्रतिनिधित्व के लिए आइकन के रूप में उपयोग की जाने वाली इमेज फ़ाइल प्रकार है। |
| [TGA](#TGA) | Truevision TGA (TARGA) फ़ाइल को दर्शाता है, जो TRUEVISION द्वारा विकसित बिटमैप डिजिटल छवियों को संग्रहीत करने के लिए उपयोग की जाती है। |
| [JP_2](#JP-2) | JPEG 2000 Core Image File (.jp2) को दर्शाता है, जो एक इमेज कोडिंग सिस्टम और अत्याधुनिक इमेज संपीड़न मानक है। |
| [JPF](#JPF) | JPEG 2000 Image File (.jpf) को दर्शाता है। |
| [JPX](#JPX) | JPEG 2000 Image File (.jpx) को दर्शाता है। |
| [JPM](#JPM) | JPEG 2000 Image File (.jpm) को दर्शाता है। |
| [J2C](#J2C) | JPEG 2000 Code InputStream (.j2c) को दर्शाता है। |
| [J2K](#J2K) | JPEG 2000 Code Stream (.j2k) को दर्शाता है, जो DCT संपीड़न के बजाय वेवलेट संपीड़न का उपयोग करके संकुचित इमेज है। |
| [JPC](#JPC) | JPEG 2000 Code Stream (.jpc) को दर्शाता है। |
| [JLS](#JLS) | JPEG-LS (JLS) फ़ाइल (.jls) को दर्शाता है। |
| [DIB](#DIB) | Device Independent Bitmap File (.dib) को दर्शाता है। |
| [WMF](#WMF) | Windows Metafile (.wmf) को दर्शाता है, जो वेक्टर और बिटमैप-फ़ॉर्मेट इमेज डेटा को संग्रहीत करने के लिए माइक्रोसॉफ्ट विंडोज़ मेेटाफाइल (WMF) का प्रतिनिधित्व करता है। |
| [WMZ](#WMZ) | Compressed Windows Metafile (.wmz) को दर्शाता है, जो वेक्टर और बिटमैप-फ़ॉर्मेट इमेज डेटा को संग्रहीत करने के लिए GZIP आर्काइव में संकुचित माइक्रोसॉफ्ट विंडोज़ मेेटाफाइल (WMF) का प्रतिनिधित्व करता है। |
| [EMF](#EMF) | Enhanced Windows Metafile (.emf) को दर्शाता है, जो डिवाइस-स्वतंत्र रूप से ग्राफिकल इमेज को प्रस्तुत करता है। |
| [EMZ](#EMZ) | Windows Compressed Enhanced Metafile (.emz) को दर्शाता है, जो GZIP द्वारा डिवाइस-स्वतंत्र रूप से संकुचित ग्राफिकल इमेज को प्रस्तुत करता है। |
| [WEBP](#WEBP) | WebP Image (.webp) को दर्शाता है, जो लॉसलेस और लॉसी संपीड़न पर आधारित एक आधुनिक रास्टर वेब इमेज फ़ाइल फ़ॉर्मेट है। |
| [DNG](#DNG) | Digital Negative Specification (.dng) को दर्शाता है, जो कच्ची फ़ाइलों के संग्रह के लिए उपयोग किया जाने वाला डिजिटल कैमरा इमेज फ़ॉर्मेट है। |
| [CDR](#CDR) | CorelDraw Vector Graphic Drawing (.cdr) को दर्शाता है, जो कोरलड्रॉ द्वारा मूल रूप से निर्मित एक वेक्टर ड्रॉइंग इमेज फ़ाइल है, जो डिजिटल रूप से एन्कोडेड और संकुचित छवियों को संग्रहीत करने के लिए उपयोग होती है। |
| [CMX](#CMX) | Corel Exchange (.cmx) को दर्शाता है, जो एक ड्रॉइंग इमेज फ़ाइल है जिसमें वेक्टर ग्राफिक्स और बिटमैप ग्राफिक्स दोनों हो सकते हैं। |
| [DJVU](#DJVU) | DjVu Image (.djvu) को दर्शाता है, जो स्कैन किए गए दस्तावेज़ों और पुस्तकों के लिए अभिप्रेत ग्राफिक्स फ़ाइल फ़ॉर्मेट है, विशेष रूप से उन फ़ाइलों के लिए जिनमें पाठ, ड्रॉइंग, इमेज और फ़ोटोग्राफ़ का मिश्रण होता है। |
| [CGM](#CGM) | Computer Graphics Metafile (.cgm) को दर्शाता है, जो वेक्टर ग्राफिक्स (2D), रास्टर ग्राफिक्स और टेक्स्ट को संग्रहीत और विनिमय करने के लिए एक मुक्त, प्लेटफ़ॉर्म-स्वतंत्र, अंतर्राष्ट्रीय मानक मेेटाफाइल फ़ॉर्मेट है। |
| [PCL](#PCL) | Printer Command Language Document (.pcl) को दर्शाता है। |
| [PSD](#PSD) | Adobe Photoshop Document (.psd) को दर्शाता है, जो ग्राफिक्स डिज़ाइनिंग और विकास के लिए उपयोग किया जाने वाला Adobe Photoshop का मूल फ़ाइल फ़ॉर्मेट है। |
| [PSB](#PSB) | Adobe Photoshop में ग्राफ़िक्स डिज़ाइनिंग और विकास के लिए उपयोग किया जाने वाला Photoshop Large Document Format (.psb) दर्शाता है। |
| [DCM](#DCM) | DICOM Image (.dcm) को दर्शाता है, जो एक डिजिटल छवि है जो रोगियों की मेडिकल जानकारी जैसे MRI, CT स्कैन और अल्ट्रासाउंड इमेजेज़ को संग्रहीत करती है। |
| [PS](#PS) | PostScript फ़ाइल (.ps) को दर्शाता है। |
| [EPS](#EPS) | Encapsulated PostScript फ़ाइल (.eps) को दर्शाता है, जो एक Encapsulated PostScript भाषा प्रोग्राम का वर्णन करता है जो एक पृष्ठ की उपस्थिति को परिभाषित करता है। |
| [ODG](#ODG) | OpenDocument Graphic फ़ाइल (.odg) को दर्शाता है, जो Apache OpenOffice के Draw एप्लिकेशन द्वारा ड्रॉइंग तत्वों को वेक्टर इमेज के रूप में संग्रहीत करने के लिए उपयोग की जाती है। |
| [FODG](#FODG) | Flat XML ODF टेम्पलेट (.fodg) को दर्शाता है, जो Apache OpenOffice के Draw एप्लिकेशन द्वारा ड्रॉइंग तत्वों को वेक्टर इमेज के रूप में संग्रहीत करने के लिए उपयोग किया जाता है। |
| [SVG](#SVG) | Scalable Vector Graphics फ़ाइल (.svg) को दर्शाता है, जो एक Scalable Vector Graphics फ़ाइल है जो इमेज की उपस्थिति का वर्णन करने के लिए XML-आधारित टेक्स्ट फ़ॉर्मेट का उपयोग करती है। |
| [SVGZ](#SVGZ) | Compressed Scalable Vector Graphics फ़ाइल (.svgz) को दर्शाता है, जो एक Scalable Vector Graphics फ़ाइल है जो XML-आधारित टेक्स्ट फ़ॉर्मेट, GZIP द्वारा संकुचित, का उपयोग करके इमेज की उपस्थिति का वर्णन करती है। |
| [OTG](#OTG) | OpenDocument Graphic टेम्पलेट (.otg) को दर्शाता है। |
| [HTM](#HTM) | Hypertext Markup Language फ़ाइल (.htm) को दर्शाता है, जो ब्राउज़र में प्रदर्शित होने वाले वेब पेजों के लिए एक्सटेंशन है। |
| [HTML](#HTML) | Hypertext Markup Language फ़ाइल (.html) को दर्शाता है, जो ब्राउज़र में प्रदर्शित होने वाले वेब पेजों के लिए एक्सटेंशन है। |
| [MHT](#MHT) | MHTML वेब आर्काइव (.mht) को दर्शाता है। |
| [NSF](#NSF) | Lotus Notes डेटाबेस (.nsf) को दर्शाता है। |
| [MBOX](#MBOX) | ईमेल मेलबॉक्स फ़ाइल (.mbox) को दर्शाता है। |
| [MHTML](#MHTML) | MIME HTML फ़ाइल (.mhtml) को दर्शाता है। |
| [XML](#XML) | XML फ़ाइल (.xml) को दर्शाता है। |
| [ONE](#ONE) | Microsoft OneNote एप्लिकेशन द्वारा निर्मित OneNote दस्तावेज़ (.one) को दर्शाता है। |
| [PDF](#PDF) | Portable Document Format फ़ाइल (.pdf) को दर्शाता है, जो 1990 के दशक में Adobe द्वारा बनाई गई दस्तावेज़ प्रकार है। |
| [XPS](#XPS) | XML Paper Specification फ़ाइल (.xps) को दर्शाता है, जो Microsoft द्वारा बनाई गई XML Paper Specifications पर आधारित पेज लेआउट फ़ाइलों को दर्शाती है। |
| [OXPS](#OXPS) | OpenXPS फ़ाइल (.oxps) को दर्शाता है। |
| [TEX](#TEX) | LaTeX स्रोत दस्तावेज़ (.tex) को दर्शाता है, जो एक भाषा है जिसमें प्रोग्रामिंग और मार्क‑अप सुविधाएँ शामिल हैं, जो दस्तावेज़ों को टाइपसेट करने के लिए उपयोग होती हैं। |
| [PPT](#PPT) | PowerPoint प्रस्तुति (.ppt) को दर्शाता है, जो स्लाइडशो के रूप में प्रदर्शित करने के लिए स्लाइडों के संग्रह वाली PowerPoint फ़ाइल को दर्शाता है। |
| [PPTX](#PPTX) | PowerPoint Open XML प्रस्तुति (.pptx) को दर्शाता है, जो लोकप्रिय Microsoft PowerPoint एप्लिकेशन द्वारा बनाई गई प्रस्तुति फ़ाइलें हैं। |
| [PPS](#PPS) | PowerPoint स्लाइड शो (.pps) को दर्शाता है, जो स्लाइड शो उद्देश्यों के लिए Microsoft PowerPoint का उपयोग करके बनाई गई हैं। |
| [PPSX](#PPSX) | PowerPoint Open XML स्लाइड शो (.ppsx) फ़ाइलों को दर्शाता है, जो स्लाइड शो उद्देश्यों के लिए Microsoft PowerPoint 2007 और उसके बाद के संस्करणों का उपयोग करके बनाई गई हैं। |
| [ODP](#ODP) | OpenDocument Presentation (.odp) को दर्शाता है, जो OpenOffice.org द्वारा OASISOpen मानक में उपयोग किए जाने वाले प्रस्तुति फ़ाइल प्रारूप को दर्शाता है। |
| [FODP](#FODP) | OpenDocument Presentation (.fodp) को दर्शाता है, जो OpenDocument Flat XML Presentation को दर्शाता है। |
| [POT](#POT) | PowerPoint Template (.pot) को दर्शाता है, जो PowerPoint 97-2003 संस्करणों द्वारा निर्मित Microsoft PowerPoint टेम्पलेट फ़ाइलों को दर्शाता है। |
| [PPTM](#PPTM) | PowerPoint Open XML Macro-Enabled Presentation (.pptm) को दर्शाता है, जो Microsoft PowerPoint 2007 या उससे उच्च संस्करणों द्वारा निर्मित मैक्रो-सक्षम प्रस्तुति फ़ाइलें हैं। |
| [POTX](#POTX) | PowerPoint Open XML Presentation Template (.potx) को दर्शाता है, जो Microsoft PowerPoint 2007 और उसके बाद के संस्करणों द्वारा निर्मित Microsoft PowerPoint टेम्पलेट प्रस्तुतियों को दर्शाता है। |
| [POTM](#POTM) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) को दर्शाता है, जो मैक्रो समर्थन वाले Microsoft PowerPoint टेम्पलेट फ़ाइलें हैं। |
| [PPSM](#PPSM) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) को दर्शाता है, जो Microsoft PowerPoint 2007 या उससे उच्च संस्करणों द्वारा निर्मित मैक्रो-सक्षम स्लाइड शो फ़ाइल प्रारूप को दर्शाता है। |
| [OTP](#OTP) | OpenDocument Presentation Template (.otp) को दर्शाता है, जो OASIS OpenDocument मानक प्रारूप में अनुप्रयोगों द्वारा निर्मित प्रस्तुति टेम्पलेट फ़ाइलों को दर्शाता है। |
| [XLS](#XLS) | Excel Spreadsheet (.xls) को दर्शाता है, जो Excel बाइनरी फ़ाइल प्रारूप को दर्शाता है। |
| [EXCEL_2003_XML](#EXCEL-2003-XML) | Excel 2003 XML (SpreadsheetML) (.xml) को दर्शाता है, जो Excel बाइनरी फ़ाइल प्रारूप को दर्शाता है। |
| [NUMBERS](#NUMBERS) | Apple Numbers (.numbers) को दर्शाता है, जो Excel-समतुल्य बाइनरी फ़ाइल प्रारूप को दर्शाता है। |
| [XLSX](#XLSX) | Microsoft Excel Open XML Spreadsheet (.xlsx) को दर्शाता है, जो Microsoft Office 2007 के रिलीज़ के साथ Microsoft द्वारा प्रस्तुत Microsoft Excel दस्तावेज़ों के लिए एक प्रसिद्ध प्रारूप है। |
| [XLSM](#XLSM) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) को दर्शाता है, जो मैक्रो का समर्थन करने वाली स्प्रेडशीट फ़ाइल का प्रकार है। |
| [XLSB](#XLSB) | Excel Binary Spreadsheet (.xlsb) को दर्शाता है, जो Excel बाइनरी फ़ाइल प्रारूप को निर्दिष्ट करता है। |
| [CSV](#CSV) | Comma Separated Values File (.csv) को दर्शाता है, जो कॉमा द्वारा अलग किए गए मानों वाले डेटा रिकॉर्ड्स वाली सादा पाठ फ़ाइलों को दर्शाता है। |
| [TSV](#TSV) | Tab Separated Values File (.tsv) को दर्शाता है, जो टैब द्वारा अलग किए गए डेटा को सादा पाठ प्रारूप में दर्शाता है। |
| [ODS](#ODS) | OpenDocument Spreadsheet (.ods) को दर्शाता है, जो उपयोगकर्ता द्वारा संपादित किए जा सकने वाले OpenDocument Spreadsheet दस्तावेज़ प्रारूप को दर्शाता है। |
| [FODS](#FODS) | OpenDocument Flat XML Spreadsheet (.fods) को दर्शाता है। |
| [OTS](#OTS) | OpenDocument Spreadsheet Template (.ots) को दर्शाता है। |
| [XLAM](#XLAM) | Microsoft Excel Add-in (.xlam) को दर्शाता है। |
| [XLTM](#XLTM) | Microsoft Excel Macro-Enabled Template (.xltm) को दर्शाता है, जो Microsoft Excel द्वारा मैक्रो-सक्षम टेम्पलेट फ़ाइलों के रूप में उत्पन्न फ़ाइलों को दर्शाता है। |
| [XLT](#XLT) | Microsoft Excel Template (.xlt) को दर्शाता है, जो Microsoft Excel द्वारा निर्मित टेम्पलेट फ़ाइलें हैं, जो Microsoft Office सूट का हिस्सा स्प्रेडशीट अनुप्रयोग है। |
| [XLTX](#XLTX) | Excel Open XML Spreadsheet Template (.xltx) को दर्शाता है, जो Office OpenXML फ़ाइल प्रारूप विनिर्देशों पर आधारित Microsoft Excel टेम्पलेट्स को दर्शाता है। |
| [SXC](#SXC) | StarOffice Calc Spreadsheet (.sxc) को दर्शाता है। |
| [MPP](#MPP) | Microsoft Project File (.mpp) को दर्शाता है, जो एक Microsoft Project डेटा फ़ाइल है जो परियोजना प्रबंधन से संबंधित जानकारी को एकीकृत तरीके से संग्रहीत करती है। |
| [MPT](#MPT) | Microsoft Project टेम्प्लेट (.mpt) का प्रतिनिधित्व करता है, जिसमें बुनियादी जानकारी और संरचना के साथ .MPP फ़ाइलें बनाने के लिए दस्तावेज़ सेटिंग्स शामिल हैं। |
| [MPX](#MPX) | Microsoft Project Exchange फ़ाइल (.mpx) का प्रतिनिधित्व करता है, जो एक ASCII फ़ाइल फ़ॉर्मेट है जो Microsoft Project (MSP) और अन्य अनुप्रयोगों जैसे Primavera Project Planner, Sciforma, और Timerline Precision Estimating के बीच प्रोजेक्ट जानकारी स्थानांतरित करने के लिए उपयोग किया जाता है। |
| [AS](#AS) | ActionScript फ़ाइल (.as) का प्रतिनिधित्व करता है। |
| [AS_3](#AS-3) | ActionScript फ़ाइल (.as3) का प्रतिनिधित्व करता है। |
| [ASM](#ASM) | Assembly Language स्रोत कोड फ़ाइल (.asm) का प्रतिनिधित्व करता है। |
| [BAT](#BAT) | DOS बैच फ़ाइल (.bat) का प्रतिनिधित्व करता है। |
| [C](#C) | C/C++ स्रोत कोड फ़ाइल (.c) का प्रतिनिधित्व करता है। |
| [CC](#CC) | C++ स्रोत कोड फ़ाइल (.cc) का प्रतिनिधित्व करता है। |
| [CMAKE](#CMAKE) | CMake फ़ाइल (.cmake) का प्रतिनिधित्व करता है। |
| [CPP](#CPP) | C++ स्रोत कोड फ़ाइल (.cpp) का प्रतिनिधित्व करता है। |
| [CS](#CS) | C\# स्रोत कोड फ़ाइल (.cs) का प्रतिनिधित्व करता है, जो C\# प्रोग्रामिंग भाषा की स्रोत कोड फ़ाइल है। |
| [VB](#VB) | Visual Basic प्रोजेक्ट आइटम फ़ाइल (.vb) का प्रतिनिधित्व करता है, जो Visual Basic भाषा में बनाई गई स्रोत कोड फ़ाइल है। |
| [CSS](#CSS) | Cascading Style Sheet (.css) फ़ाइल का प्रतिनिधित्व करता है। |
| [CXX](#CXX) | C++ स्रोत कोड फ़ाइल (.cxx) का प्रतिनिधित्व करता है। |
| [DIFF](#DIFF) | पैच फ़ाइल (.diff) का प्रतिनिधित्व करता है। |
| [ERB](#ERB) | Ruby ERB स्क्रिप्ट (.erb) का प्रतिनिधित्व करता है। |
| [GROOVY](#GROOVY) | Groovy स्रोत कोड फ़ाइल (.groovy) का प्रतिनिधित्व करता है। |
| [H](#H) | C/C++/Objective-C हेडर फ़ाइल (.h) का प्रतिनिधित्व करता है। |
| [HAML](#HAML) | Haml स्रोत कोड फ़ाइल (.haml) का प्रतिनिधित्व करता है। |
| [HH](#HH) | C++ हेडर फ़ाइल (.hh) का प्रतिनिधित्व करता है। |
| [JAVA](#JAVA) | Java स्रोत कोड फ़ाइल (.java) का प्रतिनिधित्व करता है। |
| [JS](#JS) | JavaScript फ़ाइल (.js) का प्रतिनिधित्व करता है। |
| [JSON](#JSON) | JavaScript Object Notation फ़ाइल (.json) का प्रतिनिधित्व करता है। |
| [LESS](#LESS) | LESS स्टाइल शीट (.less) फ़ाइल का प्रतिनिधित्व करता है। |
| [LOG](#LOG) | Log फ़ाइल (.log) का प्रतिनिधित्व करता है। |
| [M](#M) | एक Objective-C इम्प्लीमेंटेशन फ़ाइल (.m) को दर्शाता है। |
| [MAKE](#MAKE) | एक Xcode मेकफ़ाइल स्क्रिप्ट (.make) को दर्शाता है। |
| [MD](#MD) | एक Markdown दस्तावेज़ फ़ाइल (.md) को दर्शाता है। |
| [ML](#ML) | एक ML स्रोत कोड फ़ाइल (.ml) को दर्शाता है। |
| [MM](#MM) | एक Objective-C++ स्रोत फ़ाइल (.mm) को दर्शाता है। |
| [PHP](#PHP) | एक PHP स्रोत कोड फ़ाइल (.php) को दर्शाता है। |
| [PL](#PL) | एक Perl स्क्रिप्ट (.pl) को दर्शाता है। |
| [PROPERTIES](#PROPERTIES) | एक Java प्रॉपर्टीज़ फ़ाइल (.properties) को दर्शाता है। |
| [PY](#PY) | एक Python स्क्रिप्ट (.py) को दर्शाता है। |
| [RB](#RB) | एक Ruby स्रोत कोड (.rb) फ़ाइल को दर्शाता है। |
| [RST](#RST) | एक reStructuredText फ़ाइल (.rst) को दर्शाता है। |
| [SASS](#SASS) | एक Syntactically Awesome StyleSheets फ़ाइल (.sass) को दर्शाता है। |
| [SCALA](#SCALA) | एक Scala स्रोत कोड फ़ाइल (.scala) को दर्शाता है। |
| [SCM](#SCM) | एक Scheme स्रोत कोड फ़ाइल (.scm) को दर्शाता है। |
| [SCRIPT](#SCRIPT) | एक Generic स्क्रिप्ट फ़ाइल (.script) को दर्शाता है। |
| [SH](#SH) | एक Bash शेल स्क्रिप्ट (.sh) को दर्शाता है। |
| [SML](#SML) | एक Standard ML स्रोत कोड फ़ाइल (.sml) को दर्शाता है। |
| [SQL](#SQL) | एक Structured Query Language डेटा फ़ाइल (.sql) को दर्शाता है। |
| [VIM](#VIM) | एक Vim सेटिंग्स फ़ाइल (.vim) को दर्शाता है। |
| [YAML](#YAML) | एक YAML दस्तावेज़ (.yaml) को दर्शाता है। |
| [DOC](#DOC) | एक Microsoft Word दस्तावेज़ (.doc) फ़ाइल को दर्शाता है। |
| [DOCX](#DOCX) | एक Microsoft Word Open XML दस्तावेज़ (.docx) फ़ाइल को दर्शाता है। |
| [CHM](#CHM) | एक Microsoft Compiled HTML Help फ़ाइल (.chm) को दर्शाता है। |
| [DOCM](#DOCM) | एक Word Open XML मैक्रो-एनेबल्ड दस्तावेज़ (.docm) फ़ाइल को दर्शाता है। |
| [DOT](#DOT) | एक Word दस्तावेज़ टेम्पलेट (.dot) फ़ाइल को दर्शाता है। |
| [DOTX](#DOTX) | एक Word Open XML दस्तावेज़ टेम्पलेट (.dotx) फ़ाइल का प्रतिनिधित्व करता है। |
| [DOTM](#DOTM) | एक Word Open XML मैक्रो-सक्षम दस्तावेज़ टेम्पलेट (.dotm) फ़ाइल का प्रतिनिधित्व करता है। |
| [RTF](#RTF) | एक Rich Text Format फ़ाइल (.rtf) का प्रतिनिधित्व करता है। |
| [TXT](#TXT) | एक Plain Text फ़ाइल (.txt) का प्रतिनिधित्व करता है। |
| [ODT](#ODT) | एक OpenDocument टेक्स्ट दस्तावेज़ (.odt) का प्रतिनिधित्व करता है। |
| [OTT](#OTT) | एक OpenDocument दस्तावेज़ टेम्पलेट (.ott) का प्रतिनिधित्व करता है। |
| [VCF](#VCF) | एक vCard फ़ाइल (.vcf) का प्रतिनिधित्व करता है, जो संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल फ़ॉर्मेट है। |
| [AI](#AI) | एक Adobe Illustrator फ़ाइल (.ai) का प्रतिनिधित्व करता है, जो Adobe Illustrator ड्रॉइंग्स के लिए फ़ाइल फ़ॉर्मेट है। |
| [PSM1](#PSM1) | एक PowerShell स्क्रिप्ट मॉड्यूल फ़ाइल (.psm1) का प्रतिनिधित्व करता है। |
| [PS1](#PS1) | एक PowerShell स्क्रिप्ट फ़ाइल (.ps1) का प्रतिनिधित्व करता है। |
| [PSD1](#PSD1) | एक PowerShell स्क्रिप्ट मॉड्यूल मैनिफेस्ट फ़ाइल (.psd1) का प्रतिनिधित्व करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | फ़ाइल एक्सटेंशन को फ़ाइल प्रकार से मैप करता है। |
| [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | फ़ाइल नाम या फ़ाइल पथ से फ़ाइल एक्सटेंशन निकालता है और उसे फ़ाइल प्रकार से मैप करता है। |
| [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | फ़ाइल मीडिया प्रकार को फ़ाइल प्रकार से मैप करता है। |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है। |
| [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है। |
| [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है। |
| [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है। |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | समर्थित फ़ाइल प्रकारों को पुनः प्राप्त करता है। |
| [detectCharset(String filePath)](#detectCharset-java.lang.String-) | पथ द्वारा टेक्स्ट [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) और [CSV](../../com.groupdocs.viewer/filetype\#CSV) फ़ाइलों की कैरेक्टर सेट का पता लगाने का प्रयास करता है। |
| [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | स्ट्रीम द्वारा टेक्स्ट [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) और [CSV](../../com.groupdocs.viewer/filetype\#CSV) फ़ाइल की कैरेक्टर सेट का पता लगाने का प्रयास करता है। |
| [getFileFormat()](#getFileFormat--) | फ़ाइल फ़ॉर्मेट का नाम प्राप्त करता है, उदाहरण के लिए "Microsoft Word Document"। |
| [getExtension()](#getExtension--) | फ़ाइल एक्सटेंशन उपसर्ग (बिंदु "." सहित) प्राप्त करता है, उदाहरण के लिए ".doc"। |
| [toString()](#toString--) | वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


अज्ञात फ़ाइल प्रकार का प्रतिनिधित्व करता है।

### ZIP {#ZIP}
```
public static final FileType ZIP
```


एक ज़िप्ड फ़ाइल (.zip) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों या डायरेक्टरीज़ को रख सकती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/compression/zip

### TAR {#TAR}
```
public static final FileType TAR
```


एक समेकित Unix फ़ाइल आर्काइव (.tar) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों को इकट्ठा करने के लिए बनाया गया है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/compression/tar

### XZ {#XZ}
```
public static final FileType XZ
```


एक XZ फ़ाइल (.xz) का प्रतिनिधित्व करता है जो LZMA एल्गोरिदम पर आधारित उच्च अनुपात संपीड़न एल्गोरिदम से संकुचित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://fileinfo.com/extension/xz

### TXZ {#TXZ}
```
public static final FileType TXZ
```


एक समेकित Unix फ़ाइल आर्काइव (.txz, .tar.xz) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों को इकट्ठा करने के लिए बनाया गया है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://fileinfo.com/extension/txz

### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


एक समेकित Unix फ़ाइल आर्काइव (.txz, .tar.xz) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों को इकट्ठा करने के लिए बनाया गया है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://fileinfo.com/extension/txz

### TGZ {#TGZ}
```
public static final FileType TGZ
```


एक समेकित Unix फ़ाइल आर्काइव (.tgz, .tar.gz) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों को इकट्ठा करने के लिए बनाया गया है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://fileinfo.com/extension/tgz

### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


एक समेकित Unix फ़ाइल आर्काइव (.tgz, .tar.gz) का प्रतिनिधित्व करता है जो एक या अधिक फ़ाइलों को इकट्ठा करने के लिए बनाया गया है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://fileinfo.com/extension/tgz

### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


BZIP2 ओपन-सोर्स संपीड़न विधि का उपयोग करके उत्पन्न Bzip2 संपीड़ित फ़ाइल (.bz2) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/compression/bz2

### RAR {#RAR}
```
public static final FileType RAR
```


RAR (WINRAR संस्करण 4) संपीड़न विधि का उपयोग करके उत्पन्न Roshal Archive (.rar) संपीड़ित फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/compression/rar

### GZ {#GZ}
```
public static final FileType GZ
```


gzip संपीड़न एप्लिकेशन से बनाई गई Gnu Zipped File (.gz) संपीड़ित फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/compression/gz

### GZIP {#GZIP}
```
public static final FileType GZIP
```


Unix सिस्टम में उपयोग किए जाने वाले Compress प्रोग्राम को बदलने के लिए एक मुफ्त उपयोगिता के रूप में प्रस्तुत Gnu Zipped File (.gzip) संपीड़ित फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/compression/gz

### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


7Zip (.7z, .7zip) फ़ाइल का प्रतिनिधित्व करता है, जो LZMA और LZMA2 संपीड़न के साथ एक मुफ्त ओपन-सोर्स आर्काइवर है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/compression/7z/

### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio एक सामान्य फ़ाइल आर्काइवर उपयोगिता और उसका संबंधित फ़ाइल फ़ॉर्मेट है। यह मुख्य रूप से Unix-समरूप कंप्यूटर ऑपरेटिंग सिस्टम पर स्थापित होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/compression/cpio

### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


ZST फ़ाइल एक संपीड़ित फ़ाइल है जो Zstandard (zstd) संपीड़न एल्गोरिदम से उत्पन्न होती है। यह एल्गोरिदम द्वारा लॉसलेस संपीड़न के साथ बनाई गई फ़ाइल है। ZST फ़ाइलों का उपयोग विभिन्न प्रकार की फ़ाइलों जैसे डेटाबेस, फ़ाइल सिस्टम, नेटवर्क और गेम्स को संपीड़ित करने के लिए किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/compression/zst/

### TZST {#TZST}
```
public static final FileType TZST
```


TZST फ़ाइलें (.tar.zst, .tzst) Zstandard अभिलेख (ZST) हैं, जो आंतरिक रूप से एक एकीकृत Unix फ़ाइल अभिलेख (Tar) को समाहित करती हैं, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए Unix-आधारित उपयोगिता द्वारा बनाई गई है।

### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


TZST फ़ाइलें (.tar.zst, .tzst) Zstandard अभिलेख (ZST) हैं, जो आंतरिक रूप से एक एकीकृत Unix फ़ाइल अभिलेख (Tar) को समाहित करती हैं, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए Unix-आधारित उपयोगिता द्वारा बनाई गई है।

### ISO {#ISO}
```
public static final FileType ISO
```


ISO ऑप्टिकल डिस्क इमेज एक अनकम्प्रेस्ड आर्काइव डिस्क इमेज फ़ाइल है जो CD या DVD जैसे ऑप्टिकल डिस्क पर संपूर्ण डेटा की सामग्री को दर्शाती है, ISO-9660 मानक पर आधारित। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/compression/iso/

### LHA {#LHA}
```
public static final FileType LHA
```


LHA या LZH एक फ्रीवेयर संपीड़न उपयोगिता और संबंधित फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/compression/lzh/

### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (या CAB) माइक्रोसॉफ्ट विंडोज़ के लिए एक आर्काइव-फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://en.wikipedia.org/wiki/Cabinet_%28file_format%29

### DXF {#DXF}
```
public static final FileType DXF
```


Drawing Exchange Format फ़ाइल (.dxf) का प्रतिनिधित्व करता है, जो AutoCAD ड्रॉइंग फ़ाइल का टैग्ड डेटा प्रतिनिधित्व है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/cad/dxf

### DWG {#DWG}
```
public static final FileType DWG
```


AutoCAD Drawing Database फ़ाइल (.dwg) का प्रतिनिधित्व करता है, जो 2D और 3D डिज़ाइन डेटा रखने के लिए उपयोग की जाने वाली स्वामित्व बाइनरी फ़ाइलें हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/cad/dwg

### DWT {#DWT}
```
public static final FileType DWT
```


AutoCAD Drawing Template (.dwt) का प्रतिनिधित्व करता है, जो AutoCAD ड्रॉइंग टेम्प्लेट फ़ाइल है जिसे ड्रॉइंग बनाने के लिए शुरुआती रूप में उपयोग किया जाता है और इसे DWG फ़ाइलों के रूप में सहेजा जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### STL {#STL}
```
public static final FileType STL
```


Stereolithography फ़ाइल (.stl) का प्रतिनिधित्व करता है, जो एक परस्पर बदलने योग्य फ़ाइल फ़ॉर्मेट है जो 3-आयामी सतह ज्यामिति को दर्शाता है। यह तेज़ प्रोटोटाइपिंग, 3D प्रिंटिंग और कंप्यूटर-सहायता निर्माṇ में सामान्यतः उपयोग होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/cad/stl

### IFC {#IFC}
```
public static final FileType IFC
```


Industry Foundation Classes फ़ाइल (.ifc) का प्रतिनिधित्व करता है, जो भवन वस्तुओं और उनकी विशेषताओं के आयात और निर्यात के लिए अंतर्राष्ट्रीय मानक स्थापित करने वाला फ़ाइल फ़ॉर्मेट है। यह विभिन्न सॉफ़्टवेयर अनुप्रयोगों के बीच अंतःक्रियाशीलता को सक्षम करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### DWF {#DWF}
```
public static final FileType DWF
```


Design Web Format फ़ाइल (.dwf) का प्रतिनिधित्व करता है, जो 2D/3D ड्रॉइंग को देखने, समीक्षा करने या प्रिंट करने के लिए एक संपीड़ित फ़ाइल फ़ॉर्मेट है। इसमें डिज़ाइन डेटा के हिस्से के रूप में ग्राफ़िक्स और टेक्स्ट शामिल हैं और संपीड़न के कारण फ़ाइल आकार घटता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### FBX {#FBX}
```
public static final FileType FBX
```


Autodesk FBX Interchange फ़ाइल (FilmBoX) (.fbx) का प्रतिनिधित्व करता है, जो एक 3D मॉडल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/cad/fbx

### DWFX {#DWFX}
```
public static final FileType DWFX
```


Design Web Format फ़ाइल XPS (.dwfx) का प्रतिनिधित्व करता है, जो XPS दस्तावेज़ के रूप में 2D/3D ड्रॉइंग को देखने, समीक्षा करने या प्रिंट करने के लिए एक संपीड़ित फ़ॉर्मेट है। इसमें डिज़ाइन डेटा के हिस्से के रूप में ग्राफ़िक्स और टेक्स्ट शामिल हैं और संपीड़न के कारण फ़ाइल आकार घटता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/cad/dwfx

### DGN {#DGN}
```
public static final FileType DGN
```


MicroStation Design फ़ाइल (.dgn) का प्रतिनिधित्व करता है, जो MicroStation और Intergraph Interactive Graphics Design System जैसे CAD अनुप्रयोगों द्वारा निर्मित और समर्थित ड्रॉइंग हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/cad/dgn

### PLT {#PLT}
```
public static final FileType PLT
```


एक PLT (HPGL) फ़ाइल (.plt) का प्रतिनिधित्व करता है, जो Autodesk, Inc. द्वारा प्रस्तुत एक वेक्टर-आधारित प्लॉटर फ़ाइल है। इसमें किसी विशिष्ट CAD फ़ाइल की जानकारी होती है, और सभी छवियों को बिंदुओं के बजाय रेखाओं का उपयोग करके मुद्रित किया जाता है, जिससे उत्पादन में सटीकता और शुद्धता सुनिश्चित होती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/cad/plt

### CF2 {#CF2}
```
public static final FileType CF2
```


एक Common File Format फ़ाइल (.cf2) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://fileinfo.com/extension/cf2

### OBJ {#OBJ}
```
public static final FileType OBJ
```


एक Wavefront 3D Object फ़ाइल (.obj) का प्रतिनिधित्व करता है, जो Wavefront Technologies द्वारा प्रस्तुत एक 3D इमेज फ़ाइल है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/3d/obj/

### HPG {#HPG}
```
public static final FileType HPG
```


एक PLT (HPGL) फ़ाइल (.hpg) का प्रतिनिधित्व करता है। यह HP ग्राफ़िक्स लैंग्वेज (HPGL) में प्लॉटर फ़ाइलों के लिए उपयोग किया जाने वाला फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://fileinfo.com/extension/hpg

### IGS {#IGS}
```
public static final FileType IGS
```


एक Initial Graphics Exchange Specification (IGES) फ़ाइल (.igs) को दर्शाता है।

### VSD {#VSD}
```
public static final FileType VSD
```


एक Visio Drawing फ़ाइल (.vsd) का प्रतिनिधित्व करता है, जो Microsoft Visio एप्लिकेशन से बनाई गई ड्रॉइंग्स हैं, जो विभिन्न ग्राफ़िकल ऑब्जेक्ट्स और उनके अंतर्संबंधों को दर्शाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/image/vsd

### VSDX {#VSDX}
```
public static final FileType VSDX
```


एक Visio Drawing फ़ाइल (.vsdx) का प्रतिनिधित्व करता है, जो Microsoft Office 2013 से शुरू होकर प्रस्तुत Microsoft Visio फ़ाइल फ़ॉर्मेट को दर्शाता है। इसने पहले के Microsoft Visio संस्करणों द्वारा समर्थित बाइनरी फ़ाइल फ़ॉर्मेट (.VSD) को प्रतिस्थापित किया। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/image/vsdx

### VSS {#VSS}
```
public static final FileType VSS
```


एक Visio Stencil फ़ाइल (.vss) का प्रतिनिधित्व करता है, जो Microsoft Visio 2007 और उससे पहले के संस्करणों से बनाई गई स्टेंसिल फ़ाइलें हैं। स्टेंसिल फ़ाइलें ड्रॉइंग ऑब्जेक्ट्स प्रदान करती हैं जिन्हें .VSD Visio ड्रॉइंग में शामिल किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/image/vss

### VSSX {#VSSX}
```
public static final FileType VSSX
```


एक Visio Stencil फ़ाइल (.vssx) का प्रतिनिधित्व करता है, जो Microsoft Visio 2013 और उसके बाद के संस्करणों से बनाई गई ड्रॉइंग स्टेंसिल हैं। VSSX फ़ाइल फ़ॉर्मेट को Visio 2013 और उससे ऊपर के संस्करणों में खोला जा सकता है। Visio फ़ाइलें विभिन्न ड्रॉइंग तत्वों जैसे आकार, कनेक्टर, फ्लोचार्ट, नेटवर्क लेआउट, UML डायग्राम आदि को दर्शाने के लिए जानी जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/image/vssx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


एक Visio Macro-Enabled Drawing (.vsdm) का प्रतिनिधित्व करता है, जो Microsoft Visio एप्लिकेशन से बनाई गई ड्रॉइंग फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। VSDM फ़ाइलें OPC/XML ड्रॉइंग्स हैं जो VSDX के समान हैं, लेकिन फ़ाइल खोलने पर मैक्रो चलाने की क्षमता भी प्रदान करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/image/vsdm

### VST {#VST}
```
public static final FileType VST
```


एक Visio Drawing टेम्पलेट (.vst) का प्रतिनिधित्व करता है, जो Microsoft Visio से बनाई गई वेक्टर इमेज फ़ाइलें हैं। ये आगे की फ़ाइलें बनाने के लिए टेम्पलेट के रूप में कार्य करती हैं और नई Visio ड्रॉइंग्स बनाने के लिए उपयोग किए जाने वाले डिफ़ॉल्ट लेआउट और सेटिंग्स को समाहित करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/image/vst

### VSTX {#VSTX}
```
public static final FileType VSTX
```


एक Visio Drawing टेम्पलेट (.vstx) का प्रतिनिधित्व करता है, जो Microsoft Visio 2013 और उसके बाद के संस्करणों से बनाई गई ड्रॉइंग टेम्पलेट फ़ाइलें हैं। ये VSTX फ़ाइलें .VSDX फ़ाइलों के रूप में सहेजी गई Visio ड्रॉइंग्स बनाने के लिए एक प्रारंभिक बिंदु प्रदान करती हैं, जिसमें डिफ़ॉल्ट लेआउट और सेटिंग्स होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


एक Visio Macro-Enabled Drawing टेम्पलेट (.vstm) का प्रतिनिधित्व करता है, जो Microsoft Visio से बनाई गई टेम्पलेट फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। VSTM टेम्पलेट से बनाई गई फ़ाइलें Visual Basic for Applications (VBA) कोड में विकसित मैक्रो को चला सकती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


एक Visio Macro-Enabled Stencil फ़ाइल (.vssm) का प्रतिनिधित्व करता है, जो Microsoft Visio Stencil फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। जब VSSM फ़ाइल खोली जाती है, तो इच्छित फ़ॉर्मेटिंग और डायग्राम में आकारों की स्थिति प्राप्त करने के लिए मैक्रो चलाए जा सकते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


एक Visio Stencil XML फ़ाइल (.vsx) का प्रतिनिधित्व करता है, जो Microsoft Visio में डायग्राम बनाने के लिए उपयोग किए जाने वाले ड्रॉइंग्स और आकारों से बनी स्टेंसिल को दर्शाता है। VSX फ़ाइलें XML फ़ाइल फ़ॉर्मेट में सहेजी जाती हैं और Visio 2013 तक समर्थित थीं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


एक Visio Template XML फ़ाइल (.vtx) का प्रतिनिधित्व करता है, जो XML फ़ाइल फ़ॉर्मेट में डिस्क पर सहेजा गया Microsoft Visio ड्रॉइंग टेम्पलेट है। यह टेम्पलेट समान सेटिंग्स के साथ कई Visio फ़ाइलें बनाने के लिए बुनियादी सेटिंग्स प्रदान करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/image/vtx

### VDW {#VDW}
```
public static final FileType VDW
```


एक Visio Web Drawing (.vdw) का प्रतिनिधित्व करता है, जो वेब ड्रॉइंग को रेंडर करने के लिए आवश्यक स्ट्रीम्स और स्टोरेज को निर्दिष्ट करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/web/vdw

### VDX {#VDX}
```
public static final FileType VDX
```


Visio Drawing XML फ़ाइल (.vdx) का प्रतिनिधित्व करता है, जो Microsoft Visio में बनाई गई किसी भी ड्राइंग या चार्ट को दर्शाता है लेकिन .VDX एक्सटेंशन के साथ XML फ़ॉर्मेट में सहेजी जाती है। Visio ड्रॉइंग XML फ़ाइल Microsoft द्वारा विकसित Visio सॉफ़्टवेयर में बनाई जाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook फ़ाइल (.epub) का प्रतिनिधित्व करता है, जो एक ई-बुक फ़ाइल फ़ॉर्मेट है जो प्रकाशकों और उपभोक्ताओं के लिए मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। यह फ़ॉर्मेट कई ई-रीडर और सॉफ़्टवेयर अनुप्रयोगों द्वारा समर्थित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket eBook (.mobi) का प्रतिनिधित्व करता है, जो सबसे अधिक उपयोग किए जाने वाले ईबुक फ़ाइल फ़ॉर्मेट्स में से एक है। यह फ़ॉर्मेट पुराने OEB (Open Ebook Format) फ़ॉर्मेट का उन्नयन है और Mobipocket Reader के लिए एक स्वामित्व फ़ॉर्मेट के रूप में उपयोग किया जाता था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Amazon Kindle Format 8 (KF8) ईबुक Amazon Kindle डिवाइसों के लिए विकसित डिजिटल फ़ाइल फ़ॉर्मेट है। यह फ़ॉर्मेट पुराने AZW फ़ाइलों का उन्नयन है और केवल Kindle Fire डिवाइसों पर उपयोग किया जाता है, साथ ही पूर्वज फ़ाइल फ़ॉर्मेट जैसे MOBI और AZW के साथ पीछे की संगतता रखता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/ebook/azw3

### MSG {#MSG}
```
public static final FileType MSG
```


Outlook Mail Message (.msg) का प्रतिनिधित्व करता है, जो Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, नियुक्तियों या अन्य कार्यों को संग्रहीत करने के लिए उपयोग किया जाने वाला फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/email/msg

### EML {#EML}
```
public static final FileType EML
```


E-Mail Message (.eml) का प्रतिनिधित्व करता है, जो Outlook और अन्य संबंधित अनुप्रयोगों द्वारा सहेजे गए ईमेल संदेशों को दर्शाता है। लगभग सभी ईमेल क्लाइंट इस फ़ाइल फ़ॉर्मेट का समर्थन करते हैं क्योंकि यह RFC-822 इंटरनेट संदेश फ़ॉर्मेट मानक के अनुरूप है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/email/eml

### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail Message (.emlx) का प्रतिनिधित्व करता है, जिसे Apple ने लागू और विकसित किया है। Apple Mail एप्लिकेशन ईमेल निर्यात करने के लिए EMLX फ़ाइल फ़ॉर्मेट का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/email/emlx

### PST {#PST}
```
public static final FileType PST
```


Outlook Personal Information Store File (.pst) का प्रतिनिधित्व करता है, जो Outlook Personal Storage Files (जिसे Personal Storage Table भी कहा जाता है) को दर्शाता है, जो विभिन्न उपयोगकर्ता जानकारी संग्रहीत करते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/email/pst

### OST {#OST}
```
public static final FileType OST
```


Outlook Offline Data File (.ost) का प्रतिनिधित्व करता है, जो Exchange Server के साथ Microsoft Outlook का उपयोग करके पंजीकरण के बाद स्थानीय मशीन पर ऑफ़लाइन मोड में उपयोगकर्ता के मेलबॉक्स डेटा को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/email/ost

### TIF {#TIF}
```
public static final FileType TIF
```


Tagged Image File (.tif) का प्रतिनिधित्व करता है, जो रास्टर इमेजेज़ को दर्शाता है जो इस फ़ाइल फ़ॉर्मेट मानक के अनुरूप विभिन्न उपकरणों पर उपयोग के लिए बनाए गए हैं। यह कई रंग स्थानों में द्वि-स्तरीय, ग्रेस्केल, पैलेट-रंग, और पूर्ण-रंग इमेज डेटा का वर्णन करने में सक्षम है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/tiff

### TIFF {#TIFF}
```
public static final FileType TIFF
```


Tagged Image File Format (.tiff) का प्रतिनिधित्व करता है, जो रास्टर इमेजेज़ को दर्शाता है जो इस फ़ाइल फ़ॉर्मेट मानक के अनुरूप विभिन्न उपकरणों पर उपयोग के लिए बनाए गए हैं। यह कई रंग स्थानों में द्वि-स्तरीय, ग्रेस्केल, पैलेट-रंग, और पूर्ण-रंग इमेज डेटा का वर्णन करने में सक्षम है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/tiff

### JPG {#JPG}
```
public static final FileType JPG
```


JPEG Image (.jpg) का प्रतिनिधित्व करता है, जो एक प्रकार का इमेज फ़ॉर्मेट है जिसे लॉसी कम्प्रेशन विधि से सहेजा जाता है। कम्प्रेशन के परिणामस्वरूप आउटपुट इमेज संग्रह आकार और इमेज गुणवत्ता के बीच संतुलन बनाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG Image (.jpeg) का प्रतिनिधित्व करता है, जो एक प्रकार का इमेज फ़ॉर्मेट है जिसे लॉसी कम्प्रेशन विधि से सहेजा जाता है। कम्प्रेशन के परिणामस्वरूप आउटपुट इमेज संग्रह आकार और इमेज गुणवत्ता के बीच संतुलन बनाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG File Interchange Format (.jfif) एक इमेज है जिसे प्लेटफ़ॉर्मों के बीच तेज़ आदान-प्रदान के लिए विकसित किया गया था। यह फ़ॉर्मेट JPEG कम्प्रेशन का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/jfif

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) का प्रतिनिधित्व करता है, जो एक प्रकार का रास्टर इमेज फ़ाइल फ़ॉर्मेट है जो लॉसलेस कम्प्रेशन का उपयोग करता है। यह फ़ाइल फ़ॉर्मेट Graphics Interchange Format (GIF) के विकल्प के रूप में बनाया गया था और इसमें कोई कॉपीराइट प्रतिबंध नहीं है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/png

### GIF {#GIF}
```
public static final FileType GIF
```


एक ग्राफ़िकल इंटरचेंज फ़ॉर्मेट फ़ाइल (.gif) का प्रतिनिधित्व करता है, जो अत्यधिक संकुचित छवि का एक प्रकार है। प्रत्येक छवि के लिए, GIF आमतौर पर प्रति पिक्सेल अधिकतम 8 बिट और पूरे चित्र में अधिकतम 256 रंगों की अनुमति देता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/gif

### APNG {#APNG}
```
public static final FileType APNG
```


एक एनीमेटेड पोर्टेबल नेटवर्क ग्राफिक (.apng) का प्रतिनिधित्व करता है, जो PNG फ़ॉर्मेट का एक विस्तार है जो एनीमेशन का समर्थन करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/apng

### BMP {#BMP}
```
public static final FileType BMP
```


एक बिटमैप इमेज फ़ाइल (.bmp) का प्रतिनिधित्व करता है, जिसका उपयोग बिटमैप डिजिटल छवियों को संग्रहीत करने के लिए किया जाता है। ये छवियां ग्राफ़िक्स एडेप्टर से स्वतंत्र होती हैं और इन्हें डिवाइस इंडिपेंडेंट बिटमैप (DIB) फ़ाइल फ़ॉर्मेट भी कहा जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/bmp

### ICO {#ICO}
```
public static final FileType ICO
```


एक आइकन फ़ाइल (.ico) का प्रतिनिधित्व करता है, जो माइक्रोसॉफ्ट विंडोज़ पर एप्लिकेशन के प्रतिनिधित्व के लिए आइकन के रूप में उपयोग की जाने वाली इमेज फ़ाइल प्रकार है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/ico

### TGA {#TGA}
```
public static final FileType TGA
```


एक ट्रूविज़न TGA (TARGA) फ़ाइल का प्रतिनिधित्व करता है, जिसका उपयोग TRUEVISION द्वारा विकसित बिटमैप डिजिटल छवियों को संग्रहीत करने के लिए किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/tga

### JP_2 {#JP-2}
```
public static final FileType JP_2
```


एक JPEG 2000 कोर इमेज फ़ाइल (.jp2) का प्रतिनिधित्व करता है, जो एक इमेज कोडिंग सिस्टम और अत्याधुनिक इमेज संपीड़न मानक है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/jp2

### JPF {#JPF}
```
public static final FileType JPF
```


एक JPEG 2000 इमेज फ़ाइल (.jpf) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/image/jpf

### JPX {#JPX}
```
public static final FileType JPX
```


एक JPEG 2000 इमेज फ़ाइल (.jpx) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/jpx

### JPM {#JPM}
```
public static final FileType JPM
```


एक JPEG 2000 इमेज फ़ाइल (.jpm) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/jpm

### J2C {#J2C}
```
public static final FileType J2C
```


एक JPEG 2000 कोड इनपुटस्ट्रीम (.j2c) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/j2c

### J2K {#J2K}
```
public static final FileType J2K
```


एक JPEG 2000 कोड स्ट्रीम (.j2k) का प्रतिनिधित्व करता है, जो DCT संपीड़न के बजाय वेवलेट संपीड़न का उपयोग करके संकुचित इमेज है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/j2k

### JPC {#JPC}
```
public static final FileType JPC
```


एक JPEG 2000 कोड स्ट्रीम (.jpc) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/jpc

### JLS {#JLS}
```
public static final FileType JLS
```


एक JPEG-LS (JLS) फ़ाइल (.jls) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://fileinfo.com/extension/jls

### DIB {#DIB}
```
public static final FileType DIB
```


एक डिवाइस इंडिपेंडेंट बिटमैप फ़ाइल (.dib) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/dib

### WMF {#WMF}
```
public static final FileType WMF
```


एक विंडोज़ मेटा फ़ाइल (.wmf) का प्रतिनिधित्व करता है, जो वेक्टर और बिटमैप-फ़ॉर्मेट इमेज डेटा को संग्रहीत करने के लिए माइक्रोसॉफ्ट विंडोज़ मेटा फ़ाइल (WMF) को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/wmf

### WMZ {#WMZ}
```
public static final FileType WMZ
```


एक संकुचित विंडोज़ मेटा फ़ाइल (.wmz) का प्रतिनिधित्व करता है, जो वेक्टर और बिटमैप-फ़ॉर्मेट इमेज डेटा को संग्रहीत करने के लिए GZIP आर्काइव में संकुचित माइक्रोसॉफ्ट विंडोज़ मेटा फ़ाइल (WMF) को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://fileinfo.com/extension/wmz#compressed_windows_metafile

### EMF {#EMF}
```
public static final FileType EMF
```


एक एन्हांस्ड विंडोज़ मेटा फ़ाइल (.emf) का प्रतिनिधित्व करता है, जो ग्राफ़िकल इमेजेज़ को डिवाइस-स्वतंत्र रूप से दर्शाता है। EMF के मेटा फ़ाइलों में कालानुक्रमिक क्रम में परिवर्तनीय-लंबाई वाले रिकॉर्ड होते हैं जो किसी भी आउटपुट डिवाइस पर पार्स करने के बाद संग्रहीत इमेज को रेंडर कर सकते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/emf

### EMZ {#EMZ}
```
public static final FileType EMZ
```


एक विंडोज़ संकुचित एन्हांस्ड मेटा फ़ाइल (.emz) का प्रतिनिधित्व करता है, जो GZIP द्वारा डिवाइस-स्वतंत्र रूप से संकुचित ग्राफ़िकल इमेजेज़ को दर्शाता है। EMF के मेटा फ़ाइलों में कालानुक्रमिक क्रम में परिवर्तनीय-लंबाई वाले रिकॉर्ड होते हैं जो किसी भी आउटपुट डिवाइस पर पार्स करने के बाद संग्रहीत इमेज को रेंडर कर सकते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/emz

### WEBP {#WEBP}
```
public static final FileType WEBP
```


एक WebP इमेज (.webp) का प्रतिनिधित्व करता है, जो लॉसलेस और लॉसी संपीड़न पर आधारित एक आधुनिक रास्टर वेब इमेज फ़ाइल फ़ॉर्मेट है। यह समान इमेज गुणवत्ता प्रदान करता है जबकि इमेज आकार को काफी कम करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/webp

### DNG {#DNG}
```
public static final FileType DNG
```


एक डिजिटल नेगेटिव स्पेसिफिकेशन (.dng) का प्रतिनिधित्व करता है, जो कच्ची फ़ाइलों के संग्रह के लिए उपयोग किया जाने वाला डिजिटल कैमरा इमेज फ़ॉर्मेट है। इसे एडोब ने सितंबर 2004 में विकसित किया था और यह मुख्यतः डिजिटल फोटोग्राफी के लिए उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/dng

### CDR {#CDR}
```
public static final FileType CDR
```


एक CorelDraw वेक्टर ग्राफ़िक ड्राइंग (.cdr) का प्रतिनिधित्व करता है, जो CorelDRAW के साथ मूल रूप से निर्मित एक वेक्टर ड्राइंग इमेज फ़ाइल है, जो डिजिटल रूप से एन्कोडेड और संकुचित छवियों को संग्रहीत करती है। एक CDR ड्राइंग फ़ाइल में टेक्स्ट, लाइन्स, शेप्स, इमेजेज़, रंग और इफ़ेक्ट्स होते हैं जो इमेज सामग्री के वेक्टर प्रतिनिधित्व के लिए होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/cdr

### CMX {#CMX}
```
public static final FileType CMX
```


एक Corel Exchange (.cmx) का प्रतिनिधित्व करता है, जो एक ड्राइंग इमेज फ़ाइल है जिसमें वेक्टर ग्राफ़िक्स और बिटमैप ग्राफ़िक्स दोनों हो सकते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/image/cmx

### DJVU {#DJVU}
```
public static final FileType DJVU
```


एक DjVu इमेज (.djvu) का प्रतिनिधित्व करता है, जो एक ग्राफ़िक्स फ़ाइल फ़ॉर्मेट है जो स्कैन किए गए दस्तावेज़ों और पुस्तकों के लिए अभिप्रेत है, विशेष रूप से उन में जिनमें पाठ, चित्र, छवियां और फ़ोटोग्राफ़ का संयोजन होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/image/djvu

### CGM {#CGM}
```
public static final FileType CGM
```


एक कंप्यूटर ग्राफ़िक्स मेटा फ़ाइल (.cgm) का प्रतिनिधित्व करता है, जो एक मुक्त, प्लेटफ़ॉर्म-स्वतंत्र, अंतरराष्ट्रीय मानक मेटा फ़ाइल फ़ॉर्मेट है जो वेक्टर ग्राफ़िक्स (2D), रास्टर ग्राफ़िक्स और पाठ को संग्रहीत और विनिमय करने के लिए उपयोग होता है। CGM ऑब्जेक्ट‑ओरिएंटेड दृष्टिकोण का उपयोग करता है और इमेज उत्पादन के लिए कई फ़ंक्शन प्रदान करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### PCL {#PCL}
```
public static final FileType PCL
```


एक प्रिंटर कमांड लैंग्वेज दस्तावेज़ (.pcl) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### PSD {#PSD}
```
public static final FileType PSD
```


एक Adobe Photoshop दस्तावेज़ (.psd) का प्रतिनिधित्व करता है, जो Adobe Photoshop का मूल फ़ाइल फ़ॉर्मेट है जो ग्राफ़िक्स डिज़ाइन और विकास के लिए उपयोग होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/image/psd

### PSB {#PSB}
```
public static final FileType PSB
```


एक Photoshop Large Document Format (.psb) का प्रतिनिधित्व करता है, जो Adobe Photoshop में ग्राफ़िक्स डिज़ाइन और विकास के लिए उपयोग होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/image/psb

### DCM {#DCM}
```
public static final FileType DCM
```


एक DICOM इमेज (.dcm) का प्रतिनिधित्व करता है, जो एक डिजिटल इमेज है जो रोगियों की चिकित्सा जानकारी जैसे MRI, CT स्कैन और अल्ट्रासाउंड इमेज को संग्रहीत करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/image/dcm

### PS {#PS}
```
public static final FileType PS
```


एक PostScript फ़ाइल (.ps) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### EPS {#EPS}
```
public static final FileType EPS
```


एक Encapsulated PostScript फ़ाइल (.eps) का प्रतिनिधित्व करता है, जो एक Encapsulated PostScript भाषा प्रोग्राम का वर्णन करता है जो एक पृष्ठ की उपस्थिति को परिभाषित करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### ODG {#ODG}
```
public static final FileType ODG
```


एक OpenDocument ग्राफ़िक फ़ाइल (.odg) का प्रतिनिधित्व करता है, जो Apache OpenOffice के Draw एप्लिकेशन द्वारा ड्रॉइंग तत्वों को वेक्टर इमेज के रूप में संग्रहीत करने के लिए उपयोग होती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/image/odg

### FODG {#FODG}
```
public static final FileType FODG
```


एक Flat XML ODF टेम्प्लेट (.fodg) का प्रतिनिधित्व करता है, जो Apache OpenOffice के Draw एप्लिकेशन द्वारा ड्रॉइंग तत्वों को वेक्टर इमेज के रूप में संग्रहीत करने के लिए उपयोग होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/image/fodg

### SVG {#SVG}
```
public static final FileType SVG
```


एक Scalable Vector Graphics फ़ाइल (.svg) का प्रतिनिधित्व करता है, जो एक स्केलेबल वेक्टर ग्राफ़िक्स फ़ाइल है जो इमेज की उपस्थिति का वर्णन करने के लिए XML-आधारित टेक्स्ट फ़ॉर्मेट का उपयोग करती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


एक Compressed Scalable Vector Graphics फ़ाइल (.svgz) का प्रतिनिधित्व करता है, जो एक स्केलेबल वेक्टर ग्राफ़िक्स फ़ाइल है जो XML-आधारित टेक्स्ट फ़ॉर्मेट, GZIP द्वारा संकुचित, का उपयोग इमेज की उपस्थिति का वर्णन करने के लिए करती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://fileinfo.com/extension/svgz

### OTG {#OTG}
```
public static final FileType OTG
```


एक OpenDocument ग्राफ़िक टेम्प्लेट (.otg) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/image/otg

### HTM {#HTM}
```
public static final FileType HTM
```


एक Hypertext Markup Language फ़ाइल (.htm) का प्रतिनिधित्व करता है, जो ब्राउज़र में प्रदर्शित होने वाले वेब पेजों के लिए एक्सटेंशन है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/web/html

### HTML {#HTML}
```
public static final FileType HTML
```


एक Hypertext Markup Language फ़ाइल (.html) का प्रतिनिधित्व करता है, जो ब्राउज़र में प्रदर्शित होने वाले वेब पेजों के लिए एक्सटेंशन है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


एक MHTML वेब आर्काइव (.mht) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/web/mht

### NSF {#NSF}
```
public static final FileType NSF
```


एक Lotus Notes डेटाबेस (.nsf) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://fileinfo.com/extension/nsf

### MBOX {#MBOX}
```
public static final FileType MBOX
```


एक ईमेल मेलबॉक्स फ़ाइल (.mbox) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://fileinfo.com/extension/mbox

### MHTML {#MHTML}
```
public static final FileType MHTML
```


एक MIME HTML फ़ाइल (.mhtml) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### XML {#XML}
```
public static final FileType XML
```


एक XML फ़ाइल (.xml) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/web/xml

### ONE {#ONE}
```
public static final FileType ONE
```


एक OneNote दस्तावेज़ (.one) का प्रतिनिधित्व करता है जो Microsoft OneNote एप्लिकेशन द्वारा बनाया गया है। OneNote आपको एप्लिकेशन का उपयोग करके जानकारी एकत्र करने देता है जैसे आप नोट्स लेने के लिए अपने ड्राफ्टपैड का उपयोग कर रहे हों। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


एक Portable Document Format फ़ाइल (.pdf) का प्रतिनिधित्व करता है, जो 1990 के दशक में Adobe द्वारा बनाई गई दस्तावेज़ प्रकार है। इस फ़ाइल फ़ॉर्मेट का उद्देश्य दस्तावेज़ों और अन्य संदर्भ सामग्री को एक ऐसे फ़ॉर्मेट में प्रस्तुत करने का मानक पेश करना था जो एप्लिकेशन सॉफ़्टवेयर, हार्डवेयर और ऑपरेटिंग सिस्टम से स्वतंत्र हो। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


XML पेपर स्पेसिफिकेशन फ़ाइल (.xps) का प्रतिनिधित्व करता है, जो माइक्रोसॉफ्ट द्वारा निर्मित XML पेपर स्पेसिफिकेशन्स पर आधारित पृष्ठ लेआउट फ़ाइलों का प्रतिनिधित्व करता है। यह फ़ॉर्मेट माइक्रोसॉफ्ट द्वारा EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और PDF फ़ाइल फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, रूप‑रंग और प्रिंटिंग जानकारी में XML का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### OXPS {#OXPS}
```
public static final FileType OXPS
```


OpenXPS फ़ाइल (.oxps) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/page-description-language/oxps

### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX स्रोत दस्तावेज़ (.tex) का प्रतिनिधित्व करता है, जो एक भाषा है जिसमें प्रोग्रामिंग और मार्क‑अप सुविधाएँ शामिल हैं, जो दस्तावेज़ों को टाइपसेट करने के लिए उपयोग होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint प्रस्तुति (.ppt) का प्रतिनिधित्व करता है, जो स्लाइडों के संग्रह से बनी PowerPoint फ़ाइल को स्लाइडशो के रूप में प्रदर्शित करने के लिए उपयोग होती है। यह Microsoft PowerPoint 97-2003 द्वारा उपयोग किए जाने वाले बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML प्रस्तुति (.pptx) का प्रतिनिधित्व करता है, जो लोकप्रिय Microsoft PowerPoint एप्लिकेशन से बनाई गई प्रस्तुति फ़ाइलें हैं। पूर्व संस्करण PPT, जो बाइनरी था, के विपरीत, PPTX फ़ॉर्मेट Microsoft PowerPoint Open XML प्रस्तुति फ़ाइल फ़ॉर्मेट पर आधारित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint स्लाइड शो (.pps) का प्रतिनिधित्व करता है, जो स्लाइड शो उद्देश्यों के लिए Microsoft PowerPoint का उपयोग करके बनाई जाती हैं। PPS फ़ाइलों को पढ़ना और बनाना Microsoft PowerPoint 97-2003 द्वारा समर्थित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML स्लाइड शो (.ppsx) फ़ाइलों का प्रतिनिधित्व करता है, जो स्लाइड शो उद्देश्यों के लिए Microsoft PowerPoint 2007 और उसके बाद के संस्करणों का उपयोग करके बनाई जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument प्रस्तुति (.odp) का प्रतिनिधित्व करता है, जो OpenOffice.org द्वारा OASISOpen मानक में उपयोग किए जाने वाले प्रस्तुति फ़ाइल फ़ॉर्मेट को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### FODP {#FODP}
```
public static final FileType FODP
```


OpenDocument प्रस्तुति (.fodp) का प्रतिनिधित्व करता है, जो OpenDocument फ्लैट XML प्रस्तुति को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://fileinfo.com/extension/fodp

### POT {#POT}
```
public static final FileType POT
```


PowerPoint टेम्पलेट (.pot) का प्रतिनिधित्व करता है, जो PowerPoint 97-2003 संस्करणों द्वारा बनाई गई Microsoft PowerPoint टेम्पलेट फ़ाइलों को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### PPTM {#PPTM}
```
public static final FileType PPTM
```


PowerPoint Open XML मैक्रो‑सक्षम प्रस्तुति (.pptm) का प्रतिनिधित्व करता है, जो Microsoft PowerPoint 2007 या उससे उच्च संस्करणों से बनाई गई मैक्रो‑सक्षम प्रस्तुति फ़ाइलें हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### POTX {#POTX}
```
public static final FileType POTX
```


PowerPoint Open XML प्रस्तुति टेम्पलेट (.potx) का प्रतिनिधित्व करता है, जो Microsoft PowerPoint 2007 और उसके बाद के संस्करणों से बनाई गई Microsoft PowerPoint टेम्पलेट प्रस्तुतियों को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### POTM {#POTM}
```
public static final FileType POTM
```


PowerPoint Open XML मैक्रो‑सक्षम प्रस्तुति टेम्पलेट (.potm) का प्रतिनिधित्व करता है, जो मैक्रो समर्थन वाली Microsoft PowerPoint टेम्पलेट फ़ाइलें हैं। POTM फ़ाइलें PowerPoint 2007 या उससे ऊपर के संस्करणों से बनाई जाती हैं और डिफ़ॉल्ट सेटिंग्स शामिल करती हैं जिन्हें आगे की प्रस्तुति फ़ाइलें बनाने के लिए उपयोग किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### PPSM {#PPSM}
```
public static final FileType PPSM
```


PowerPoint Open XML मैक्रो‑सक्षम स्लाइड (.ppsm) का प्रतिनिधित्व करता है, जो Microsoft PowerPoint 2007 या उससे उच्च संस्करणों से बनाई गई मैक्रो‑सक्षम स्लाइड शो फ़ाइल फ़ॉर्मेट को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument प्रस्तुति टेम्पलेट (.otp) का प्रतिनिधित्व करता है, जो OASIS OpenDocument मानक फ़ॉर्मेट में अनुप्रयोगों द्वारा बनाई गई प्रस्तुति टेम्पलेट फ़ाइलों को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Excel स्प्रेडशीट (.xls) का प्रतिनिधित्व करता है, जो Excel बाइनरी फ़ाइल फ़ॉर्मेट को दर्शाता है। ऐसी फ़ाइलें Microsoft Excel के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे OpenOffice Calc या Apple Numbers द्वारा भी बनाई जा सकती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Excel 2003 XML (SpreadsheetML) (.xml) का प्रतिनिधित्व करता है, जो Excel बाइनरी फ़ाइल फ़ॉर्मेट को दर्शाता है। ऐसी फ़ाइलें Microsoft Excel के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे OpenOffice Calc या Apple Numbers द्वारा भी बनाई जा सकती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Apple Numbers (.numbers) को दर्शाता है, जो Excel जैसी बाइनरी फ़ाइल फ़ॉर्मेट को दर्शाता है। ऐसी फ़ाइलें Apple Numbers एप्लिकेशन द्वारा बनाई जा सकती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://fileinfo.com/extension/numbers

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Spreadsheet (.xlsx) को दर्शाता है, जो Microsoft Excel दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है जिसे Microsoft ने Microsoft Office 2007 के रिलीज़ के साथ प्रस्तुत किया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Macro-Enabled Spreadsheet (.xlsm) को दर्शाता है, जो मैक्रो को सपोर्ट करने वाला स्प्रेडशीट फ़ाइल प्रकार है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel Binary Spreadsheet (.xlsb) को दर्शाता है, जो Excel बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है। यह रिकॉर्ड और संरचनाओं का संग्रह है जो Excel वर्कबुक सामग्री को निर्दिष्ट करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Comma Separated Values फ़ाइल (.csv) को दर्शाता है, जो कॉमा द्वारा अलग किए गए मानों के साथ डेटा रिकॉर्ड्स वाली प्लेन टेक्स्ट फ़ाइलें होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Tab Separated Values फ़ाइल (.tsv) को दर्शाता है, जो टैब द्वारा अलग किए गए डेटा को प्लेन टेक्स्ट फ़ॉर्मेट में रखती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Spreadsheet (.ods) को दर्शाता है, जो OpenDocument स्प्रेडशीट दस्तावेज़ फ़ॉर्मेट का संक्षिप्त रूप है जिसे उपयोगकर्ता संपादित कर सकता है। डेटा ODF फ़ाइलों में पंक्तियों और स्तंभों में संग्रहीत होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### FODS {#FODS}
```
public static final FileType FODS
```


OpenDocument Flat XML Spreadsheet (.fods) को दर्शाता है। यह XML पर आधारित स्प्रेडशीट दस्तावेज़ फ़ॉर्मेट है जो OpenOffice और LibreOffice द्वारा उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/spreadsheet/fods

### OTS {#OTS}
```
public static final FileType OTS
```


OpenDocument Spreadsheet Template (.ots) को दर्शाता है। यह OpenOffice और LibreOffice द्वारा स्प्रेडशीट के लिए उपयोग किया जाने वाला टेम्पलेट दस्तावेज़ फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ots

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Microsoft Excel Add-in (.xlam) को दर्शाता है। यह Microsoft Excel द्वारा कस्टम कार्यक्षमता वाले ऐड-इन बनाने के लिए उपयोग किया जाने वाला फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://fileinfo.com/extension/xlam

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel Macro-Enabled Template (.xltm) को दर्शाता है, जो Microsoft Excel द्वारा मैक्रो-सक्षम टेम्पलेट फ़ाइलों के रूप में उत्पन्न फ़ाइलें हैं। XLTM फ़ाइलें संरचना में XLTX के समान हैं, सिवाय इसके कि बाद वाला मैक्रो वाले टेम्पलेट फ़ाइलें बनाने का समर्थन नहीं करता। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel Template (.xlt) को दर्शाता है, जो Microsoft Excel द्वारा बनाई गई टेम्पलेट फ़ाइलें हैं, जो Microsoft Office सूट का हिस्सा है। Microsoft Office 97-2003 नई XLT फ़ाइलें बनाने और उन्हें खोलने का समर्थन करता था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML Spreadsheet Template (.xltx) को दर्शाता है, जो Office OpenXML फ़ाइल फ़ॉर्मेट विनिर्देशों पर आधारित Microsoft Excel टेम्पलेट हैं। इसका उपयोग एक मानक टेम्पलेट फ़ाइल बनाने के लिए किया जाता है जिसे समान सेटिंग्स वाले XLSX फ़ाइलें उत्पन्न करने के लिए उपयोग किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### SXC {#SXC}
```
public static final FileType SXC
```


StarOffice Calc Spreadsheet (.sxc) को दर्शाता है। यह StarOffice Calc, एक स्प्रेडशीट प्रोग्राम, द्वारा बनाई गई स्प्रेडशीट दस्तावेज़ है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### MPP {#MPP}
```
public static final FileType MPP
```


Microsoft Project फ़ाइल (.mpp) को दर्शाता है, जो Microsoft Project डेटा फ़ाइल है जो प्रोजेक्ट प्रबंधन से संबंधित जानकारी को एकीकृत रूप में संग्रहीत करती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### MPT {#MPT}
```
public static final FileType MPT
```


Microsoft Project Template (.mpt) को दर्शाता है, जिसमें .MPP फ़ाइलें बनाने के लिए बुनियादी जानकारी, संरचना और दस्तावेज़ सेटिंग्स शामिल हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### MPX {#MPX}
```
public static final FileType MPX
```


Microsoft Project Exchange फ़ाइल (.mpx) को दर्शाता है, जो ASCII फ़ाइल फ़ॉर्मेट है जो Microsoft Project (MSP) और अन्य अनुप्रयोगों जैसे Primavera Project Planner, Sciforma, और Timerline Precision Estimating के बीच प्रोजेक्ट जानकारी स्थानांतरित करने के लिए उपयोग होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### AS {#AS}
```
public static final FileType AS
```


ActionScript फ़ाइल (.as) को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/programming/as

### AS_3 {#AS-3}
```
public static final FileType AS_3
```


ActionScript फ़ाइल (.as3) को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://datatypes.net/open-as3-files

### ASM {#ASM}
```
public static final FileType ASM
```


एक असेंबली भाषा स्रोत कोड फ़ाइल (.asm) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/cad/asm

### BAT {#BAT}
```
public static final FileType BAT
```


एक DOS बैच फ़ाइल (.bat) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/executable/bat

### C {#C}
```
public static final FileType C
```


एक C/C++ स्रोत कोड फ़ाइल (.c) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/programming/c

### CC {#CC}
```
public static final FileType CC
```


एक C++ स्रोत कोड फ़ाइल (.cc) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/programming/cc

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


एक CMake फ़ाइल (.cmake) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/programming/cmake

### CPP {#CPP}
```
public static final FileType CPP
```


एक C++ स्रोत कोड फ़ाइल (.cpp) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/programming/cpp

### CS {#CS}
```
public static final FileType CS
```


एक C\# स्रोत कोड फ़ाइल (.cs) का प्रतिनिधित्व करता है, जो C\# प्रोग्रामिंग भाषा की स्रोत कोड फ़ाइल है। इसे माइक्रोसॉफ्ट ने .NET फ्रेमवर्क के साथ उपयोग के लिए प्रस्तुत किया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/programming/cs

### VB {#VB}
```
public static final FileType VB
```


एक Visual Basic प्रोजेक्ट आइटम फ़ाइल (.vb) का प्रतिनिधित्व करता है, जो Visual Basic भाषा में बनाई गई स्रोत कोड फ़ाइल है। इसे माइक्रोसॉफ्ट ने .NET एप्लिकेशन के विकास के लिए बनाया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/programming/vb

### CSS {#CSS}
```
public static final FileType CSS
```


एक Cascading Style Sheet (.css) फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/web/css

### CXX {#CXX}
```
public static final FileType CXX
```


एक C++ स्रोत कोड फ़ाइल (.cxx) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/programming/cxx

### DIFF {#DIFF}
```
public static final FileType DIFF
```


एक पैच फ़ाइल (.diff) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/programming/diff

### ERB {#ERB}
```
public static final FileType ERB
```


एक Ruby ERB स्क्रिप्ट (.erb) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/programming/erb

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


एक Groovy स्रोत कोड फ़ाइल (.groovy) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/programming/groovy

### H {#H}
```
public static final FileType H
```


एक C/C++/Objective-C हेडर फ़ाइल (.h) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/programming/h

### HAML {#HAML}
```
public static final FileType HAML
```


एक Haml स्रोत कोड फ़ाइल (.haml) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/programming/haml

### HH {#HH}
```
public static final FileType HH
```


एक C++ हेडर फ़ाइल (.hh) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/programming/hh

### JAVA {#JAVA}
```
public static final FileType JAVA
```


एक Java स्रोत कोड फ़ाइल (.java) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/programming/java

### JS {#JS}
```
public static final FileType JS
```


एक JavaScript फ़ाइल (.js) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/web/js

### JSON {#JSON}
```
public static final FileType JSON
```


एक JavaScript Object Notation फ़ाइल (.json) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/web/json

### LESS {#LESS}
```
public static final FileType LESS
```


एक LESS स्टाइल शीट (.less) फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/web/less

### LOG {#LOG}
```
public static final FileType LOG
```


एक लॉग फ़ाइल (.log) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/database/log

### M {#M}
```
public static final FileType M
```


एक Objective-C इम्प्लीमेंटेशन फ़ाइल (.m) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://fileinfo.com/extension/m

### MAKE {#MAKE}
```
public static final FileType MAKE
```


एक Xcode Makefile स्क्रिप्ट (.make) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/programming/make

### MD {#MD}
```
public static final FileType MD
```


एक Markdown दस्तावेज़ फ़ाइल (.md) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://docs.fileformat.com/word-processing/md

### ML {#ML}
```
public static final FileType ML
```


एक ML स्रोत कोड फ़ाइल (.ml) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here][].


[here]: https://wiki.fileformat.com/programming/ml

### MM {#MM}
```
public static final FileType MM
```


एक Objective-C++ स्रोत फ़ाइल (.mm) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/programming/mm

### PHP {#PHP}
```
public static final FileType PHP
```


एक PHP स्रोत कोड फ़ाइल (.php) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/programming/php

### PL {#PL}
```
public static final FileType PL
```


एक Perl स्क्रिप्ट (.pl) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/programming/pl

### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


एक Java प्रॉपर्टीज़ फ़ाइल (.properties) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://fileinfo.com/extension/properties

### PY {#PY}
```
public static final FileType PY
```


एक Python स्क्रिप्ट (.py) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/programming/py

### RB {#RB}
```
public static final FileType RB
```


एक Ruby स्रोत कोड (.rb) फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/programming/rb

### RST {#RST}
```
public static final FileType RST
```


एक reStructuredText फ़ाइल (.rst) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/programming/rst

### SASS {#SASS}
```
public static final FileType SASS
```


एक Syntactically Awesome StyleSheets फ़ाइल (.sass) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/web/sass

### SCALA {#SCALA}
```
public static final FileType SCALA
```


एक Scala स्रोत कोड फ़ाइल (.scala) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/programming/scala

### SCM {#SCM}
```
public static final FileType SCM
```


एक Scheme स्रोत कोड फ़ाइल (.scm) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/programming/scm

### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


एक Generic स्क्रिप्ट फ़ाइल (.script) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/programming/script

### SH {#SH}
```
public static final FileType SH
```


एक Bash शेल स्क्रिप्ट (.sh) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/cs/programming/sh

### SML {#SML}
```
public static final FileType SML
```


एक Standard ML स्रोत कोड फ़ाइल (.sml) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://fileinfo.com/extension/sml

### SQL {#SQL}
```
public static final FileType SQL
```


एक Structured Query Language डेटा फ़ाइल (.sql) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/database/sql

### VIM {#VIM}
```
public static final FileType VIM
```


एक Vim सेटिंग्स फ़ाइल (.vim) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://fileinfo.com/extension/vim

### YAML {#YAML}
```
public static final FileType YAML
```


एक YAML दस्तावेज़ (.yaml) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/programming/yaml

### DOC {#DOC}
```
public static final FileType DOC
```


एक Microsoft Word दस्तावेज़ (.doc) फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


एक Microsoft Word Open XML दस्तावेज़ (.docx) फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/word-processing/docx

### CHM {#CHM}
```
public static final FileType CHM
```


एक Microsoft Compiled HTML Help फ़ाइल (.chm) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://docs.fileformat.com/web/chm

### DOCM {#DOCM}
```
public static final FileType DOCM
```


एक Word Open XML मैक्रो-सक्षम दस्तावेज़ (.docm) फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


एक Word दस्तावेज़ टेम्पलेट (.dot) फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


एक Word Open XML दस्तावेज़ टेम्पलेट (.dotx) फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


एक Word Open XML मैक्रो-सक्षम दस्तावेज़ टेम्पलेट (.dotm) फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


एक Rich Text Format फ़ाइल (.rtf) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


एक Plain Text फ़ाइल (.txt) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here][].


[here]: https://wiki.fileformat.com/word-processing/txt

### ODT {#ODT}
```
public static final FileType ODT
```


एक OpenDocument टेक्स्ट दस्तावेज़ (.odt) का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


एक OpenDocument दस्तावेज़ टेम्प्लेट (.ott) का प्रतिनिधित्व करता है। यह OASIS के OpenDocument मानक फ़ॉर्मेट के अनुरूप उत्पन्न किया गया टेम्प्लेट दस्तावेज़ है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/word-processing/ott

### VCF {#VCF}
```
public static final FileType VCF
```


एक vCard फ़ाइल (.vcf) का प्रतिनिधित्व करता है, जो संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल फ़ॉर्मेट है। यह लोकप्रिय सूचना विनिमय अनुप्रयोगों के बीच डेटा आदान‑प्रदान के लिए व्यापक रूप से उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://wiki.fileformat.com/email/vcf

### AI {#AI}
```
public static final FileType AI
```


एक Adobe Illustrator फ़ाइल (.ai) का प्रतिनिधित्व करता है, जो Adobe Illustrator ड्रॉइंग्स के लिए फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://docs.fileformat.com/image/ai

### PSM1 {#PSM1}
```
public static final FileType PSM1
```


एक PowerShell स्क्रिप्ट मॉड्यूल फ़ाइल (.psm1) का प्रतिनिधित्व करता है। यह PowerShell मॉड्यूल स्क्रिप्ट्स के लिए फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://fileinfo.com/extension/psm1

### PS1 {#PS1}
```
public static final FileType PS1
```


एक PowerShell स्क्रिप्ट फ़ाइल (.ps1) का प्रतिनिधित्व करता है। यह Windows PowerShell Cmdlet फ़ाइलों के लिए फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://fileinfo.com/extension/ps1

### PSD1 {#PSD1}
```
public static final FileType PSD1
```


एक PowerShell स्क्रिप्ट मॉड्यूल मैनिफेस्ट फ़ाइल (.psd1) का प्रतिनिधित्व करता है। यह PowerShell मॉड्यूल मैनिफेस्ट स्क्रिप्ट्स के लिए फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ][].


[here]: https://fileinfo.com/extension/psd1

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


फ़ाइल एक्सटेंशन को फ़ाइल प्रकार से मैप करता है।

यह मेथड फ़ाइल एक्सटेंशन लेता है, चाहे वह बिंदु "." के साथ हो या बिना, और यदि समर्थित हो तो संबंधित फ़ाइल प्रकार लौटाता है। यदि फ़ाइल प्रकार समर्थित नहीं है, तो यह डिफ़ॉल्ट [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) फ़ाइल प्रकार लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| extension | java.lang.String | फ़ाइल एक्सटेंशन बिंदु "." के साथ या बिना। |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


फ़ाइल नाम या फ़ाइल पथ से फ़ाइल एक्सटेंशन निकालता है और उसे फ़ाइल प्रकार से मैप करता है।

यदि फ़ाइल प्रकार समर्थित है, तो मेथड संबंधित FileType लौटाता है, अन्यथा यह डिफ़ॉल्ट [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) फ़ाइल प्रकार लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल पथ | java.lang.String | फ़ाइल नाम या फ़ाइल पथ। |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


फ़ाइल मीडिया प्रकार को फ़ाइल प्रकार में मैप करता है। उदाहरण के लिए, 'application/pdf' को [PDF](../../com.groupdocs.viewer/filetype\#PDF) में मैप किया जाएगा।

यह मेथड फ़ाइल मीडिया प्रकार को इनपुट के रूप में लेता है और इसे संबंधित FileType में मैप करता है। यदि मीडिया प्रकार समर्थित है, तो मेथड संबंधित फ़ाइल प्रकार लौटाता है। यदि मीडिया प्रकार समर्थित नहीं है, तो यह डिफ़ॉल्ट [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) फ़ाइल प्रकार लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mediaType | java.lang.String | फ़ाइल मीडिया प्रकार, उदाहरण के लिए, 'application/pdf'। |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।

यह मेथड फ़ाइल का प्रतिनिधित्व करने वाले इनपुट स्ट्रीम को लेता है और फ़ाइल सिग्नेचर का विश्लेषण करके उसके फ़ाइल प्रकार का पता लगाने का प्रयास करता है। फ़ाइल सिग्नेचर फ़ाइल की शुरुआत में बाइट्स की एक अनूठी श्रृंखला है जो उसके फ़ाइल प्रकार को दर्शाती है। मेथड इनपुट स्ट्रीम से फ़ाइल सिग्नेचर पढ़ता है और इसे समर्थित फ़ाइल प्रकारों के ज्ञात फ़ाइल सिग्नेचर से मिलाता है। यदि मिलान मिलता है, तो मेथड संबंधित फ़ाइल प्रकार लौटाता है। यदि कोई मिलान नहीं मिलता, तो यह डिफ़ॉल्ट [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) फ़ाइल प्रकार लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | फ़ाइल का प्रतिनिधित्व करने वाला इनपुट स्ट्रीम। |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।

यह मेथड फ़ाइल सिग्नेचर का विश्लेषण करता है, जो फ़ाइल की शुरुआत में बाइट्स की एक अनूठी श्रृंखला है, ताकि फ़ाइल प्रकार निर्धारित किया जा सके। यह प्रदान किए गए इनपुट स्ट्रीम से फ़ाइल सिग्नेचर पढ़ता है और इसे समर्थित फ़ाइल प्रकारों के ज्ञात फ़ाइल सिग्नेचर से मिलाता है। यदि मिलान मिलता है, तो मेथड संबंधित फ़ाइल प्रकार लौटाता है। यदि कोई मिलान नहीं मिलता, तो यह डिफ़ॉल्ट [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) फ़ाइल प्रकार लौटाता है।

यदि फ़ाइल एन्क्रिप्टेड है और खोलने के लिए पासवर्ड की आवश्यकता है, तो पासवर्ड इस मेथड के पैरामीटर के रूप में प्रदान किया जाना चाहिए। पासवर्ड का उपयोग फ़ाइल को डिक्रिप्ट करने और उसके सिग्नेचर का विश्लेषण करके फ़ाइल प्रकार निर्धारित करने के लिए किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | फ़ाइल का प्रतिनिधित्व करने वाला इनपुट स्ट्रीम। |
| password | java.lang.String | फ़ाइल खोलने के लिए पासवर्ड। |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।

यह मेथड फ़ाइल सिग्नेचर का विश्लेषण करता है, जो फ़ाइल की शुरुआत में बाइट्स की एक अनूठी श्रृंखला है, ताकि फ़ाइल प्रकार निर्धारित किया जा सके। यह प्रदान किए गए इनपुट स्ट्रीम से फ़ाइल सिग्नेचर पढ़ता है और इसे समर्थित फ़ाइल प्रकारों के ज्ञात फ़ाइल सिग्नेचर से मिलाता है। यदि मिलान मिलता है, तो मेथड संबंधित फ़ाइल प्रकार लौटाता है। यदि कोई मिलान नहीं मिलता, तो यह डिफ़ॉल्ट [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) फ़ाइल प्रकार लौटाता है।

फ़ाइल प्रकार पहचान प्रक्रिया के दौरान किसी भी प्रासंगिक जानकारी या त्रुटियों को लॉग करने के लिए एक लॉगर प्रदान किया जा सकता है। लॉगर को ILogger इंटरफ़ेस को लागू करना चाहिए। यदि कोई लॉगर प्रदान नहीं किया जाता है, तो पहचान प्रक्रिया कोई लॉग आउटपुट उत्पन्न नहीं करेगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | फ़ाइल का प्रतिनिधित्व करने वाला इनपुट स्ट्रीम। |
| लॉगर | com.groupdocs.foundation.logging.ILogger | सूचना या त्रुटियों को लॉग करने के लिए लॉगर। |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।

यह मेथड फ़ाइल सिग्नेचर का विश्लेषण करता है, जो फ़ाइल की शुरुआत में बाइट्स की एक अनूठी श्रृंखला है, ताकि फ़ाइल प्रकार निर्धारित किया जा सके। यह प्रदान किए गए इनपुट स्ट्रीम से फ़ाइल सिग्नेचर पढ़ता है और इसे समर्थित फ़ाइल प्रकारों के ज्ञात फ़ाइल सिग्नेचर से मिलाता है। यदि मिलान मिलता है, तो मेथड संबंधित फ़ाइल प्रकार लौटाता है। यदि कोई मिलान नहीं मिलता, तो यह डिफ़ॉल्ट [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) फ़ाइल प्रकार लौटाता है।

यदि फ़ाइल एन्क्रिप्टेड या संरक्षित है तो पासवर्ड प्रदान किया जा सकता है। पासवर्ड फ़ाइल को खोलने के लिए उपयोग किया जाएगा, फ़ाइल हस्ताक्षर का विश्लेषण करने से पहले। यदि फ़ाइल को पासवर्ड की आवश्यकता नहीं है, तो इस पैरामीटर को null सेट किया जा सकता है।

फ़ाइल प्रकार पहचान प्रक्रिया के दौरान किसी भी प्रासंगिक जानकारी या त्रुटियों को लॉग करने के लिए एक लॉगर प्रदान किया जा सकता है। लॉगर को ILogger इंटरफ़ेस को लागू करना चाहिए। यदि कोई लॉगर प्रदान नहीं किया जाता है, तो पहचान प्रक्रिया कोई लॉग आउटपुट उत्पन्न नहीं करेगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | फ़ाइल का प्रतिनिधित्व करने वाला इनपुट स्ट्रीम। |
| password | java.lang.String | फ़ाइल खोलने के लिए पासवर्ड। |
| लॉगर | com.groupdocs.foundation.logging.ILogger | सूचना या त्रुटियों को लॉग करने के लिए लॉगर। |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


समर्थित फ़ाइल प्रकारों को पुनः प्राप्त करता है।

यह मेथड सिस्टम द्वारा समर्थित सभी फ़ाइल प्रकारों की एक श्रृंखला लौटाता है। फ़ाइल प्रकार विभिन्न दस्तावेज़ फ़ॉर्मेट को दर्शाते हैं जिन्हें सिस्टम द्वारा प्रोसेस या पहचाना जा सकता है।

 **Learn more**

 *  Learn more about the supported document formats: [Full list of supported file formats][]


[Full list of supported file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/

**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - समर्थित फ़ाइल प्रकारों की एक श्रृंखला।
### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


पथ द्वारा टेक्स्ट [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) और [CSV](../../com.groupdocs.viewer/filetype\#CSV) फ़ाइलों की कैरेक्टर सेट का पता लगाने का प्रयास करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल पथ | java.lang.String | फ़ाइल नाम या फ़ाइल पथ। |

**Returns:**
java.nio.charset.Charset - फ़ाइल कैरेक्टर सेट का पता न चलने पर Charset या null।

**Example:**

```
Charset charset = FileType.detectCharset("message.txt");
```
### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


स्ट्रीम द्वारा टेक्स्ट [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) और [CSV](../../com.groupdocs.viewer/filetype\#CSV) फ़ाइल की कैरेक्टर सेट का पता लगाने का प्रयास करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | फ़ाइल स्ट्रीम। |

**Returns:**
java.nio.charset.Charset - फ़ाइल कैरेक्टर सेट का पता न चलने पर Charset या null।

**Example:**

```
InputStream stream = new FileInputStream("message.txt");
 Charset charset = FileType.detectCharset(stream);
```
### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


फ़ाइल फ़ॉर्मेट का नाम प्राप्त करता है, उदाहरण के लिए "Microsoft Word Document"।

**Returns:**
java.lang.String - फ़ाइल फ़ॉर्मेट का नाम।
### getExtension() {#getExtension--}
```
public final String getExtension()
```


फ़ाइल एक्सटेंशन उपसर्ग (बिंदु "." सहित) प्राप्त करता है, उदाहरण के लिए ".doc"।

**Returns:**
java.lang.String - फ़ाइल एक्सटेंशन उपसर्ग।
### toString() {#toString--}
```
public String toString()
```


वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व।
