---
title: "GroupDocs.Viewer.Interfaces"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "यह नेमस्पेस आउटपुट दस्तावेज़ और उसकी संसाधनों को इंस्टैंसिएट और रिलीज़ करने के लिए इंटरफ़ेस प्रदान करता है।"
type: docs
weight: 60
url: /hi/net/groupdocs.viewer.interfaces/
---

यह नेमस्पेस आउटपुट दस्तावेज़ और उसकी संसाधनों को इंस्टैंशिएट और रिलीज़ करने के लिए इंटरफ़ेस प्रदान करता है।

## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [CreateFileStream](./createfilestream) | आउटपुट फ़ाइल डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि को दर्शाता है। |
| [CreatePageStream](./createpagestream) | आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि को दर्शाता है। |
| [CreateResourceStream](./createresourcestream) | आउटपुट HTML संसाधन डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि को दर्शाता है। |
| [CreateResourceUrl](./createresourceurl) | HTML संसाधन के लिए URL बनाने वाली विधि को दर्शाता है। |
| [ReleaseFileStream](./releasefilestream) | स्ट्रीम को रिलीज़ करता है जो [`CreateFileStream`](../groupdocs.viewer.interfaces/createfilestream) डेलीगेट से जुड़ी विधि द्वारा इंस्टैंसिएट किया गया था। |
| [ReleasePageStream](./releasepagestream) | स्ट्रीम को रिलीज़ करता है जो [`CreatePageStream`](../groupdocs.viewer.interfaces/createpagestream) डेलीगेट से जुड़ी विधि द्वारा इंस्टैंसिएट किया गया था। |
| [ReleaseResourceStream](./releaseresourcestream) | स्ट्रीम को रिलीज़ करता है जो [`CreateResourceStream`](../groupdocs.viewer.interfaces/createresourcestream) डेलीगेट से जुड़ी विधि द्वारा इंस्टैंसिएट किया गया था। |
## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [IFileStreamFactory](./ifilestreamfactory) | आउटपुट फ़ाइल स्ट्रीम को इंस्टैंसिएट और रिलीज़ करने के लिए आवश्यक विधियों को परिभाषित करता है। |
| [IPageStreamFactory](./ipagestreamfactory) | आउटपुट पेज स्ट्रीम को इंस्टैंसिएट और रिलीज़ करने के लिए आवश्यक विधियों को परिभाषित करता है। |
| [IResourceStreamFactory](./iresourcestreamfactory) | संसाधन URL बनाने, आउटपुट HTML संसाधन स्ट्रीम को इंस्टैंसिएट और रिलीज़ करने के लिए आवश्यक विधियों को परिभाषित करता है। |

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
