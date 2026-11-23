---
title: "FileType वर्ग"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक फ़ाइल प्रकार का प्रतिनिधित्व करता है और GroupDocs.Viewer द्वारा समर्थित सभी फ़ाइल प्रकारों की सूची प्राप्त करने के लिए मेथड्स प्रदान करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

एक फ़ाइल प्रकार का प्रतिनिधित्व करता है और GroupDocs.Viewer द्वारा समर्थित सभी फ़ाइल प्रकारों की सूची प्राप्त करने के लिए मेथड्स प्रदान करता है।

यह FileType प्रकार निम्नलिखित सदस्यों को प्रदर्शित करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | एक नया उदाहरण प्रारंभ करता है [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) का। |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | एक नया FileType उदाहरण प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | पथ द्वारा टेक्स्ट TXT, TSV, और CSV फ़ाइलों की एन्कोडिंग का पता लगाता है। |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | स्ट्रीम से टेक्स्ट फ़ाइलों (TXT, TSV, CSV) की एन्कोडिंग का पता लगाने का प्रयास करता है। |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | निर्धारित करता है कि वर्तमान [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) निर्दिष्ट [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) के समान है या नहीं। |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | निर्धारित करता है कि वर्तमान [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) निर्दिष्ट ऑब्जेक्ट के समान है या नहीं। |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | फ़ाइल एक्सटेंशन को फ़ाइल प्रकार से मैप करता है। |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | फ़ाइल एक्सटेंशन निकालता है और उसे फ़ाइल प्रकार से मैप करता है। |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | फ़ाइल मीडिया प्रकार को एक [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) से मैप करता है (उदाहरण के लिए, 'application/pdf' को [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/) से मैप किया जाता है)। |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है। |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है। |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है। |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है। |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | वर्तमान [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | समर्थित फ़ाइल प्रकारों को पुनः प्राप्त करता है। |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | वर्तमान ऑब्जेक्ट को दर्शाने वाली स्ट्रिंग लौटाता है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | फ़ाइलनाम प्रत्यय (जिसमें अवधि "." शामिल है) जैसे ".doc"। |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | फ़ाइल प्रकार का नाम जैसे "Microsoft Word Document"। |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | अज्ञात फ़ाइल प्रकार को दर्शाता है। |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | ज़िप्ड फ़ाइल (.zip) उन अभिलेखों को दर्शाती है जो एक या अधिक फ़ाइलों या निर्देशिकाओं को रख सकते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | कंसॉलिडेटेड यूनिक्स फ़ाइल आर्काइव (.tar) ऐसे अभिलेख हैं जो एक या अधिक फ़ाइलों को एकत्र करने के लिए यूनिक्स-आधारित यूटिलिटी से बनाए जाते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | XZ फ़ाइल (.xz) एक अभिलेख है जो LZMA एल्गोरिद्म पर आधारित उच्च अनुपात संपीड़न एल्गोरिद्म से संकुचित है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | कंसॉलिडेटेड यूनिक्स फ़ाइल आर्काइव (.txz, .tar.xz) ऐसे अभिलेख हैं जो एक या अधिक फ़ाइलों को एकत्र करने के लिए यूनिक्स-आधारित यूटिलिटी से बनाए जाते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | कंसॉलिडेटेड यूनिक्स फ़ाइल आर्काइव (.txz, .tar.xz) ऐसे अभिलेख हैं जो एक या अधिक फ़ाइलों को एकत्र करने के लिए यूनिक्स-आधारित यूटिलिटी से बनाए जाते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | कंसॉलिडेटेड यूनिक्स फ़ाइल आर्काइव (.tgz, .tar.gz) ऐसे अभिलेख हैं जो एक या अधिक फ़ाइलों को एकत्र करने के लिए यूनिक्स-आधारित यूटिलिटी से बनाए जाते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | कंसॉलिडेटेड यूनिक्स फ़ाइल आर्काइव (.tgz, .tar.gz) ऐसे अभिलेख हैं जो एक या अधिक फ़ाइलों को एकत्र करने के लिए यूनिक्स-आधारित यूटिलिटी से बनाए जाते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Bzip2 संपीड़ित फ़ाइल (.bz2) ऐसी संपीड़ित फ़ाइलें हैं जो BZIP2 ओपन सोर्स संपीड़न विधि का उपयोग करके उत्पन्न होती हैं, मुख्यतः UNIX या Linux सिस्टम पर। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar) संपीड़ित फ़ाइलें हैं जो RAR (WINRAR) संपीड़न विधि का उपयोग करके उत्पन्न की जाती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz) संपीड़ित फ़ाइलें हैं जो gzip संपीड़न एप्लिकेशन से बनाई गई हैं। यह कई संपीड़ित फ़ाइलें रख सकता है और UNIX तथा Linux प्रणालियों पर सामान्यतः उपयोग किया जाता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip) को Unix प्रणालियों में उपयोग किए जाने वाले Compress प्रोग्राम को बदलने के लिए एक मुफ्त उपयोगिता के रूप में प्रस्तुत किया गया था। ऐसी फ़ाइलें कई अनुप्रयोगों जैसे WinZip के साथ खोली और निकाली जा सकती हैं, जो Windows और MacOS दोनों पर उपलब्ध है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip) एक मुफ्त ओपन सोर्स आर्काइवर है जिसमें LZMA और LZMA2 संपीड़न होता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio एक सामान्य फ़ाइल आर्काइवर उपयोगिता और इसका संबंधित फ़ाइल स्वरूप है। यह मुख्यतः Unix-समतुल्य कंप्यूटर ऑपरेटिंग सिस्टम पर स्थापित होता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | ZST फ़ाइल एक संपीड़ित फ़ाइल है जो Zstandard (zstd) संपीड़न एल्गोरिद्म से उत्पन्न होती है। यह एल्गोरिद्म द्वारा लॉसलेस संपीड़न के साथ बनाई गई फ़ाइल है। ZST फ़ाइलों का उपयोग विभिन्न प्रकार की फ़ाइलों जैसे डेटाबेस, फ़ाइल सिस्टम, नेटवर्क और गेम्स को संपीड़ित करने के लिए किया जा सकता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | TZST फ़ाइलें (.tar.zst, .tzst) Zstandard आर्काइव (ZST) हैं, जो आंतरिक रूप से एक एकीकृत Unix फ़ाइल आर्काइव (Tar) को समाहित करती हैं, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए Unix-आधारित उपयोगिता से बनाई गई है। |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | TZST फ़ाइलें (.tar.zst, .tzst) Zstandard आर्काइव (ZST) हैं, जो आंतरिक रूप से एक एकीकृत Unix फ़ाइल आर्काइव (Tar) को समाहित करती हैं, जो एक या अधिक फ़ाइलों को एकत्र करने के लिए Unix-आधारित उपयोगिता से बनाई गई है। |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | ISO ऑप्टिकल डिस्क इमेज एक अनकम्प्रेस्ड आर्काइव डिस्क इमेज फ़ाइल है जो CD या DVD जैसे ऑप्टिकल डिस्क पर संपूर्ण डेटा की सामग्री को ISO-9660 मानक के आधार पर दर्शाती है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA या LZH एक फ्रीवेयर संपीड़न उपयोगिता और संबंधित फ़ाइल स्वरूप है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet (या CAB) Microsoft Windows के लिए एक आर्काइव-फ़ाइल स्वरूप है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Drawing Exchange Format File (.dxf) AutoCAD ड्राइंग फ़ाइल का टैग्ड डेटा प्रतिनिधित्व है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | AutoCAD Drawing Database File (.dwg) स्वामित्व वाले बाइनरी फ़ाइलों को दर्शाता है जो 2D और 3D डिज़ाइन डेटा को रखने के लिए उपयोग होती हैं। DXF की तरह, जो ASCII फ़ाइलें हैं, DWG CAD (Computer Aided Design) ड्रॉइंग्स के लिए बाइनरी फ़ाइल स्वरूप का प्रतिनिधित्व करता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | AutoCAD Drawing Template (.dwt) एक AutoCAD ड्राइंग टेम्पलेट फ़ाइल है जिसका उपयोग ड्रॉइंग्स बनाने के प्रारंभिक बिंदु के रूप में किया जाता है, जिन्हें DWG फ़ाइलों के रूप में सहेजा जा सकता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Stereolithography File (.stl) एक अदलाबदल योग्य फ़ाइल स्वरूप है जो त्रि-आयामी सतह ज्यामिति को दर्शाता है। यह फ़ाइल स्वरूप तेज़ प्रोटोटाइपिंग, 3D प्रिंटिंग और कंप्यूटर-एडेड मैन्युफैक्चरिंग जैसे कई क्षेत्रों में उपयोग पाया जाता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Industry Foundation Classes File (.ifc) एक फ़ाइल स्वरूप है जो भवन वस्तुओं और उनकी विशेषताओं को आयात और निर्यात करने के लिए अंतरराष्ट्रीय मानक स्थापित करता है। यह फ़ाइल स्वरूप विभिन्न सॉफ़्टवेयर अनुप्रयोगों के बीच अंतःक्रियाशीलता प्रदान करता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Design Web Format File (.dwf) 2D/3D ड्रॉइंग को संपीड़ित स्वरूप में दर्शाता है ताकि डिज़ाइन फ़ाइलों को देखा, समीक्षा किया या प्रिंट किया जा सके। इसमें डिज़ाइन डेटा के हिस्से के रूप में ग्राफ़िक्स और पाठ शामिल होते हैं और संपीड़ित स्वरूप के कारण फ़ाइल का आकार घट जाता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Autodesk FBX Interchange File (FilmBoX) (.fbx) 3D मॉडल स्वरूप को दर्शाता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Design Web Format File XPS (.dwfx) 2D/3D ड्रॉइंग को XPS दस्तावेज़ के रूप में संपीड़ित स्वरूप में दर्शाता है ताकि डिज़ाइन फ़ाइलों को देखा, समीक्षा किया या प्रिंट किया सके। इसमें डिज़ाइन डेटा के हिस्से के रूप में ग्राफ़िक्स और पाठ शामिल होते हैं और संपीड़ित स्वरूप के कारण फ़ाइल का आकार घट जाता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | MicroStation Design File (.dgn) उन ड्रॉइंग्स को दर्शाता है जो MicroStation और Intergraph Interactive Graphics Design System जैसे CAD अनुप्रयोगों द्वारा निर्मित और समर्थित हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें यहाँ। |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt) एक वेक्टर-आधारित प्लॉटर फ़ाइल है जिसे Autodesk, Inc. ने प्रस्तुत किया है और यह एक विशिष्ट CAD फ़ाइल की जानकारी रखती है। प्लॉटिंग विवरण उत्पादन में सटीकता और शुद्धता की आवश्यकता रखते हैं, और PLT फ़ाइल का उपयोग यह सुनिश्चित करता है क्योंकि सभी छवियां बिंदुओं के बजाय रेखाओं से मुद्रित की जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | सामान्य फ़ाइल फ़ॉर्मेट फ़ाइल इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj) एक 3D इमेज फ़ाइल है जिसे Wavefront Technologies ने प्रस्तुत किया है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd) Microsoft Visio एप्लिकेशन द्वारा बनाई गई ड्रॉइंग्स हैं जो विभिन्न ग्राफ़िकल ऑब्जेक्ट्स और उनके बीच के कनेक्शन को दर्शाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx) Microsoft Visio फ़ाइल फ़ॉर्मेट को दर्शाता है जो Microsoft Office 2013 से प्रस्तुत किया गया है। इसे बाइनरी फ़ाइल फ़ॉर्मेट .VSD को बदलने के लिए विकसित किया गया था, जो Microsoft Visio के पहले संस्करणों द्वारा समर्थित था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File(.vss) Microsoft Visio 2007 और उससे पहले के संस्करणों द्वारा बनाई गई स्टेंसिल फ़ाइलें हैं। स्टेंसिल फ़ाइलें ड्रॉइंग ऑब्जेक्ट्स प्रदान करती हैं जिन्हें .VSD Visio ड्रॉइंग में शामिल किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx) Microsoft Visio 2013 और उसके बाद के संस्करणों द्वारा बनाई गई ड्रॉइंग स्टेंसिल हैं। VSSX फ़ाइल फ़ॉर्मेट को Visio 2013 और उसके बाद के संस्करणों में खोला जा सकता है। Visio फ़ाइलें विभिन्न ड्रॉइंग तत्वों जैसे आकारों का संग्रह, कनेक्टर, फ्लोचार्ट, नेटवर्क लेआउट, UML डायग्राम आदि के प्रतिनिधित्व के लिए जानी जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm) Microsoft Visio एप्लिकेशन द्वारा बनाई गई ड्रॉइंग फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। VSDM फ़ाइलें OPC/XML ड्रॉइंग हैं जो VSDX के समान हैं, लेकिन फ़ाइल खोलने पर मैक्रो चलाने की क्षमता भी प्रदान करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst) Microsoft Visio द्वारा बनाई गई वेक्टर इमेज फ़ाइलें हैं और आगे की फ़ाइलें बनाने के लिए टेम्पलेट के रूप में कार्य करती हैं। ये टेम्पलेट फ़ाइलें बाइनरी फ़ाइल फ़ॉर्मेट में हैं और डिफ़ॉल्ट लेआउट और सेटिंग्स रखती हैं जो नई Visio ड्रॉइंग्स बनाने में उपयोग होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx) Microsoft Visio 2013 और उसके बाद के संस्करणों द्वारा बनाई गई ड्रॉइंग टेम्पलेट फ़ाइलें हैं। ये VSTX फ़ाइलें Visio ड्रॉइंग्स बनाने के लिए प्रारंभिक बिंदु प्रदान करती हैं, जो .VSDX फ़ाइलों के रूप में सहेजी जाती हैं, और डिफ़ॉल्ट लेआउट और सेटिंग्स रखती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm) Microsoft Visio द्वारा बनाई गई टेम्पलेट फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। VSDX फ़ाइलों के विपरीत, VSTM टेम्पलेट से बनाई गई फ़ाइलें Visual Basic for Applications (VBA) कोड में विकसित मैक्रो चलाने में सक्षम होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm) Microsoft Visio स्टेंसिल फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। जब VSSM फ़ाइल खोली जाती है तो यह मैक्रो चलाकर आरेख में आकारों के वांछित फ़ॉर्मेटिंग और प्लेसमेंट को प्राप्त करने की अनुमति देती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx) उन स्टेंसिल्स को दर्शाता है जिनमें ड्रॉइंग्स और आकार होते हैं जो Microsoft Visio में आरेख बनाने के लिए उपयोग होते हैं। VSX फ़ाइलें XML फ़ाइल फ़ॉर्मेट में सहेजी जाती हैं और Visio 2013 तक समर्थित थीं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx) एक Microsoft Visio ड्रॉइंग टेम्पलेट है जो XML फ़ाइल फ़ॉर्मेट में डिस्क पर सहेजा जाता है। यह टेम्पलेट मूल सेटिंग्स वाली फ़ाइल प्रदान करने के लिए बनाया गया है जिसे समान सेटिंग्स वाली कई Visio फ़ाइलें बनाने में उपयोग किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw) एक फ़ाइल फ़ॉर्मेट को दर्शाता है जो वेब ड्रॉइंग को रेंडर करने के लिए आवश्यक स्ट्रीम और स्टोरेज को निर्दिष्ट करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx) Microsoft Visio में बनाई गई किसी भी ड्रॉइंग या चार्ट को दर्शाता है, लेकिन XML फ़ॉर्मेट में सहेजी गई फ़ाइलों का .VDX एक्सटेंशन होता है। Visio ड्रॉइंग XML फ़ाइल Visio सॉफ़्टवेयर में बनाई जाती है, जिसे Microsoft ने विकसित किया है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें। |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Open eBook File (.epub) एक ई-बुक फ़ाइल फ़ॉर्मेट है जो प्रकाशकों और उपभोक्ताओं के लिए एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। यह फ़ॉर्मेट अब इतना सामान्य हो गया है कि यह कई ई-रीडर्स और सॉफ़्टवेयर अनुप्रयोगों द्वारा समर्थित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Mobipocket eBook (.mobi) सबसे अधिक उपयोग किए जाने वाले ईबुक फ़ाइल फ़ॉर्मेट में से एक है। यह फ़ॉर्मेट पुराने OEB (Open Ebook Format) फ़ॉर्मेट का उन्नयन है और Mobipocket Reader के लिए स्वामित्व फ़ॉर्मेट के रूप में उपयोग किया जाता था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | Amazon Kindle Format 8 (KF8) ईबुक Amazon Kindle उपकरणों के लिए विकसित डिजिटल फ़ाइल फ़ॉर्मेट है। यह फ़ॉर्मेट पुराने AZW फ़ाइलों का उन्नयन है और केवल Kindle Fire उपकरणों पर उपयोग किया जाता है, साथ ही पूर्ववर्ती फ़ॉर्मेट जैसे MOBI और AZW के साथ पीछे की संगतता रखता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Outlook Mail Message (.msg) Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, नियुक्ति या अन्य कार्यों को संग्रहीत करने के लिए उपयोग किया जाने वाला फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | E-Mail Message (.eml) Outlook और अन्य संबंधित अनुप्रयोगों का उपयोग करके सहेजे गए ईमेल संदेशों को दर्शाता है। लगभग सभी ईमेल क्लाइंट इस फ़ाइल फ़ॉर्मेट को RFC-822 इंटरनेट संदेश फ़ॉर्मेट मानक के अनुपालन के कारण समर्थन करते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Lotus Notes Database (.nsf) इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Email Mailbox File (.mbox) इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Apple Mail Message (.emlx) Apple द्वारा लागू और विकसित किया गया है। Apple Mail एप्लिकेशन ईमेल निर्यात करने के लिए EMLX फ़ाइल फ़ॉर्मेट का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Outlook Personal Information Store File (.pst) Outlook Personal Storage Files (जिसे Personal Storage Table भी कहा जाता है) को दर्शाता है जो विभिन्न उपयोगकर्ता जानकारी संग्रहीत करते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Outlook Offline Data File (.ost) Microsoft Outlook का उपयोग करके Exchange Server के साथ पंजीकरण के बाद स्थानीय मशीन पर ऑफ़लाइन मोड में उपयोगकर्ता के मेलबॉक्स डेटा को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Tagged Image File (.tif) रास्टर छवियों को दर्शाता है जो इस फ़ाइल फ़ॉर्मेट मानक के अनुरूप विभिन्न उपकरणों पर उपयोग के लिए बनाई गई हैं। यह कई रंग स्थानों में द्वि-स्तरीय, ग्रेस्केल, पैलेट-रंग और पूर्ण-रंग छवि डेटा का वर्णन करने में सक्षम है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Tagged Image File Format (.tiff) रास्टर छवियों को दर्शाता है जो इस फ़ाइल फ़ॉर्मेट मानक के अनुरूप विभिन्न उपकरणों पर उपयोग के लिए बनाई गई हैं। यह कई रंग स्थानों में द्वि-स्तरीय, ग्रेस्केल, पैलेट-रंग और पूर्ण-रंग छवि डेटा का वर्णन करने में सक्षम है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | JPEG Image (.jpg) एक प्रकार का इमेज फ़ॉर्मेट है जिसे लॉसी संपीड़न विधि से सहेजा जाता है। संपीड़न के परिणामस्वरूप उत्पन्न छवि संग्रहण आकार और छवि गुणवत्ता के बीच संतुलन बनाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | JPEG Image (.jpeg) एक प्रकार का इमेज फ़ॉर्मेट है जिसे लॉसी संपीड़न विधि से सहेजा जाता है। संपीड़न के परिणामस्वरूप उत्पन्न छवि संग्रहण आकार और छवि गुणवत्ता के बीच संतुलन बनाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | JPEG File Interchange Format (.jfif) एक इमेज है जिसे प्लेटफ़ॉर्मों के बीच तेज़ आदान-प्रदान के लिए विकसित किया गया था। यह फ़ॉर्मेट JPEG संपीड़न का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Portable Network Graphic (.png) एक प्रकार का रास्टर इमेज फ़ाइल फ़ॉर्मेट है जो लॉसलेस संपीड़न का उपयोग करता है। यह फ़ॉर्मेट Graphics Interchange Format (GIF) के विकल्प के रूप में बनाया गया था और इसमें कोई कॉपीराइट प्रतिबंध नहीं है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Graphical Interchange Format File (.gif) एक प्रकार की अत्यधिक संपीड़ित इमेज है। प्रत्येक इमेज के लिए GIF आमतौर पर प्रति पिक्सेल 8 बिट्स और कुल 256 रंगों की अनुमति देता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Animated Portable Network Graphic (.apng) PNG फ़ॉर्मेट का एक विस्तार है जो एनीमेशन का समर्थन करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | Bitmap Image File (.bmp) का उपयोग बिटमैप डिजिटल छवियों को संग्रहीत करने के लिए किया जाता है। ये छवियां ग्राफ़िक्स एडाप्टर से स्वतंत्र होती हैं और इन्हें डिवाइस इंडिपेंडेंट बिटमैप (DIB) फ़ाइल फ़ॉर्मेट भी कहा जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA) का उपयोग TRUEVISION द्वारा विकसित बिटमैप डिजिटल छवियों को संग्रहीत करने के लिए किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | Icon File (.ico) इमेज फ़ाइल प्रकार हैं जो माइक्रोसॉफ्ट विंडोज पर एप्लिकेशन का प्रतिनिधित्व करने के लिए आइकन के रूप में उपयोग किए जाते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | JPEG 2000 Core Image File (.jp2) एक इमेज कोडिंग सिस्टम और अत्याधुनिक इमेज संपीड़न मानक है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | JPEG 2000 इमेज फ़ाइल (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | JPEG 2000 इमेज फ़ाइल (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | JPEG 2000 इमेज फ़ाइल (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | JPEG 2000 कोड स्ट्रीम (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | JPEG 2000 कोड स्ट्रीम (.j2k) एक इमेज है जिसे DCT संपीड़न के बजाय वेवलेट संपीड़न का उपयोग करके संपीड़ित किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | JPEG 2000 कोड स्ट्रीम (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | डिवाइस इंडिपेंडेंट बिटमैप फ़ाइल (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Windows Metafile (.wmf) माइक्रोसॉफ्ट विंडोज मेटाफाइल (WMF) को दर्शाता है जिसका उपयोग वेक्टर और बिटमैप-फ़ॉर्मेट छवि डेटा को संग्रहीत करने के लिए किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Compressed Windows Metafile (.wmz) माइक्रोसॉफ्ट विंडोज मेटाफाइल (WMF) को GZIP आर्काइव में संकुचित करके दर्शाता है - वेक्टर और बिटमैप-फ़ॉर्मेट छवि डेटा को संग्रहीत करने के लिए। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Enhanced Windows Metafile (.emf) ग्राफ़िकल छवियों को डिवाइस-स्वतंत्र रूप से दर्शाता है। EMF के मेटाफाइल में क्रमबद्ध क्रम में परिवर्तनशील लंबाई के रिकॉर्ड होते हैं जो किसी भी आउटपुट डिवाइस पर पार्स करने के बाद संग्रहीत छवि को रेंडर कर सकते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Enhanced Windows Metafile compressed (.emz) ग्राफ़िकल छवियों को GZIP द्वारा डिवाइस-स्वतंत्र रूप से संकुचित करके दर्शाता है। EMF के मेटाफाइल में क्रमबद्ध क्रम में परिवर्तनशील लंबाई के रिकॉर्ड होते हैं जो किसी भी आउटपुट डिवाइस पर पार्स करने के बाद संग्रहीत छवि को रेंडर कर सकते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | WebP Image (.webp) एक आधुनिक रास्टर वेब इमेज फ़ाइल फ़ॉर्मेट है जो लॉसलेस और लॉसी संपीड़न पर आधारित है। यह समान इमेज गुणवत्ता प्रदान करता है जबकि इमेज आकार को काफी कम करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | Digital Negative Specification (.dng) एक डिजिटल कैमरा इमेज फ़ॉर्मेट है जिसका उपयोग रॉ फ़ाइलों को संग्रहीत करने के लिए किया जाता है। इसे एडोबी ने सितंबर 2004 में विकसित किया था। यह मूलतः डिजिटल फ़ोटोग्राफी के लिए विकसित किया गया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | CorelDraw Vector Graphic Drawing (.cdr) एक वेक्टर ड्रॉइंग इमेज फ़ाइल है जो मूल रूप से CorelDRAW के साथ बनाई जाती है ताकि एन्कोडेड और संकुचित डिजिटल इमेज को संग्रहीत किया जा सके। ऐसी ड्रॉइंग फ़ाइल में टेक्स्ट, लाइन्स, शैप्स, इमेज, रंग और इफ़ेक्ट्स होते हैं जो इमेज सामग्री के वेक्टर प्रतिनिधित्व के लिए होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx) एक ड्रॉइंग इमेज फ़ाइल है जिसमें वेक्टर ग्राफ़िक्स और बिटमैप ग्राफ़िक्स दोनों हो सकते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | DjVu Image (.djvu) एक ग्राफ़िक्स फ़ाइल फ़ॉर्मेट है जो स्कैन किए गए दस्तावेज़ों और पुस्तकों के लिए अभिप्रेत है, विशेष रूप से उन में जिनमें टेक्स्ट, ड्रॉइंग, इमेज और फ़ोटोग्राफ़ का संयोजन होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Computer Graphics Metafile (.cgm) एक मुफ्त, प्लेटफ़ॉर्म-स्वतंत्र, अंतर्राष्ट्रीय मानक मेटाफाइल फ़ॉर्मेट है जो वेक्टर ग्राफ़िक्स (2D), रास्टर ग्राफ़िक्स और टेक्स्ट को संग्रहीत और विनिमय करने के लिए उपयोग किया जाता है। CGM ऑब्जेक्ट-ओरिएंटेड दृष्टिकोण और इमेज उत्पादन के लिए कई फ़ंक्शन प्रावधानों का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Printer Command Language दस्तावेज़ (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Adobe Photoshop Document (.psd) Adobe Photoshop का मूल फ़ाइल फ़ॉर्मेट दर्शाता है जिसका उपयोग ग्राफ़िक्स डिज़ाइनिंग और विकास के लिए किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Photoshop Large Document Format (.psb) ग्राफ़िक्स डिज़ाइनिंग और विकास के लिए उपयोग किए जाने वाले Photoshop Large Document Format को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | DICOM Image (.dcm) डिजिटल इमेज को दर्शाता है जो रोगियों की मेडिकल जानकारी जैसे MRI, CT स्कैन और अल्ट्रासाउंड इमेज को संग्रहीत करता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | PostScript फ़ाइल (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | Encapsulated PostScript फ़ाइल (.eps) एक Encapsulated PostScript भाषा प्रोग्राम को वर्णित करती है जो एक पृष्ठ की उपस्थिति को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | OpenDocument Graphic फ़ाइल (.odg) Apache OpenOffice के Draw एप्लिकेशन द्वारा ड्राइंग तत्वों को वेक्टर इमेज के रूप में संग्रहीत करने के लिए उपयोग की जाती है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Flat XML ODF टेम्प्लेट (.fodg) Apache OpenOffice के Draw एप्लिकेशन द्वारा ड्राइंग तत्वों को वेक्टर इमेज के रूप में संग्रहीत करने के लिए उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | Scalable Vector Graphics फ़ाइल (.svg) एक स्केलेबल वेक्टर ग्राफ़िक्स फ़ाइल है जो इमेज की उपस्थिति को वर्णित करने के लिए XML आधारित टेक्स्ट फ़ॉर्मेट का उपयोग करती है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | Scalable Vector Graphics फ़ाइल (.svgz) एक स्केलेबल वेक्टर ग्राफ़िक्स फ़ाइल है जो इमेज की उपस्थिति को वर्णित करने के लिए XML आधारित टेक्स्ट फ़ॉर्मेट का उपयोग करती है, जिसे GZIP द्वारा संकुचित किया गया है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | OpenDocument Graphic टेम्प्लेट (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | Hypertext Markup Language फ़ाइल (.htm) वेब पेजों के लिए एक्सटेंशन है जो ब्राउज़र में प्रदर्शित होने के लिए बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | Hypertext Markup Language फ़ाइल (.html) वेब पेजों के लिए एक्सटेंशन है जो ब्राउज़र में प्रदर्शित होने के लिए बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | MHTML वेब आर्काइव (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | MIME HTML फ़ाइल (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | XML फ़ाइल (.xml). GroupDocs.Viewer के पास XML फ़ाइलों को संभालने के लिए एक विशेष प्रोसेसर है, दस्तावेज़ देखें। |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | OneNote दस्तावेज़ (.one) Microsoft OneNote एप्लिकेशन द्वारा बनाया जाता है। OneNote आपको एप्लिकेशन का उपयोग करके जानकारी इकट्ठा करने देता है जैसे आप नोट्स लेने के लिए अपने ड्राफ्टपैड का उपयोग कर रहे हों। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | Portable Document Format फ़ाइल (.pdf) 1990 के दशक में Adobe द्वारा बनाई गई दस्तावेज़ का प्रकार है। इस फ़ाइल फ़ॉर्मेट का उद्देश्य दस्तावेज़ों और अन्य संदर्भ सामग्री को एक ऐसे फ़ॉर्मेट में प्रस्तुत करना था जो एप्लिकेशन सॉफ़्टवेयर, हार्डवेयर और ऑपरेटिंग सिस्टम से स्वतंत्र हो। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | XML Paper Specification फ़ाइल (.xps) पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो Microsoft द्वारा बनाई गई XML Paper Specifications पर आधारित हैं। इस फ़ॉर्मेट को Microsoft ने EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया और यह PDF फ़ाइल फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, उपस्थिति और प्रिंटिंग जानकारी में XML का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | OpenXPS फ़ाइल (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | LaTeX स्रोत दस्तावेज़ (.tex) एक भाषा है जिसमें प्रोग्रामिंग और मार्क‑अप दोनों विशेषताएँ शामिल हैं, जिसका उपयोग दस्तावेज़ टाइपसेट करने के लिए किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | Open Fixed-layout दस्तावेज़ (OFD) फ़ॉर्मेट, जो GB/T 33190-2016 द्वारा परिभाषित है, चीनी सार्वजनिक संस्थानों में PDF को बदलने का लक्ष्य रखता है। |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | PowerPoint प्रस्तुति (.ppt) PowerPoint फ़ाइल को दर्शाता है जिसमें स्लाइड शो के रूप में प्रदर्शित करने के लिए स्लाइडों का संग्रह होता है। यह Microsoft PowerPoint 97-2003 द्वारा उपयोग किए जाने वाले बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | PowerPoint Open XML प्रस्तुति (.pptx) लोकप्रिय Microsoft PowerPoint एप्लिकेशन द्वारा बनाई गई प्रस्तुति फ़ाइलें हैं। पहले के PPT बाइनरी फ़ॉर्मेट के विपरीत, PPTX फ़ॉर्मेट Microsoft PowerPoint के ओपन XML प्रस्तुति फ़ाइल फ़ॉर्मेट पर आधारित है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | PowerPoint स्लाइड शो (.pps) Microsoft PowerPoint का उपयोग करके स्लाइड शो उद्देश्य के लिए बनाई जाती हैं। PPS फ़ाइल को पढ़ना और बनाना Microsoft PowerPoint 97-2003 द्वारा समर्थित है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | PowerPoint Open XML स्लाइड शो (.ppsx) फ़ाइलें Microsoft PowerPoint 2007 और उससे ऊपर के संस्करणों का उपयोग करके स्लाइड शो उद्देश्य के लिए बनाई जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | OpenDocument प्रस्तुति (.odp) OpenOffice.org द्वारा OASISOpen मानक में उपयोग किए जाने वाले प्रस्तुति फ़ाइल फ़ॉर्मेट को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | OpenDocument प्रस्तुति (.fodp) OpenDocument फ्लैट XML प्रस्तुति को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | PowerPoint टेम्प्लेट (.pot) Microsoft PowerPoint टेम्प्लेट फ़ाइलों को दर्शाता है जो PowerPoint 97-2003 संस्करणों द्वारा बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML मैक्रो-सक्षम प्रस्तुति वह मैक्रो-सक्षम प्रस्तुति फ़ाइलें हैं जो Microsoft PowerPoint 2007 या उससे उच्च संस्करणों द्वारा बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML प्रस्तुति टेम्प्लेट (.potx) Microsoft PowerPoint टेम्प्लेट प्रस्तुतियों को दर्शाता है जो Microsoft PowerPoint 2007 और उसके बाद के संस्करणों द्वारा बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML मैक्रो-सक्षम प्रस्तुति टेम्प्लेट (.potm) Microsoft PowerPoint टेम्प्लेट फ़ाइलें हैं जिनमें मैक्रो समर्थन होता है। POTM फ़ाइलें PowerPoint 2007 या उससे ऊपर के संस्करणों द्वारा बनाई जाती हैं और इनमें डिफ़ॉल्ट सेटिंग्स होती हैं जिन्हें आगे की प्रस्तुति फ़ाइलें बनाने के लिए उपयोग किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML मैक्रो-सक्षम स्लाइड (.ppsm) Microsoft PowerPoint 2007 या उससे उच्च संस्करणों द्वारा बनाई गई मैक्रो-सक्षम स्लाइड शो फ़ाइल फ़ॉर्मेट को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument प्रस्तुति टेम्प्लेट (.otp) OASIS OpenDocument मानक फ़ॉर्मेट में अनुप्रयोगों द्वारा बनाई गई प्रस्तुति टेम्प्लेट फ़ाइलों को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel स्प्रेडशीट (.xls) Excel बाइनरी फ़ाइल फ़ॉर्मेट को दर्शाता है। ऐसी फ़ाइलें Microsoft Excel के साथ-साथ OpenOffice Calc या Apple Numbers जैसे समान स्प्रेडशीट प्रोग्रामों द्वारा भी बनाई जा सकती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) Excel बाइनरी फ़ाइल फ़ॉर्मेट को दर्शाता है। ऐसी फ़ाइलें Microsoft Excel के साथ-साथ OpenOffice Calc या Apple Numbers जैसे समान स्प्रेडशीट प्रोग्रामों द्वारा भी बनाई जा सकती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple Numbers Excel जैसी बाइनरी फ़ाइल फ़ॉर्मेट को दर्शाता है। ऐसी फ़ाइलें Apple Numbers एप्लिकेशन द्वारा बनाई जा सकती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML स्प्रेडशीट (.xlsx) Microsoft Excel दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है जिसे Microsoft ने Microsoft Office 2007 के रिलीज़ के साथ पेश किया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML मैक्रो-सक्षम स्प्रेडशीट (.xlsm) मैक्रो का समर्थन करने वाली स्प्रेडशीट फ़ाइलों का एक प्रकार है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel बाइनरी स्प्रेडशीट (.xlsb) Excel बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है, जो रिकॉर्ड्स और संरचनाओं का संग्रह है जो Excel वर्कबुक की सामग्री को परिभाषित करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | कॉमा सेपरेटेड वैल्यूज़ फ़ाइल (.csv) साधारण टेक्स्ट फ़ाइलों को दर्शाता है जिनमें कॉमा द्वारा अलग किए गए डेटा रिकॉर्ड होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | टैब सेपरेटेड वैल्यूज़ फ़ाइल (.tsv) टैब द्वारा अलग किए गए डेटा को साधारण टेक्स्ट फ़ॉर्मेट में दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument स्प्रेडशीट (.ods) OpenDocument स्प्रेडशीट दस्तावेज़ फ़ॉर्मेट को दर्शाता है जिसे उपयोगकर्ता संपादित कर सकते हैं। डेटा ODF फ़ाइल के भीतर पंक्तियों और स्तंभों में संग्रहीत होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument फ्लैट XML स्प्रेडशीट (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument स्प्रेडशीट टेम्प्लेट (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel ऐड‑इन (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel मैक्रो-सक्षम टेम्प्लेट (.xltm) उन फ़ाइलों को दर्शाता है जो Microsoft Excel द्वारा मैक्रो-सक्षम टेम्प्लेट फ़ाइलों के रूप में उत्पन्न की जाती हैं। XLTM फ़ाइलें संरचना में XLTX के समान हैं, सिवाय इसके कि बाद वाली मैक्रो के साथ टेम्प्लेट फ़ाइलें बनाने का समर्थन नहीं करती। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel टेम्प्लेट (.xlt) वे टेम्प्लेट फ़ाइलें हैं जो Microsoft Excel, जो Microsoft Office सूट का हिस्सा है, द्वारा बनाई जाती हैं। Microsoft Office 97-2003 नई XLT फ़ाइलें बनाने और इन्हें खोलने का समर्थन करता था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML स्प्रेडशीट टेम्प्लेट (.xltx) Microsoft Excel टेम्प्लेट को दर्शाता है जो Office OpenXML फ़ाइल फ़ॉर्मेट विनिर्देशों पर आधारित हैं। इसका उपयोग एक मानक टेम्प्लेट फ़ाइल बनाने के लिए किया जाता है जिसे XLSX फ़ाइलें उत्पन्न करने के लिए उपयोग किया जा सकता है, जो XLTX फ़ाइल में निर्दिष्ट समान सेटिंग्स प्रदर्शित करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc स्प्रेडशीट (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Microsoft Project फ़ाइल (.mpp) एक Microsoft Project डेटा फ़ाइल है जो परियोजना प्रबंधन से संबंधित जानकारी को एकीकृत तरीके से संग्रहीत करती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Microsoft Project टेम्प्लेट (.mpt) बुनियादी जानकारी और संरचना के साथ .MPP फ़ाइलें बनाने के लिए दस्तावेज़ सेटिंग्स भी शामिल करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Microsoft Project Exchange फ़ाइल (.mpx) एक ASCII फ़ाइल फ़ॉर्मेट है जो Microsoft Project (MSP) और अन्य अनुप्रयोगों जैसे Primavera Project Planner, Sciforma और Timerline Precision Estimating के बीच परियोजना जानकारी के स्थानांतरण के लिए उपयोग होती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | ActionScript फ़ाइल (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | ActionScript फ़ाइल (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | Assembly भाषा स्रोत कोड फ़ाइल (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | DOS बैच फ़ाइल (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | C/C++ स्रोत कोड फ़ाइल (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | C++ स्रोत कोड फ़ाइल (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | CMake फ़ाइल (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | C++ स्रोत कोड फ़ाइल (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | C# स्रोत कोड फ़ाइल (.cs) C# प्रोग्रामिंग भाषा की स्रोत कोड फ़ाइल है। इसे Microsoft ने .NET फ्रेमवर्क के साथ उपयोग के लिए पेश किया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Visual Basic प्रोजेक्ट आइटम फ़ाइल (.vb) Visual Basic भाषा में बनाई गई स्रोत कोड फ़ाइल है, जिसे Microsoft ने .NET अनुप्रयोगों के विकास के लिए बनाया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें। |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | कैस्केडिंग स्टाइल शीट (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | C++ स्रोत कोड फ़ाइल (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | पैच फ़ाइल (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Ruby ERB स्क्रिप्ट (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | Groovy स्रोत कोड फ़ाइल (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | C/C++/Objective-C हेडर फ़ाइल (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | Haml स्रोत कोड फ़ाइल (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | C++ हेडर फ़ाइल (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | Java स्रोत कोड फ़ाइल (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | JavaScript फ़ाइल (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | JavaScript ऑब्जेक्ट नोटेशन फ़ाइल (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | LESS स्टाइल शीट (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | लॉग फ़ाइल (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | Objective-C कार्यान्वयन फ़ाइल (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Xcode मेकफ़ाइल स्क्रिप्ट (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | Markdown दस्तावेज़ फ़ाइल (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | ML स्रोत कोड फ़ाइल (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | Objective-C++ स्रोत फ़ाइल (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | PHP स्रोत कोड फ़ाइल (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Perl स्क्रिप्ट (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | Java प्रॉपर्टी फ़ाइल (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Python स्क्रिप्ट (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Ruby स्रोत कोड (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | reStructuredText फ़ाइल (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | Syntactically Awesome StyleSheets फ़ाइल (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | Scala स्रोत कोड फ़ाइल (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | Scheme स्रोत कोड फ़ाइल (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | सामान्य स्क्रिप्ट फ़ाइल (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Bash शेल स्क्रिप्ट (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | Standard ML स्रोत कोड फ़ाइल (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | Structured Query Language डेटा फ़ाइल (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | Vim सेटिंग्स फ़ाइल (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | YAML दस्तावेज़ (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Microsoft Word दस्तावेज़ (.doc) Microsoft Word या अन्य वर्ड प्रोसेसिंग दस्तावेज़ों द्वारा बाइनरी फ़ाइल स्वरूप में उत्पन्न दस्तावेज़ों को दर्शाता है। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए यहाँ। |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Microsoft Word Open XML दस्तावेज़ (.docx) Microsoft Word दस्तावेज़ों के लिए एक प्रसिद्ध स्वरूप है। यह 2007 में Microsoft Office 2007 के रिलीज़ के साथ प्रस्तुत किया गया, जिसमें इस नए दस्तावेज़ स्वरूप की संरचना साधारण बाइनरी से XML और बाइनरी फ़ाइलों के संयोजन में बदल दी गई। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए यहाँ। |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Microsoft Compiled HTML Help फ़ाइल (.chm) HELP (किसी एप्लिकेशन के लिए दस्तावेज़) दस्तावेज़ों के लिए एक प्रसिद्ध स्वरूप है। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए यहाँ। |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Word Open XML मैक्रो-सक्षम दस्तावेज़ (.docm) Microsoft Word 2007 या उससे उच्च संस्करण द्वारा उत्पन्न दस्तावेज़ है जिसमें मैक्रो चलाने की क्षमता होती है। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए यहाँ। |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Word दस्तावेज़ टेम्पलेट (.dot) Microsoft Word द्वारा बनाए गए टेम्पलेट फ़ाइलें हैं जिनमें आगे के DOC या DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए यहाँ। |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML Document Template (.dotx) माइक्रोसॉफ्ट वर्ड द्वारा बनाए गए टेम्पलेट फ़ाइलें हैं, जिनमें आगे के DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ और जानें। |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML Macro-Enabled Document Template (.dotm) माइक्रोसॉफ्ट वर्ड 2007 या उसके बाद के संस्करणों से बनाई गई टेम्पलेट फ़ाइल को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ और जानें। |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Rich Text Format File (.rtf) फ़ॉर्मेटेड टेक्स्ट और ग्राफ़िक्स को एन्कोड करने की एक विधि को दर्शाता है, जिसका उपयोग अनुप्रयोगों में किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ और जानें। |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Plain Text File (.txt) एक टेक्स्ट दस्तावेज़ को दर्शाता है जिसमें लाइनों के रूप में साधारण टेक्स्ट होता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ और जानें। |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument Text Document (.odt) उन दस्तावेज़ों का प्रकार है जो शब्द प्रसंस्करण अनुप्रयोगों द्वारा बनाए जाते हैं और OpenDocument Text File फ़ॉर्मेट पर आधारित होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ और जानें। |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument Document Template (.ott) उन टेम्पलेट दस्तावेज़ों को दर्शाता है जो OASIS के OpenDocument मानक फ़ॉर्मेट के अनुरूप अनुप्रयोगों द्वारा उत्पन्न किए जाते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ और जानें। |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard File (.vcf) संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय सूचना विनिमय अनुप्रयोगों के बीच डेटा आदान-प्रदान के लिए व्यापक रूप से उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ और जानें। |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai) Adobe Illustrator ड्रॉइंग्स के लिए एक फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ और जानें। |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell script module (.psm1) PowerShell मॉड्यूल स्क्रिप्ट्स के लिए एक फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ और जानें। |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell script file (.ps1) Windows PowerShell Cmdlet फ़ाइलों के लिए एक फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ और जानें। |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell script module manifest (.psd1) PowerShell मॉड्यूल मैनिफेस्ट स्क्रिप्ट्स के लिए एक फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ और जानें। |

### उदाहरण

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# दस्तावेज़ लोड करते समय फ़ाइल प्रकार (जैसे, Markdown) निर्दिष्ट करें
load_options = LoadOptions(FileType.MD)

# दस्तावेज़ को PDF में रेंडर करें
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### साथ में देखें
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
